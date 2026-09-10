# Wattiq 360 — Sistema de Subagentes de Diagnóstico Comercial

Sete subagentes de Claude Code que rodam o diagnóstico comercial **Wattiq 360** em
empresas integradoras de energia solar: do raio-x da operação até o roteiro da reunião
de apresentação.

O objetivo do diagnóstico é achar **onde a empresa está perdendo dinheiro** e recomendar
a combinação certa de agente de marketing, agente comercial (SDR e follow-up) e mentoria
comercial. Não é um relatório bonito — é a base de uma proposta que o dono precisa
conseguir contestar número por número.

## Os dois eixos

O diagnóstico roda em dois eixos independentes, e os sete agentes cobrem os dois:

**Conversão** — o funil vaza? Entrada, resposta, qualificação, proposta, fechamento,
cadência. Vem do playbook oficial.

**Posicionamento** — a empresa é uma instaladora de commodity ou uma firma de engenharia?
Ticket, margem, LTV, CAC, defensabilidade. Vem dos 9 insights de top players.

Por que os dois: funil perfeito com posicionamento de commodity converte bem e **perde
margem em toda venda**. Posicionamento de engenharia com funil ruim tem o que cobrar e
não chega a cobrar. Um diagnóstico que só olha funil recomenda agente de IA para uma
empresa cujo problema é que ela vende furo de telhado.

---

## Instalação

```bash
git clone https://github.com/jonasmoritello1011-byte/Wattiq360.git
cd Wattiq360
claude
```

Os agentes ficam em `.claude/agents/` e o Claude Code os carrega sozinho ao abrir o
projeto. Confirme com:

```
/agents
```

Devem aparecer os sete: `diagnostico`, `perdas-financeiras`, `oportunidades-regionais`,
`perfil-cliente-ideal`, `analise-concorrentes`, `plano-ideal`, `apresentacao-executiva`.

**Para usar em qualquer pasta**, copie os agentes para o diretório do usuário:

```bash
mkdir -p ~/.claude/agents && cp .claude/agents/*.md ~/.claude/agents/
```

Nesse caso copie também `referencia/playbook-wattiq360.md` para junto do projeto onde
for rodar — todos os agentes leem esse arquivo.

---

## Estrutura

```
.claude/agents/                 os 7 subagentes
referencia/
  playbook-wattiq360.md         eixo de conversão — lido por todos os agentes
  insights-top-players.md       eixo de posicionamento — lido por todos os agentes
  wattiq360-playbook-v2.pdf     playbook original
diagnosticos/
  _modelo/00-briefing.md        modelo de briefing para copiar
  <empresa>/                    uma pasta por cliente diagnosticado
    00-briefing.md
    01-diagnostico.md
    ...
    07-apresentacao-executiva.md
```

Cada agente **lê os arquivos dos anteriores e grava o seu**. É assim que o contexto
atravessa a cadeia: subagente não enxerga a conversa dos outros, só o que está em disco.
Por isso todo agente termina com uma seção **Passagem de bastão** — o resumo curto
escrito para o próximo da fila.

---

## Como rodar

### Passo 0 — briefing

```bash
mkdir -p diagnosticos/solarluz && cp diagnosticos/_modelo/00-briefing.md diagnosticos/solarluz/
```

Preencha com o que veio da call. Campo sem resposta fica "não sei" — os agentes tratam
isso como lacuna e devolvem a pergunta a fazer. Não invente número aqui: um chute no
briefing contamina os sete relatórios.

### Passos 1 e 2 — sequenciais

```
Rode o diagnóstico da SolarLuz com base no briefing em diagnosticos/solarluz/
```
```
Calcule as perdas financeiras da SolarLuz
```

O agente 2 depende do 1. Rodar fora de ordem faz o agente parar e pedir o anterior.

### Passos 3, 4 e 5 — em paralelo

Peça os três na mesma mensagem; o Claude Code dispara os subagentes juntos:

```
Para a SolarLuz, rode em paralelo: oportunidades regionais, perfil de cliente ideal
e análise de concorrentes.
```

Os três só dependem do agente 1 e usam WebSearch/WebFetch. Rodando juntos, esta é a
etapa mais lenta do diagnóstico — em paralelo ela cabe numa pausa de café.

### Passos 6 e 7 — sequenciais

```
Monte o plano ideal da SolarLuz
```
```
Transforme o plano da SolarLuz em apresentação executiva
```

### Ordem completa

| # | Agente | Depende de | Web | Entrega |
|---|---|---|---|---|
| 1 | `diagnostico` | briefing | não | Raio-X dos dois eixos, funil, gargalo dominante |
| 2 | `perdas-financeiras` | 1 | não | perdas em R$, meta reversa, oportunidades de posicionamento |
| 3 | `oportunidades-regionais` | 1 | **sim** | canais de aquisição, priorizando os de menor CAC |
| 4 | `perfil-cliente-ideal` | 1 | **sim** | ICP (preço × projeto) + roteiro do SDR |
| 5 | `analise-concorrentes` | 1 | **sim** | mapa local, lacunas e teste de commoditização |
| 6 | `plano-ideal` | 1–5 | não | proposta em SPIN, investimento, 90 dias |
| 7 | `apresentacao-executiva` | 6 | não | roteiro slide a slide com a fala |

Os agentes 3, 4 e 5 são independentes entre si: **rodam em paralelo**.

---

## Acionamento por linguagem natural

Não é preciso decorar nome de agente. As descrições foram escritas para o Claude Code
escolher sozinho. Frases que funcionam:

- "onde essa empresa está perdendo dinheiro?" → `perdas-financeiras`
- "onde eles podem buscar mais cliente na região?" → `oportunidades-regionais`
- "quem é o cliente ideal deles?" → `perfil-cliente-ideal`
- "contra quem eles competem na cidade?" → `analise-concorrentes`
- "o que a gente vende pra eles?" → `plano-ideal`
- "monta os slides da reunião" → `apresentacao-executiva`

Para forçar um agente específico, chame pelo nome: "use o agente `plano-ideal`".

---

## As regras que valem para os sete

**1. Todo número vem com a premissa colada.** Formato obrigatório:

```
Perda estimada: R$ 28.400/mês
premissa: 38 propostas/mês × 62% sem 2º contato × 12% recuperáveis × R$ 26.000 × 22% margem
confiança: baixa-média — os dois fatores do meio são estimativa, não dado do CRM
```

Confiança é sempre uma de três: **alta** (dado do cliente), **média** (dado cruzado com
benchmark), **baixa** (estimativa de mercado). Estimativa nunca é apresentada como fato.

**2. Benchmark é referência, não garantia.** Os números do playbook (23% de conversão
respondendo em 1 minuto, 1% depois de um dia, 7% das empresas respondendo em 5 minutos)
sempre aparecem com essa ressalva na mesma frase.

**3. Cenário conservador é o que vai para a conversa.** O agente 2 produz três cenários;
a proposta usa o mais baixo. É o mais fácil de defender e já costuma bastar.

**4. Lacuna é entregável.** Nenhum agente preenche buraco de dado com suposição para o
relatório parecer completo — ele lista a pergunta que destrava.

**5. Perda apurada e oportunidade estimada nunca somam.** Perda de funil vem de dado do
cliente e vai no total. Oportunidade de posicionamento vem de benchmark setorial, fica em
seção própria, em faixa, fora de qualquer total e fora do payback. Misturar as duas produz
um número que o dono derruba na primeira pergunta.

**6. Cada agente fecha com a passagem de bastão** para o próximo da cadeia.

**7. Tom de dono para dono.** Sem jargão de IA. Quem lê é o dono da integradora, não um
engenheiro: "responde todo lead em menos de um minuto, a qualquer hora" no lugar de
"orquestração de agentes com LLM".

**8. Limites éticos, do playbook.** Nunca escassez falsa. Nunca prometer parcela igual
ou menor que a conta sem simular com a taxa real. Projeção é projeção, nunca promessa
contratual.

---

## O que sustenta as recomendações

Os agentes não improvisam método. Todos leem os dois arquivos de `referencia/`.

`playbook-wattiq360.md` condensa o playbook oficial: o Raio-X de 10 blocos, as 6 perguntas de controle, o mapa
de gargalos, os canais de geração de demanda e a regra dos 50%, os 8 critérios de
qualificação e o cartão de oportunidade, comissão sobre margem × faturamento, a cadência
D+0 → D+15, o banco de argumentos do solar, o framework de objeção, os KPIs e o ritual
semanal.

`insights-top-players.md` traz os 9 insights de top players — projeto e engenharia acima
de instalação, leadgen por intenção ativa, SLA de 5 minutos, proposta visual, O&M embutido,
parcerias com arquitetos, follow-up técnico, o moat de relacionamento mais histórico
documentado, e o risco de commoditização por preço. Os percentuais de lá são **referência
setorial sem fonte declarada**: servem para dimensionar oportunidade e ordenar prioridade,
nunca para prometer resultado ao cliente.

Duas regras do playbook decidem quase toda recomendação do agente 6:

> **Não colocar IA em cima do caos.**
> **Não colocar mais tráfego num funil que não converte.** Processo primeiro, escala depois.

É por isso que a saída nem sempre é "contrate os três agentes". Quando o gargalo é
processo, meta ou comissão, a mentoria entra antes — e o relatório diz isso com todas
as letras.

---

## Ajustando ao seu jeito de vender

- **Preço**: nenhum agente inventa valor. O agente 6 deixa `<preencher: investimento
  mensal>` no lugar. Para automatizar, crie `referencia/tabela-precos.md` e cite-o no
  prompt: "use a tabela em referencia/tabela-precos.md".
- **Portfólio**: se a oferta mudar, edite a seção "O portfólio, mapeado nas camadas" em
  `.claude/agents/plano-ideal.md`.
- **Modelo**: os agentes 3, 4 e 5 rodam em `sonnet` (pesquisa em volume); os demais em
  `opus` (raciocínio e redação). Troque no campo `model` do frontmatter.
- **Método**: mudou o playbook ou a leitura de mercado? Atualize
  `referencia/playbook-wattiq360.md` ou `referencia/insights-top-players.md` — os sete
  agentes passam a seguir o novo, sem editar agente por agente.

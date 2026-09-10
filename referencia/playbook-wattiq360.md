# Referência canônica — Playbook Wattiq 360 (v2)

Destilado do playbook oficial (`referencia/wattiq360-playbook-v2.pdf`). **Todos os
agentes leem este arquivo antes de trabalhar.** Quando houver conflito entre o que
um agente "acha" e o que está aqui, vale o que está aqui.

> **O diagnóstico roda em dois eixos, e os dois são obrigatórios.**
> Este arquivo é o eixo de **conversão**: o funil vaza?
> `referencia/insights-top-players.md` é o eixo de **posicionamento**: a empresa é uma
> instaladora de commodity ou uma firma de engenharia?
> São independentes. Funil perfeito com posicionamento de commodity converte bem e perde
> margem em toda venda. Leia os dois antes de qualquer análise.

---

## Tese

A maioria das integradoras não precisa de mais leads. Precisa de uma operação que
transforme lead em venda de forma previsível. Cinco falhas se repetem: **ausência de
padrão, demora na resposta, qualificação fraca, meta sem causa, falta de visibilidade.**

Wattiq 360 = processo comercial + treinamento + agentes de IA. A IA aumenta velocidade
e consistência; o vendedor assume diagnóstico, apresentação, negociação e fechamento.

> **Não colocar IA em cima do caos.** Construir primeiro a máquina comercial e usar a
> IA para operar e acelerar essa máquina.

## Arquitetura de camadas

| Camada | Responsável | Objetivo |
|---|---|---|
| Geração | Marketing + IA | Gerar demanda e colocar leads no funil |
| Atendimento | Agente de IA | Responder imediatamente e iniciar a conversa |
| Qualificação | Agente de IA | Confirmar critérios mínimos e classificar o lead |
| Venda | Vendedor / closer | Diagnosticar, apresentar, negociar e fechar |
| Gestão | Dono / gestor | Acompanhar KPIs, gargalos e ritmo da meta |

**Mapeamento para a oferta comercial:**
- **Agente de Marketing** → camada Geração
- **Agente Comercial (SDR)** → camadas Atendimento + Qualificação
- **Agente Comercial (Follow-up)** → cadência pós-proposta
- **Mentoria Comercial** → camadas Venda + Gestão (papel do vendedor, comissão, roteiros, KPIs, ritual semanal)

---

## 1. Raio-X — os 10 blocos (últimos 30 dias, números reais)

| # | Bloco | Pergunta |
|---|---|---|
| 1 | Leads | Quantos leads entraram? |
| 2 | Resposta | Tempo médio até a primeira resposta? |
| 3 | Contato | Quantos leads tiveram contato efetivo? |
| 4 | Qualificação | Quantos foram qualificados? |
| 5 | Reuniões/visitas | Quantos diagnósticos aconteceram? |
| 6 | Propostas | Quantas propostas foram apresentadas? |
| 7 | Fechamento | Quantos contratos foram assinados? |
| 8 | Ticket | Qual o ticket médio? |
| 9 | Perdas | 3 principais motivos de perda? |
| 10 | Pessoas | Quem hoje é responsável por vender? |

**Funil canônico:** leads → contato efetivo → qualificados → diagnósticos → propostas → contratos.

### As 6 perguntas de controle
1. Todo lead recebe resposta em menos de 5 minutos?
2. Existe um roteiro único de qualificação?
3. O vendedor sabe exatamente quando um lead está pronto para atenção humana?
4. A proposta é apresentada em reunião ou apenas enviada por WhatsApp?
5. Existe uma cadência estruturada depois da proposta?
6. O CRM mostra em qual etapa cada oportunidade está parada?

Quantos "não" = tamanho do problema.

### Por que é venda complexa
Ticket alto, decisão racional + emocional, múltiplos influenciadores (cônjuge, contador,
síndico), necessidade de financiamento, comprador compara em média mais de três
fornecedores antes de decidir.

---

## 2. Benchmarks do material-base

> **Princípio Wattiq:** benchmarks de conversão são referências do material-base e
> **não garantias de resultado**. Todo agente que usar um destes números precisa dizer
> isso na mesma frase.

| Número | Significado |
|---|---|
| **23%** | conversão respondendo em até 1 minuto no WhatsApp |
| **1%** | conversão respondendo depois de 1 dia |
| **7%** | das empresas respondem dentro de 5 minutos |
| **6–8 tentativas em 7 dias** | cadência de follow-up de referência |
| **> 3 fornecedores** | média de comparação do comprador de solar |
| **0,5%–1% a.m.** | linhas subsidiadas de financiamento (BNDES, FNE Sol) |
| **0,99%–1,40% a.m.** | linhas comerciais (bancos, fintechs) — ~12,5% a ~18% a.a. |

---

## 3. Mapa de gargalos

O diagnóstico não termina em lista de problemas: aponta **um gargalo dominante**.
Regra: corrija primeiro a etapa que mais limita o resultado atual.

| Sintoma | Gargalo provável | Dono | Ação inicial |
|---|---|---|---|
| Poucos leads | Entrada baixa | Marketing / mídia | Aumentar geração só depois de validar o funil |
| Resposta lenta | Lead esfria | Atendimento | IA + SLA de resposta imediata |
| Qualificação baixa | Muitos curiosos avançam | IA / processo | Critérios e score antes do vendedor |
| Poucas reuniões | Qualifica mas não agenda | Vendedor / setter | Script de conexão + agendamento |
| Poucas propostas | Diagnóstico fraco | Vendedor | Roteiro de diagnóstico + visita |
| Poucos fechamentos | Proposta não converte | Closer | Apresentação, objeções, financiamento |
| Pipeline parado | Follow-up irregular | Vendedor + IA | Cadência multicanal e próximos passos |

> **Regra:** não coloque mais tráfego em um funil que não converte. Processo primeiro, escala depois.

### O gargalo que não aparece neste mapa

Este mapa cobre o eixo de conversão. Quando **todas** as etapas estão razoáveis e o
resultado ainda não vem — ou quando o motivo de perda declarado é "preço" —, o gargalo
não está no funil: está no **posicionamento**. Vá para `insights-top-players.md`, rode os
10 blocos do Raio-X de posicionamento e teste a hipótese de commoditização (insight 9)
antes de concluir que o mercado está barato.

---

## 4. Geração de demanda

| Canal | Custo | Quando priorizar |
|---|---|---|
| Mídia paga | Alto | Quando o funil já converte bem e falta só volume |
| Prospecção ativa | Médio-alto | Segmentos comerciais/industriais, onde o ticket justifica |
| Indicação de clientes | Baixo | Sempre — maior conversão e menor custo do setor |
| Parcerias | Baixo | Quando existe rede de profissionais que já atende o mesmo público |
| Base parada | Baixíssimo | Sempre, e quase sempre ignorado — orçamentos antigos e clientes instalados |

> **Regra dos 50%:** nenhum canal isolado deveria representar mais da metade das
> oportunidades de um mês — concentração é risco que só aparece quando o canal falha.

### Os 6 canais de parceria
| Parceiro | Por que funciona |
|---|---|
| Lojas de material de construção | Alcançam o cliente no momento da reforma, com orçamento do imóvel já aberto |
| Imobiliárias e corretores | Solar valoriza o imóvel — vira argumento do próprio corretor |
| Construtoras e arquitetos | Influenciam desde a planta; embutir no projeto evita retrofit |
| Contadores e consultores financeiros | Já têm confiança para falar de investimento — solar como decisão financeira |
| Outros integradores (regiões não concorrentes) | Troca de leads fora da área de cada um |
| Cooperativas e associações de classe | Energia como benefício ao associado — acesso a uma base inteira |

**Abordagem de parceiro:** "Eu ajudo [cliente do parceiro] a economizar na conta de
energia, e isso costuma reforçar a decisão de [reforma / compra do imóvel /
investimento] que ele já está considerando com você. Faz sentido eu te pagar uma
comissão por cada indicação que virar projeto?"

**Remuneração de indicação:** comissão única · comissão recorrente (sobre O&M) · combinada.

---

## 5. Qualificação (Agente SDR)

### Critérios mínimos que a IA confirma
Consumo · Titularidade · Local · Estrutura (telhado/área) · Motivação · Decisor · Prazo · Pagamento.

### Regra de conversa
- Uma pergunta por mensagem
- Explicar por que o dado é necessário
- Não pedir o que pode ser deduzido da conta de energia
- Parar quando um critério eliminatório reprovar o lead
- Registrar tudo no CRM

### Cartão de oportunidade (saída da IA para o vendedor)
Cliente · Consumo (R$/mês) · Local · Conta (recebida?) · Estrutura (foto?) · Decisor ·
Prazo · Pagamento · Motivação · Temperatura (A/B/C).

> O vendedor **não repete** as oito perguntas que a IA já fez. Ele confirma o contexto
> e conduz: conectar → confirmar contexto → aprofundar o motivo → validar intenção →
> agendar diagnóstico.

---

## 6. Papel do vendedor

**Setter** — primeiro contato, roteiro de qualificação, agenda visita técnica (IA
qualifica antes de qualquer humano entrar).
**Closer** — conduz diagnóstico, apresenta, negocia e fecha (recebe só lead qualificado
com contexto completo).
Só separe os papéis quando o volume justificar.

### Comissão: a decisão que mais afeta comportamento
- **Sobre faturamento** — dar desconto custa pouco ao vendedor; a empresa perde a diferença inteira.
- **Sobre margem de contribuição** — todo desconto reduz a comissão proporcionalmente; o vendedor defende o preço.

**Exemplo do playbook:** venda de R$ 42 mil com 4% de comissão; desconto de 8% reduz a
comissão sobre faturamento em 8%, mas reduz a comissão sobre margem em 73%.

### 4 perguntas de checagem do time
1. O vendedor sabe de cabeça quantos leads e vendas precisa este mês?
2. Sabe explicar como a própria comissão é calculada, sem perguntar?
3. Entende por que a comissão é sobre margem e não sobre faturamento?
4. Existe roteiro único, ou cada um qualifica e apresenta do próprio jeito?

### Rampa do novo vendedor
Dias 1–30: produto, roteiro, observa diagnósticos. Meta zero.
Dias 31–60: conduz com supervisão. Meta em 40%.
Dias 61–90: autonomia. Meta em 70%. Meta cheia a partir do dia 91.
Contratação: roleplay gravado de qualificação e diagnóstico revela em 20 minutos o que
a entrevista esconde.

---

## 7. O vendedor depois da qualificação — 10 etapas

Conectar · Aprofundar · Validar decisão · Diagnosticar · Agendar · Dimensionar ·
Apresentar · Negociar · Fechar · Handoff.

> **Regra de ouro:** qualificação é da IA; diagnóstico e venda são do humano.

### Roteiro do diagnóstico comercial (reunião)
Situação: "Como você chegou a buscar energia solar agora?" · Dor: "O que mais incomoda
hoje na sua conta?" · Impacto: "O que acontece se esse custo continuar subindo?" ·
Objetivo · Critério de escolha · Decisão (quem mais participa) · Prazo · Pagamento ·
Compromisso ("se fizer sentido, se sente confortável em avançar?").

**Nunca saia da reunião sem próximo passo com ação + responsável + data.**

### Visita combinada (diagnóstico e proposta na mesma visita)
1. Diagnóstico primeiro — consumo, telhado, estrutura, antes de abrir a pasta
2. Ponte verbal — "posso te mostrar um cenário real?"
3. Ajustar ao vivo se o real diferir do pré-calculado
4. Apresentar as 3 opções, mesmo na visita única
5. Não fechar por pressa se falta decisor

Erro mais comum: abrir a proposta antes de terminar o diagnóstico.

### Apresentação da proposta — 10 momentos
Retomar a dor · Mostrar diagnóstico (com premissas) · Apresentar solução · Mostrar
economia · Apresentar investimento · Comparar financiamento (parcela × conta atual) ·
Prova social · Checar entendimento · Testar decisão · Definir próximo passo.

Proposta não é PDF que viaja por WhatsApp: o cliente participa da construção da decisão.

---

## 8. Banco de argumentos (específicos do solar)

| Argumento | Como usar |
|---|---|
| Conta vira financiamento | Simular com a taxa real da linha. **Nunca prometa parcela igual ou menor sem simular.** |
| Proteção contra bandeira tarifária | Histórico de reajuste dos últimos 5 anos da concessionária local |
| Valorização do imóvel | Para quem pensa em vender em alguns anos |
| Garantia e monitoramento | Resolve o medo de "comprar e não ter suporte depois" |
| Prova social geográfica | "Um sistema parecido a duas quadras daqui" > estatística nacional |
| Janela de decisão real | Homologação, fila de instalação, validade de condição — urgência verdadeira |

> Todo argumento bom responde "por que agora, e por que com vocês?".

## 9. Técnicas de fechamento
Ancoragem de preço (3 opções: econômica, equilibrada, performance) · Contraste de
referência (parcela × conta atual) · Prova social específica · Storytelling de payback
(linha do tempo, não número seco) · Simulação ao vivo (com o cliente, não para ele) ·
Fechamento assumido (próximo passo prático).

> **Nunca use escassez falsa.** Solar vende por indicação de vizinho; uma mentira
> descoberta destrói mais indicações do que qualquer desconto gera.

## 10. Objeções — acolher → isolar → reenquadrar → confirmar

| Objeção | Pergunta | Reenquadramento |
|---|---|---|
| "Está caro" | "Caro comparado a quê?" | Investimento × conta atual e alternativas |
| "Vou pensar" | "O que você quer amadurecer: valor, prazo ou empresa?" | Descobrir a objeção real |
| "Vou pegar outros orçamentos" | "Quer que eu te mostre os pontos que vale comparar?" | Ajudar a comparar corretamente |
| "Não é o momento" | "É timing ou tem outro ponto pesando?" | Isolar a causa real |
| "Não confio" | "O que você precisaria ver para se sentir seguro?" | Prova social, garantia, processo, referência |

## 11. Cadência pós-proposta

| Quando | Objetivo | O que enviar |
|---|---|---|
| D+0 | Após proposta | Resumo + confirmação do próximo passo |
| D+1 | Valor | Retomar economia / cenário do cliente |
| D+3 | Prova | Caso de perfil semelhante |
| D+5 | Objeção | Atacar a principal dúvida identificada |
| D+7 | Decisão | Pergunta objetiva sobre avanço |
| D+15 | Reativação | Novo motivo / atualização / condição real |
| Longo prazo | Nutrição | Conteúdo e reabordagem até o timing |

Follow-up não é "viu minha mensagem?" — cada contato traz um novo motivo. A IA lembra,
dispara e registra; o vendedor entra quando há intenção, objeção relevante ou decisão.

### Checklist de fechamento
Solução confirmada · objeções isoladas · decisores envolvidos · condição comercial
definida · pagamento/financiamento definido · documentação solicitada · contrato
registrado · operação informada. O handoff é parte da venda.

---

## 12. KPIs e gestão

| KPI | Como calcular | Frequência |
|---|---|---|
| Tempo de 1ª resposta | Hora do 1º contato − entrada do lead | Diário |
| Taxa de qualificação | Qualificados ÷ leads recebidos | Semanal |
| Conversão por etapa | Saídas da etapa ÷ entradas | Semanal |
| Fechamento sobre propostas | Contratos ÷ propostas apresentadas | Semanal |
| Custo por projeto | Investimento em geração ÷ projetos | Mensal |
| Ritmo vs. meta | Realizado ÷ necessário no período | Semanal |

**Reunião semanal de 30 minutos:** estamos no ritmo da meta? qual etapa está abaixo da
referência? qual o principal motivo de perda? quem precisa de treinamento? qual ação
será testada nesta semana?

**Ficha semanal:** leads · qualificados · diagnósticos · propostas · vendas · conversão
· ticket médio · principal perda → gargalo atual, ação, responsável, prazo.

---

## 13. O método em 9 movimentos

1. Definir a meta (quantas vendas/mês?)
2. Fazer o diagnóstico (onde o funil está vazando?)
3. Calcular a **meta reversa** (quantos leads e oportunidades são necessários?)
4. Atrair demanda
5. Qualificar (IA responde, pergunta, registra, classifica)
6. Vender (humano diagnostica, apresenta, negocia)
7. Fazer follow-up (IA mantém cadência; vendedor conduz decisão)
8. Fechar e entregar (contrato → operação → pós-venda)
9. Otimizar (KPIs mostram o próximo gargalo)

> A tecnologia aumenta a velocidade. O processo cria previsibilidade. A combinação
> dos dois cria escala.

## 14. Limites éticos inegociáveis
- Nunca escassez falsa.
- Nunca prometer parcela igual ou menor que a conta sem simular com a taxa real.
- Benchmark é referência, não garantia.
- Projeção de resultado é projeção, nunca promessa contratual.

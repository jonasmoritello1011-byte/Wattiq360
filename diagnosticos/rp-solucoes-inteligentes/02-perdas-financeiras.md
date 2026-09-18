# 02 — Perdas Financeiras · RP Soluções Inteligentes

> Base: `diagnosticos/rp-solucoes-inteligentes/01-diagnostico.md` (pré-diagnóstico, agente 1)
> + `00-briefing.md` + `referencia/playbook-wattiq360.md` (eixo de conversão)
> + `referencia/insights-top-players.md` (eixo de posicionamento).
> Janela: os "últimos 30 dias" **não existem como janela medida** — o único número de
> funil é uma média relatada verbalmente, de período não especificado.
>
> **Este documento não tem o número da capa que um relatório de perdas normalmente tem,
> e o motivo é o próprio diagnóstico.** Faltam as duas variáveis que multiplicam tudo:
> **ticket médio e margem**. Sem elas, qualquer valor em reais aqui seria ticket de
> benchmark disfarçado de dado da RP — e contaminaria os agentes 3, 4 e 5 da cadeia.
>
> O que este documento entrega no lugar: **as contas montadas até o último fator, com a
> lacuna nomeada dentro da fórmula**, réguas de sensibilidade que o dono preenche em
> minutos na próxima call, e a separação rígida entre o que é perda apurada (**nenhuma,
> hoje**) e o que é oportunidade estimada por benchmark setorial (**dimensionável só como
> multiplicador, nunca em reais**).

---

## Aviso obrigatório — as três regras que governam este documento

**Regra 1 — nenhuma perda em reais foi calculada, porque nenhuma é calculável.**
Perda = volume × conversão × **ticket** × **margem**. A RP não informou ticket nem margem,
e não informou nenhum volume de funil exceto contratos. Dois dos quatro fatores de toda
conta estão vazios, e um terceiro (volume) só existe na última etapa. Estimar ticket a
partir de benchmark setorial e apresentar o produto como "perda da RP" seria o erro mais
caro que esta cadeia pode cometer, porque o número viraria premissa de todos os documentos
seguintes.

**Regra 2 — os dois eixos não se somam.**

| | **Eixo 1 — Perdas de conversão e margem** | **Eixo 2 — Oportunidades de posicionamento** |
|---|---|---|
| O que é | Dinheiro que já entrou e vazou | Dinheiro que a empresa talvez pudesse cobrar |
| De onde vem o número | Dado do cliente | Referência setorial de top players, **sem fonte declarada** |
| Status na RP | **Não calculável hoje** — falta ticket e margem | **Dimensionável só como multiplicador**, não em R$ |
| Entra em total? | Não há total | **Não, em nenhum total, nunca** |
| Entra em payback? | Não há payback calculável | **Não** |

**Regra 3 — régua não é perda.**
Onde a aritmética é limpa mas a frequência é desconhecida, entrego uma **régua de
sensibilidade** ("cada R$ 1.000 de X custa R$ Y por mês"). Régua não é acusação de que a
perda existe: é o instrumento para o dono medir, com um número que só ele tem. Toda régua
está marcada com **frequência: desconhecida**.

---

# 1. O número da capa

**A perda apurada da RP Soluções Inteligentes hoje é R$ 0 — não porque a operação não
perca dinheiro, mas porque a empresa não tem como saber quanto perde. Nenhuma das nove
perdas que este agente investiga é calculável com os dados existentes, e a razão é sempre
a mesma: falta ticket médio e falta margem.**

O que dá para afirmar com confiança alta, e é o que o dono precisa ouvir:

> **A RP faz ~600 vendas por ano (se as 50/mês forem realizadas), divide metade do lucro
> de cada venda de 5 dos seus 8 canais comerciais, e não sabe quanto é esse lucro.**
> Não é uma perda: é uma exposição. E ela é a única coisa neste relatório que não depende
> de mais nenhum dado para ser reconhecida como problema — só para ser medida.

**Uma frase que este documento se recusa a escrever:** "a RP perde R$ X mil por mês".
Qualquer valor aqui seria construído sobre um ticket que ninguém informou.

**E uma honestidade que precisa entrar na conversa:** é possível que, ao chegar o ticket
e a margem, algumas dessas perdas se revelem **pequenas**. Uma operação que vive de
indicação com 6,25 vendas por vendedor/mês pode estar perdendo muito menos no topo do
funil do que a média do setor. Não sei, e quem disser que sabe está chutando.

---

# 2. Tabela resumo — o que está calculável, o que está bloqueado

## 2.1 Perdas de conversão e margem

| # | Perda investigada | Valor | Status | O que falta |
|---|---|---|---|---|
| P1 | Repasse de 50% do lucro sem apuração de custo por venda | **Não calculável** · régua em 3.1 | **Bloqueada** | Custo por venda apurado · ticket · split franqueado × interno |
| P2 | Lead não respondido | **Não calculável** | **Bloqueada** | Nº de leads · % sem resposta · ticket · margem |
| P3 | Resposta lenta (janela de 5 min) | **Não calculável** | **Bloqueada** | Tempo de 1ª resposta · nº de leads · ticket · margem |
| P4 | Qualificação fraca (hora de vendedor com curioso) | **Não calculável** | **Bloqueada** | Nº de leads · custo/hora do vendedor · tempo por atendimento |
| P5 | Proposta sem cadência D+0→D+15 | **Não calculável** | **Bloqueada** | Nº de propostas · o que acontece com proposta não respondida · ticket · margem |
| P6 | Leads fora do horário | **Não calculável** | **Bloqueada** | Cobertura de horário · volume fora de horário |
| P7 | Desconto concedido (com repasse de 50%) | **Não calculável** · régua em 3.2 | **Bloqueada** | Desconto médio · existência de preço mínimo · ticket |
| P8 | Base parada (O&M, reativação, indicação, upsell) | **Não calculável** | **Bloqueada** | Nº real de clientes instalados · nº de orçamentos antigos |
| P9 | Lead órfão / colisão entre interno e franqueado | **Não calculável** | **Bloqueada** | Regra de distribuição · nº de leads |
| | **TOTAL APURADO** | **R$ 0** | — | — |

**9 de 9 perdas bloqueadas.** Isso é resultado, não omissão: é a tradução financeira de
"8 de 10 blocos do Raio-X sem resposta".

## 2.2 O que É entregável hoje

| # | Item | Forma | Confiança |
|---|---|---|---|
| F1 | Régua do repasse de franquia — custo por R$ 1.000 de erro de apuração | R$/mês por unidade de erro | Aritmética **alta** · frequência **desconhecida** |
| F2 | Régua de desconto sob repasse de 50% | R$/mês por R$ 1.000 de desconto médio | Aritmética **alta** · frequência **desconhecida** |
| F3 | Arco de leads exigidos por 50 vendas/mês | Faixa de 150 a 1.000 leads/mês | **Estrutural** — mostra a ignorância, não a resposta |
| F4 | Exposição do canal indicação, em vendas/mês | Unidades, não reais | Média |
| F5 | Cenários conservador/provável/otimista **pré-montados** | Fatores definidos, valores em branco | — |
| F6 | Oportunidades de posicionamento em **multiplicador** | Ex.: ticket T → 1,2T a 1,5T | **Baixa** (referência setorial) |

## 2.3 Riscos sem valor atribuído

| # | Risco | Por que não tem valor |
|---|---|---|
| R1 | Concentração em indicação (regra dos 50%) | % real não medido; faturamento exposto depende do ticket |
| R2 | Commoditização por preço (insight 9) | **Hipótese em aberto** — nenhum motivo de perda foi declarado |
| R3 | Uma marca, 8 posicionamentos (franquia sem padrão) | Padronização do entregável não informada |
| R4 | Repasse sobre lucro que pode não ter existido (risco de **caixa**) | Depende de F1 e da política de garantia/retrabalho |
| R5 | Raio de atuação desconhecido | Mercado endereçável não definido — passa ao agente 3 |

---

# 3. Detalhe — as contas montadas, com a lacuna dentro da fórmula

Cada bloco abaixo é a conta pronta. O que falta está em **MAIÚSCULA** e é exatamente uma
pergunta da próxima call.

---

## 3.1 · P1 — Repasse de 50% do lucro sem apuração de custo por venda

**É o furo nº 1 do agente 1, e eu concordo com a ordem — com uma correção de ênfase que
está no fim deste bloco.**

```
Perda mensal = VENDAS DE FRANQUIA/MÊS × ERRO MÉDIO DE APURAÇÃO POR VENDA × 50%

Fatores:
  VENDAS DE FRANQUIA/MÊS   — não informado (split franqueado × interno nunca foi levantado)
                              teto lógico: ~50/mês, e ainda assim as 50 são relato ambíguo
× ERRO MÉDIO DE APURAÇÃO   — não informado. É a diferença entre o "lucro" usado no repasse
     POR VENDA               e o lucro real depois de kit, frete, estrutura, mão de obra,
                              projeto, homologação, ART, deslocamento, impostos, garantia
                              e retrabalho
× 50%                      — informado pelo cliente, confiança ALTA
= NÃO CALCULÁVEL
```

**Régua F1 — o que o dono pode calcular sozinho, em 30 segundos, assim que souber o split:**

```
Cada R$ 1.000 de custo NÃO apurado por venda custa R$ 500 de repasse indevido por venda.

  se 20 das 50 vendas/mês forem de franquia  →  R$ 10.000/mês  (R$ 120.000/ano)
  se 30 das 50 vendas/mês forem de franquia  →  R$ 15.000/mês  (R$ 180.000/ano)
  se 40 das 50 vendas/mês forem de franquia  →  R$ 20.000/mês  (R$ 240.000/ano)

  por cada R$ 1.000 de erro de apuração, e escalando linearmente:
  R$ 3.000 de erro sobre 30 vendas = R$ 45.000/mês
```

```
Confiança da aritmética: ALTA — são dois dados do cliente (50% de repasse, ~50 vendas/mês)
Confiança da frequência: NULA — não sei se existe erro de apuração, nem de que tamanho.
                                Pode ser zero. A régua mede, não acusa.
Premissa: as ~50 vendas/mês são realizadas e incluem sistemas FV — AMBOS a confirmar
```

**Por que R$ 500 e não R$ 1.000 por venda:** se o custo real fecha R$ 1.000 acima do
previsto, a empresa absorve os R$ 1.000 de qualquer jeito — isso é custo, não erro de
apuração. O que a **falha de apuração** custa a mais é o repasse pago sobre um lucro que
não existiu: metade, R$ 500. Separar as duas coisas é o que torna essa linha defensável.

**A correção de ênfase que faço ao agente 1.** Ele escreveu que "o furo que provavelmente
vale mais dinheiro está na margem". Eu diria assim: **é o furo mais alavancado** — incide
em toda venda de 5 dos 8 canais, todo mês, e o multiplicador é 50%, o mais alto de todo o
relatório. Mas **o tamanho dele pode ser zero**. Se a RP apura custo venda a venda com
rigor, F1 não vale nada. Vender isso ao dono como perda confirmada é exatamente o tipo de
afirmação que ele derruba com uma frase ("a gente fecha planilha por obra"). A formulação
que se sustenta é: *é onde um erro pequeno vira dinheiro grande mais rápido, e é a primeira
coisa a medir — não a primeira coisa a afirmar.*

**Como confirmar:** pegar **3 vendas de franqueado já instaladas e encerradas** dos últimos
90 dias e refazer o custo real de cada uma, com nota fiscal na mão, incluindo retrabalho e
chamado pós-instalação. Três obras respondem essa pergunta melhor que qualquer planilha.

**Perguntas que destravam:** quantas das 50 vendas/mês são de franqueados? · quem calcula o
lucro, a empresa ou o franqueado? · quais custos entram na conta? · garantia e retrabalho
entram antes ou aparecem depois no caixa da empresa?

---

## 3.2 · P7 — Desconto concedido, com o agravante do repasse de 50%

```
Perda mensal = VENDAS DE FRANQUIA/MÊS × DESCONTO MÉDIO EM R$ × 50%

Fatores:
  DESCONTO MÉDIO CONCEDIDO — NÃO INFORMADO
  EXISTE PREÇO MÍNIMO?     — NÃO INFORMADO  ← este é o fator crítico, não o desconto
  VENDAS DE FRANQUIA/MÊS   — NÃO INFORMADO
= NÃO CALCULÁVEL
```

**Régua F2:**

```
Sob comissão sobre LUCRO, cada R$ 1.000 de desconto sai integralmente do lucro:
R$ 500 do bolso da empresa e R$ 500 do bolso do franqueado.

  30 vendas de franquia/mês × R$ 1.000 de desconto médio = R$ 15.000/mês para a empresa
  (e R$ 15.000/mês para os franqueados — é por isso que o modelo, em tese, se autorregula)
```

**Aqui a RP está no lado certo da decisão do playbook, e isso merece ser dito ao dono.**
O playbook é explícito: comissão sobre faturamento faz o desconto custar pouco ao vendedor;
comissão sobre margem faz o vendedor defender o preço. No exemplo do playbook — venda de
R$ 42 mil, comissão de 4%, desconto de 8% — a comissão sobre faturamento cai 8% e a
comissão sobre margem cai **73%**. Na RP o repasse é sobre lucro, então **o franqueado
sente cada real de desconto na pele, na proporção de 1 para 1**. Esse é o incentivo mais
forte contra desconto que existe, e a RP já o tem.

**O problema não é o incentivo, é o piso.** Se não existe preço mínimo de tabela, o
franqueado pode aceitar apertar a margem até um ponto em que a empresa — que banca
estrutura, marca, garantia e eventual retrabalho — fica com metade de quase nada. **O
vendedor que sente o desconto não deixa de dar desconto: ele deixa de dar desconto grande.
Quem impede o desconto pequeno e crônico é o piso, não o incentivo.**

**Pergunta que destrava:** existe preço mínimo de tabela? quem pode aprovar exceção?

---

## 3.3 · P2, P3, P6, P9 — Tudo que depende do número de leads

**Quatro perdas, a mesma lacuna raiz: a RP não sabe quantos leads recebe.**

```
P2 — Lead não respondido
  LEADS/MÊS × % SEM RESPOSTA × CONVERSÃO × TICKET × MARGEM  = NÃO CALCULÁVEL
  (quatro dos cinco fatores vazios)

P3 — Resposta lenta
  LEADS RESPONDIDOS FORA DA JANELA × DELTA DE CONVERSÃO × TICKET × MARGEM = NÃO CALCULÁVEL

P6 — Leads fora do horário
  LEADS FORA DO HORÁRIO × % PERDIDOS × CONVERSÃO × TICKET × MARGEM = NÃO CALCULÁVEL

P9 — Lead órfão / colisão interno × franqueado
  LEADS SEM DONO DEFINIDO × ... = NÃO CALCULÁVEL, e sem regra de distribuição informada
```

**Sobre o benchmark de velocidade, e por que NÃO o apliquei.** O material-base traz como
**referência, não garantia**: ~23% de conversão respondendo em até 1 minuto no WhatsApp
contra ~1% depois de um dia, e que só ~7% das empresas respondem dentro de 5 minutos.
Aplicar esse delta sobre a RP exigiria inventar o número de leads **e** o ticket **e** o
tempo de resposta atual — três invenções encadeadas. O número resultante seria grande,
impressionante e indefensável na primeira pergunta do dono. **Não faço.**

**O que dá para dizer sem inventar:** a RP não tem IA, não tem SLA, não tem sistema e tem 8
pessoas em dois vínculos diferentes recebendo lead sem regra de distribuição declarada.
Estatisticamente, o setor coloca 93% das empresas fora da janela de 5 minutos. A pergunta
para o dono não é quanto ele perde — é: **"quanto tempo leva, hoje, até o lead receber a
primeira resposta? e o que acontece com o que chega 21h de sábado?"**

**Um risco específico da RP que não é sobre velocidade e não tem equivalente em integradora
normal:** com 3 internos e 5 franqueados disputando a mesma marca sem regra de distribuição,
dois vendedores podem estar falando com o mesmo cliente. Em cidade pequena e venda por
indicação, **isso custa reputação, e reputação é o insumo do único canal que a RP tem.**
Não tem preço calculável e não precisa ter para entrar na pauta.

---

## 3.4 · P5 — Propostas que morrem sem cadência

```
Perda mensal = PROPOSTAS/MÊS × % QUE MORREM SEM CADÊNCIA × TAXA DE RECUPERAÇÃO
               × TICKET × MARGEM
             = NÃO CALCULÁVEL — quatro dos cinco fatores vazios
```

Na maioria das integradoras esta é a maior perda isolada. **Na RP nem sabemos se ela
existe**, porque o número de propostas nunca foi medido e ninguém perguntou o que acontece
com a proposta que o cliente não responde.

**E há uma hipótese que precisa ser testada antes de assumir que a perda é grande:** numa
operação que vive de **indicação**, o lead chega com confiança pré-instalada e a taxa
proposta→contrato tende a ser **alta**. Os 6,25 fechamentos por vendedor/mês calculados
pelo agente 1 são compatíveis com isso. Se a taxa proposta→contrato da RP for alta, sobra
pouca proposta morta para recuperar e **P5 é pequena** — e eu direi que é pequena. Inflar
essa linha por ser "a habitual" seria copiar o diagnóstico de outra empresa.

**A pergunta que destrava é uma só:** quantas propostas foram apresentadas no último mês?
Ela fecha a taxa proposta→contrato, que é a mais diagnóstica do funil inteiro.

---

## 3.5 · P4 — Qualificação fraca (custo de hora de vendedor)

```
Perda mensal = HORAS/MÊS COM LEAD SEM PERFIL × CUSTO/HORA DO VENDEDOR
             + custo de oportunidade das visitas que não aconteceram
             = NÃO CALCULÁVEL
```

**Aqui há um detalhe do modelo de franquia que muda a natureza da perda e vale a pena
registrar:** o tempo desperdiçado pelos **5 franqueados** não aparece na folha da RP — quem
paga é o franqueado, com o próprio tempo. Para a empresa, o custo é **indireto**: franqueado
que queima horas com curioso vende menos, e a empresa perde a metade dela do lucro dessas
vendas que não aconteceram. **Não é um custo menor — é um custo que não dói no lugar onde
seria visto**, e por isso tende a ficar anos sem tratamento.

Para os **3 internos**, o custo é direto e calculável assim que chegarem: salário + encargos
e número de leads atendidos por mês.

---

## 3.6 · P8 — Base parada: O&M, reativação, upsell e indicação

```
Receita potencial = Nº REAL DE CLIENTES INSTALADOS × TAXA DE ADESÃO × TICKET DE O&M
                  = NÃO CALCULÁVEL
```

**Por que não uso a estimativa do agente 1, e ele pediu explicitamente que eu não usasse.**
O 01 registra "centenas de clientes, possivelmente > 1.000", derivado de ~50 vendas/mês ×
~6 anos, **sem assumir ritmo constante**, com confiança **baixa** e com a instrução expressa
de não usar em cálculo financeiro. Eu concordo e vou além: essa estimativa herda **toda** a
ambiguidade das 50 vendas/mês. Se as 50 forem meta e não realizado, ou se incluírem
produtos que não são fotovoltaicos, a base cai pela metade ou mais. Multiplicar receita de
O&M por esse número produziria a linha mais impressionante e mais frágil do relatório.

**O que é afirmável com confiança alta:** a RP tem ~6 anos de mercado, entrega obra boa o
suficiente para o cliente indicar, e **não há nenhum processo relatado falando com essa
base**. Três receitas diferentes estão paradas no mesmo lugar — O&M recorrente, reativação
de orçamento antigo, e pedido estruturado de indicação — e nenhuma delas está sendo cobrada.
**Dizer o tamanho exige um número; dizer que existe não exige.**

**Pergunta que destrava:** quantos clientes instalados a empresa tem, ao total? e quantos
orçamentos antigos não convertidos, de que período?

---

# 4. Meta reversa

## 4.1 Por que ela não roda hoje — e são duas travas, não uma

O movimento 3 do playbook parte da meta e desce pelo funil. Na RP:

- **Trava 1 — não existe meta declarada.** Nem em unidades, nem em faturamento. Sem meta,
  não há de onde partir.
- **Trava 2 — não existe nenhuma taxa de conversão.** Cinco das seis etapas do funil são
  invisíveis; nenhuma razão entre duas etapas é calculável. Sem taxas, não há por onde descer.

Meta reversa exige um ponto de partida e um caminho. **A RP não tem nenhum dos dois.**

## 4.2 O que dá para mostrar: o arco de leads (F3)

Único número disponível: ~50 contratos/mês (relato, confiança média, ambíguo). A pergunta
"quantos leads a RP precisa?" depende inteiramente da taxa lead→contrato, que ninguém mediu.
A tabela abaixo **não estima essa taxa** — ela mostra o que cada hipótese implicaria:

| Se a taxa lead→contrato for | Leads/mês necessários para 50 vendas | Leitura |
|---|---|---|
| 5% | **1.000** | Volume de operação de mídia paga pesada — improvável sem investimento declarado |
| 10% | **500** | Padrão de funil misto |
| 20% | **250** | Funil forte |
| 33% | **~150** | Compatível com operação majoritariamente de indicação |
| 50% | **100** | Indicação quase pura, lead pré-vendido |

```
Premissa: 50 contratos/mês (relato verbal, ambíguo entre meta e realizado, confiança média)
As taxas NÃO são estimativas da RP — são hipóteses ilustrativas para mostrar a amplitude
Confiança: estrutural, não numérica
```

**A leitura que importa não é nenhuma linha da tabela — é a tabela inteira.** A RP não sabe
se movimenta 100 ou 1.000 leads por mês. **Isso é uma diferença de 10x no tamanho da
operação de topo de funil**, e é literalmente a diferença entre "o problema é conversão" e
"o problema é geração". O playbook é direto: *não coloque mais tráfego em um funil que não
converte.* Hoje a RP não tem como saber em qual dos dois lados está, e **qualquer real
investido em mídia nesse estado é aposta, não decisão.**

## 4.3 A meta reversa, pré-montada para a call

Quando os números chegarem, a conta roda assim (mesma estrutura, dois cenários):

```
COM AS TAXAS DE HOJE                        COM AS TAXAS CORRIGIDAS PELO PLANO
META DE VENDAS/MÊS                           META DE VENDAS/MÊS
÷ taxa proposta→contrato ATUAL      →        ÷ taxa proposta→contrato ALVO
÷ taxa diagnóstico→proposta ATUAL   →        ÷ taxa diagnóstico→proposta ALVO
÷ taxa qualificado→diagnóstico ATUAL →       ÷ taxa qualificado→diagnóstico ALVO
÷ taxa lead→qualificado ATUAL       →        ÷ taxa lead→qualificado ALVO
= LEADS/MÊS NECESSÁRIOS                      = LEADS/MÊS NECESSÁRIOS

A diferença entre os dois é o argumento: ou a RP compra muito mais lead, ou conserta a conversão.
```

**Dados que preenchem:** a meta · leads/mês · propostas/mês · diagnósticos/mês. Quatro
números. **Trinta dias de ficha semanal entregam os quatro.**

---

# 5. Os três cenários

**Os três cenários da RP são idênticos hoje: R$ 0.** Não porque a operação seja perfeita,
mas porque não há um único fator de conta preenchido o bastante para diferenciar piso de
teto. Apresentar três números inventados lado a lado daria a aparência de rigor a um chute
triplicado.

O que entrego no lugar é o **motor dos cenários, já montado**, para ser preenchido na call:

| | **Conservador** (vai para a conversa) | **Provável** | **Otimista** |
|---|---|---|---|
| Quais perdas entram | Só confiança alta e média | Alta, média e baixa-média | Todas |
| Fator de recuperação de lead | Piso da faixa | Meio | Teto |
| % de propostas sem cadência | Piso | Meio | Teto |
| Erro de apuração de custo (F1) | Só o medido em 3 obras reais | Média das 3 obras | Pior das 3 obras |
| Split de franquia | O menor informado | O informado | O informado |
| Ticket e margem | **Os informados pelo dono** | Os informados | Os informados |
| **Eixo 2 (posicionamento)** | **Fora** | **Fora** | **Fora — em todos, sempre** |
| **Valor hoje** | **R$ 0 — não calculável** | **R$ 0 — não calculável** | **R$ 0 — não calculável** |

**Regra que fica valendo para quando os números chegarem:** o número que vai para a
conversa com o dono é o **conservador**. É o mais fácil de defender e costuma bastar para
decidir. E **em nenhum dos três cenários entra qualquer percentual do eixo de
posicionamento.**

---

# 6. Oportunidades de posicionamento

> **Seção separada de propósito. Nada aqui entra em nenhum total, em nenhum cenário e em
> nenhum payback.** Todos os percentuais abaixo são **referências setoriais de top players,
> SEM FONTE DECLARADA na coleta**, confiança **baixa**, e **nenhum foi medido na RP** —
> lembrando que **0 de 10 blocos** do Raio-X de posicionamento foram respondidos.
> **Nenhum deles se soma a nenhum outro.**

## 6.1 Ticket com projeto técnico (insight 1: +20% a +50%)

```
Oportunidade: ticket T → entre 1,2×T e 1,5×T
premissa: faixa observada em top players (insight 1), SEM FONTE DECLARADA; a RP NÃO
          informou se emite ART, se entrega memorial, nem se o cliente recebe projeto
          técnico ou orçamento de kit (blocos 1 e 2 do Raio-X de posicionamento: NÃO
          INFORMADOS)
confiança: BAIXA — referência de mercado, não medição desta empresa
NÃO é projeção de resultado da RP. É o tamanho da oportunidade, para decidir se investiga.
```

**Não converto em reais, e o motivo é duplo:** não sei o ticket (T é literalmente
desconhecido) e não sei se a RP já entrega o projeto técnico — caso em que a oportunidade
não existe como ganho de ticket, e sim como ganho de **apresentação**.

**O agravante exclusivo da RP, e ele é grande:** com 5 franqueados vendendo sob a mesma
marca, a pergunta **"quem é o responsável técnico que assina a ART das vendas do
franqueado?"** é técnica e jurídica antes de ser comercial. Se cada franqueado monta o
próprio entregável, a RP tem **8 posicionamentos diferentes no mercado com uma marca só** —
e, em cidade pequena, a marca passa a valer o que vale o pior deles. **Nesse caso, a
primeira ação de posicionamento não é subir ticket: é padronizar o entregável.** Essa ação
não tem percentual de benchmark nenhum associado, e mesmo assim é a primeira da fila.

## 6.2 LTV com O&M (insight 5: +25% a +40%)

**Não dimensionado.** A regra do meu próprio agente é clara: só dimensionar se o tamanho da
base instalada for conhecido. Não é — a única estimativa existente tem confiança baixa e
veio com instrução expressa de não ser usada em cálculo financeiro.

**Pergunta que destrava:** quantos clientes instalados a RP tem, ao total? (e, junto:
existe algum contrato de manutenção vendido hoje?)

## 6.3 CAC com parcerias técnicas (insight 6: −30% a −60%)

**Não calculo, e não vou calcular.** O CAC da RP **não existe como número**: não há
investimento em marketing informado, não há custo por lead, não há número de leads.
Reduzir 30% a 60% de um número que ninguém tem não é conta.

**E há uma nuance específica da RP que o insight não cobre.** Uma empresa que vive de
indicação provavelmente já opera com **CAC muito baixo** — talvez o mais baixo do mapa de
canais do playbook. Se for o caso, **reduzir CAC não é a alavanca dela**. A alavanca é a
oposta: **montar um segundo canal**, aceitando um CAC maior que o de hoje, para deixar de
depender de um canal único que não se consegue acelerar. Vender "redução de CAC" a esta
empresa seria vender a solução de outra.

**Perguntas que destravam:** quanto se investe em marketing por mês, por canal? qual o custo
por lead? existe alguma parceria formal com arquiteto, construtora, loja de material,
imobiliária, cooperativa ou contador?

## 6.4 Proposta visual (insight 4: +10–20%) e follow-up técnico (insight 7: +10–18%)

**Ordem de prioridade, não reais projetados.** Para a RP, na ordem em que eu atacaria:

| Ordem | Ação | Por que nesta posição | Percentual de benchmark |
|---|---|---|---|
| 1º | **Padronizar o entregável nos 8 canais de venda** | Sem isso, qualquer melhoria de proposta melhora 1 dos 8 canais. É o multiplicador de tudo que vier depois | **Nenhum** — e mesmo assim é o primeiro |
| 2º | **Presença técnica: GMB, portfólio de obras, geração publicada** | 6 anos de obra entregue e nenhum registro público verificado. Custo quase zero, prazo de dias | Insight 2 (60–80% dos leads qualificados vêm de intenção ativa) |
| 3º | **Proposta visual com telhado, layout e geração mês a mês** | Depende do item 1 para valer nos 8 canais | Insight 4: +10–20% |
| 4º | **Follow-up técnico estruturado** | Exige CRM, que a RP não tem. Vem depois da instrumentação | Insight 7: +10–18% |

**O item 2 merece um parágrafo.** O insight 8 diz que o moat estrutural — a única coisa que
o concorrente não copia em 30 dias — é relacionamento com arquitetos **+ histórico técnico
documentado**. A RP provavelmente **tem** o histórico (6 anos de obra boa o bastante para
sustentar um negócio inteiro por indicação) e **não tem** a documentação. É engenharia
guardada na gaveta: o ativo existe, não está registrado em lugar nenhum fora da memória de
quem fez, e por isso **não é vendável nem defensável**. Transformar isso em portfólio
público é a ação de melhor relação esforço/retorno de todo o eixo 2 — e a única que não
depende de nenhum dado que está faltando.

---

# 7. Riscos — sem valor atribuído

## R1 · Concentração em indicação (regra dos 50%)

```
Faturamento exposto = % REAL DE INDICAÇÃO × 50 VENDAS/MÊS × TICKET  = NÃO CALCULÁVEL

Em unidades (F4), o que se pode mostrar:
  se indicação for 60% das vendas e o canal cair pela metade → ~15 vendas/mês somem
  se indicação for 80% das vendas e o canal cair pela metade → ~20 vendas/mês somem
premissa: 50 vendas/mês (relato, confiança média); os % de indicação são HIPÓTESES,
          porque "principalmente" nunca virou número
```

**É risco, não perda corrente — nada foi perdido ainda.** E a indicação é, pelo playbook,
o melhor canal do setor: maior conversão, menor custo, prioridade sempre. O problema não é
depender dela; é **não conseguir acelerá-la** quando o mês vem fraco, porque não há processo
de pedido de indicação, e não ter um segundo canal montado para segurar a queda.

## R2 · Commoditização por preço (insight 9) — hipótese em aberto, não testada

**O teste não roda.** O insight 9 é testado a partir do **motivo de perda declarado**, e a
RP não declarou nenhum dos três. Não sabemos **se** ela perde, **de quem** perde, nem **por
quê**. Não atribuo valor e não trato como confirmado nem como descartado.

**A pergunta que fecha o eixo — *"se o concorrente igualar seu preço amanhã, o que
sobra?"* — ainda não foi feita ao dono.** Anotar a resposta literal. Se for "nada" ou
silêncio, o eixo de posicionamento passa a ser o dominante e a ordem de todo o plano muda.

**Um sinal que joga contra a hipótese de commoditização, e é preciso registrá-lo:** viver de
indicação por 6 anos não é comportamento de empresa commoditizada. Quem é escolhido por
preço não é indicado por reputação. **Isso é evidência fraca, não prova** — mas é o único
sinal disponível, e ele é favorável à RP.

## R3 · Uma marca, 8 posicionamentos

Detalhado em 6.1. Sem valor calculável; alto impacto potencial em cidade pequena.

## R4 · Risco de caixa no repasse

Se o repasse de 50% é feito sobre lucro **estimado** e o custo real fecha acima, a empresa
pagou comissão sobre resultado que não teve — e descobre **meses depois**, na instalação ou
na garantia. Isso não aparece em nenhuma taxa de conversão e não aparece no mês em que
acontece. É o mesmo mecanismo de F1, visto pelo ângulo do caixa.

## R5 · Raio de atuação desconhecido

~50 vendas/mês não saem de um município do porte de Sanclerlândia sozinhas. De onde vem o
volume — raio regional, capitais, franqueados em outras cidades? **Define mercado
endereçável, custo de deslocamento e onde a próxima venda pode existir.** Passa direto ao
agente 3.

---

# 8. Não quantificável hoje — com a pergunta que destrava cada item

## Bloco A — destrava o relatório financeiro inteiro

| # | Item bloqueado | Pergunta exata que destrava |
|---|---|---|
| A1 | **Toda perda em reais** | **Qual o ticket médio da venda de sistema FV nos últimos 30 dias?** |
| A2 | **Toda perda em margem** | **Qual a margem média por venda, em % ou em R$?** |
| A3 | **Validade de todo volume deste relatório** | **As ~50 vendas/mês são meta ou realizado? De que período? São 50 sistemas FV ou incluem outros produtos?** |
| A4 | **Meta reversa (trava 1)** | **Existe meta de vendas/mês ou de faturamento? Qual?** |

## Bloco B — o modelo de franquia

| # | Item bloqueado | Pergunta exata |
|---|---|---|
| B1 | F1 — régua do repasse | **Quantas das ~50 vendas/mês são de franqueados e quantas dos internos?** |
| B2 | Tamanho real do erro de apuração | **Como o lucro de cada venda é calculado, e por quem? Quais custos entram?** |
| B3 | Risco de caixa (R4) | **Garantia, retrabalho e chamado pós-instalação entram no cálculo do lucro, ou aparecem depois no caixa da empresa?** |
| B4 | F2 — régua de desconto | **Qual o desconto médio concedido? Existe preço mínimo de tabela? Quem aprova exceção?** |
| B5 | Custo real por obra | **Posso pegar 3 vendas de franqueado já instaladas e refazer o custo com nota fiscal na mão?** |
| B6 | Comportamento de preço dos internos | **Qual a base de comissão dos 3 internos, e o %?** |
| B7 | Risco técnico/jurídico (R3) | **Quem é o responsável técnico que assina a ART das vendas dos franqueados?** |

## Bloco C — funil

| # | Item bloqueado | Pergunta exata |
|---|---|---|
| C1 | P2, P3, P4, P6, P9 e o arco F3 | **Quantos leads entraram no último mês? Onde eles chegam?** |
| C2 | P3 — resposta lenta | **Quanto tempo leva, em média, até o lead receber a primeira resposta?** |
| C3 | P6 — fora do horário | **O que acontece com o lead que chega 21h de sábado?** |
| C4 | P9 — lead órfão/colisão | **Quem pega o lead que chega? Existe rodízio ou regra de distribuição?** |
| C5 | P5 e a taxa mais diagnóstica do funil | **Quantas propostas foram apresentadas no último mês?** |
| C6 | P5 — existência da perda | **O que acontece hoje com a proposta que o cliente não responde?** |
| C7 | R2 — teste de commoditização | **Os 3 principais motivos de perda — force três, não aceite um** |
| C8 | Ponto de partida da instrumentação | **Existe CRM, planilha ou nada?** |

## Bloco D — base, posicionamento e mercado

| # | Item bloqueado | Pergunta exata |
|---|---|---|
| D1 | P8 e LTV/O&M (6.2) | **Quantos clientes instalados a empresa tem, ao total?** |
| D2 | P8 — reativação | **Quantos orçamentos antigos não convertidos existem, e de que período?** |
| D3 | Ticket com projeto técnico (6.1) | **O cliente recebe projeto técnico assinado com ART e memorial, ou orçamento de kit? Está no preço?** |
| D4 | Proposta visual (6.4) | **Como a proposta é apresentada: PDF de preço, ou projeto com telhado, layout e geração mês a mês?** |
| D5 | CAC e parcerias (6.3) | **Quanto se investe em marketing por mês, por canal? Qual o custo por lead? Existe parceria formal?** |
| D6 | R1 — regra dos 50% | **Qual o % real do faturamento que vem de indicação?** |
| D7 | R2 — a pergunta que fecha o eixo | **Se o concorrente igualar seu preço amanhã, o que sobra?** — anotar resposta literal |
| D8 | R5 e o agente 3 | **Qual o raio de atendimento — quais cidades, quantos km? Os 5 franqueados atuam onde?** |
| D9 | Agente 4 (perfil de cliente) | **Qual o segmento predominante: residencial, comercial, rural ou industrial? E o mix aproximado?** |
| D10 | Agente 5 (concorrentes) | **Contra quem vocês disputam, por nome? Para quem costumam perder?** |

**Atalho para a call: A1, A2, A3, B1, C1 e C5.** Seis números. Com eles, este documento sai
da próxima versão com perdas em reais, cenários preenchidos e meta reversa rodando.

---

# 9. Custo da inação — 12 meses sem mudança

Sem ticket e sem margem, **não projeto o custo da inação em reais** — seria o mesmo erro do
resto do relatório, só que com cara de urgência. O que é afirmável, em unidades e em
decisões:

**O que acontece em 12 meses se nada mudar:**

1. **~600 vendas a mais** (se as 50/mês forem realizadas) fecham sem que se saiba a margem
   de nenhuma delas. Se houver erro de apuração, ele é cobrado **600 vezes**, e a régua F1
   diz que cada R$ 1.000 de erro sobre 30 vendas/mês são R$ 180.000 no ano.
2. **A base instalada cresce ~600 clientes** — e continua sem O&M, sem indicação estruturada
   e sem histórico documentado. O ativo cresce; o registro do ativo, não.
3. **Doze meses de decisão às cegas sobre marketing.** A RP continua sem saber se precisa de
   mais lead ou de mais conversão. Cada real de mídia investido nesse estado continua sendo
   aposta — e o playbook é direto: *não coloque mais tráfego em um funil que não converte.*
4. **O risco de canal continua sem segundo canal.** Se a indicação cair, não há o que
   acionar, e a queda só será percebida no mês em que já aconteceu.
5. **O histórico técnico de 6 anos vira 7 anos guardados na gaveta.** É o único ativo que o
   concorrente não copia em 30 dias, e ele continua não existindo fora da cabeça de quem fez.
6. **E o item que não é sobre dinheiro:** doze meses a mais de 8 pessoas vendendo sob uma
   marca sem padrão declarado de entregável, em cidade pequena, onde a reputação é o insumo
   do canal principal.

**O ponto que resume tudo:** o custo da inação aqui não é uma perda que cresce — é uma
**decisão que continua impossível de tomar**. A RP não consegue responder se deve investir
em lead, em conversão, em margem ou em posicionamento. **Trinta dias de medição custam quase
nada e valem mais, para esta empresa, do que qualquer ferramenta comprada hoje.**

---

# 10. Passagem de bastão

## 10.1 → Cadeia (formato padrão)

```
Perda total (conservador): R$ 0 calculável — 9 de 9 perdas BLOQUEADAS por falta de
                           ticket médio e margem. Não é perda zero: é perda não medida.

Top 3 furos, sem valor em reais (ordem de prioridade de MEDIÇÃO, não de tamanho):
 1. Repasse de 50% do lucro sem apuração de custo por venda — o mais ALAVANCADO do
    relatório (5 de 8 canais, toda venda, multiplicador de 50%). Régua F1: cada R$ 1.000
    de custo não apurado por venda = R$ 500/venda; a 30 vendas de franquia/mês, são
    R$ 15.000/mês (R$ 180.000/ano). Aritmética: confiança ALTA. Frequência: NULA — pode
    ser zero. Destrava com B1 + B2 + B5.
 2. Funil inteiro invisível — 4 perdas (lead não respondido, resposta lenta, fora de
    horário, lead órfão) travadas na mesma lacuna raiz: ninguém sabe quantos leads entram.
    Destrava com C1 + A1 + A2.
 3. Base instalada de ~6 anos parada — O&M, reativação e indicação estruturada, três
    receitas no mesmo lugar, nenhuma cobrada. Destrava com D1 + D2.

Gargalo dominante confirmado (ou corrigido) pelo dinheiro:
  CONFIRMADO POR AUSÊNCIA, com uma correção de ênfase. O agente 1 elegeu "falta de
  visibilidade" como gargalo dominante; o fato de que 9 de 9 contas financeiras travam
  no mesmo lugar é a confirmação mais forte possível dessa escolha — o gargalo não
  sobreviveu ao teste do dinheiro, ele foi CONFIRMADO PELO TESTE NÃO PODER SER FEITO.
  CORREÇÃO ao agente 1: ele escreveu que o furo da margem "provavelmente vale mais
  dinheiro". Ajuste: é o furo mais ALAVANCADO, não comprovadamente o maior. Seu tamanho
  pode ser zero se a apuração for rigorosa. Apresentar como "onde um erro pequeno vira
  dinheiro grande mais rápido", nunca como perda confirmada — o dono derruba a
  afirmação com uma frase.

Meta reversa: NÃO RODA — duas travas. Não há meta declarada (trava 1) e não há nenhuma
  taxa de conversão calculável (trava 2). Substituída pelo arco F3: para 50 vendas/mês,
  a RP precisa de 1.000 leads/mês a 5% de conversão, ou 150 a 33%. Ela não sabe em qual
  ponto está — amplitude de 10x. Enquanto isso não fechar, TODO investimento em mídia é
  aposta.

Perda endereçável por camada (todas bloqueadas, com a lacuna nomeada):
- Geração (Agente de Marketing): NÃO CALCULÁVEL. Sem investimento, sem CPL, sem nº de
  leads → sem CAC, sem custo por projeto, sem ROI. Atenção: a RP provavelmente já tem
  CAC baixíssimo (vive de indicação) — a alavanca dela NÃO é reduzir CAC, é montar um
  segundo canal aceitando CAC maior. Não vender redução de CAC a esta empresa.
- Atendimento + Qualificação (Agente SDR): NÃO CALCULÁVEL. 4 perdas travadas na mesma
  lacuna (nº de leads). Risco específico sem equivalente em integradora normal: 8
  vendedores em 2 vínculos, sem regra de distribuição — lead órfão e colisão interno ×
  franqueado, que em cidade pequena custa reputação, o insumo do canal principal.
- Cadência pós-proposta (Agente de Follow-up): NÃO CALCULÁVEL, e NÃO assumir que é a
  maior perda só porque costuma ser. Operação de indicação tende a ter taxa
  proposta→contrato alta, e nesse caso sobra pouca proposta morta. Se for pequena, dizer
  que é pequena. Destrava com C5 + C6.
- Venda + Gestão (Mentoria): o item de maior valor estrutural. Inclui instrumentação das
  6 etapas do funil (que é o que destrava todo o resto deste relatório), apuração de
  custo venda a venda, política de preço mínimo, e a definição de meta — que hoje não
  existe. É a camada que transforma este documento de "bloqueado" em "calculado".

Oportunidades de posicionamento (referência setorial SEM FONTE DECLARADA, confiança
baixa, NÃO somadas a nada, NÃO em payback, NÃO somáveis entre si):
- Ticket com projeto técnico (insight 1): ticket T → 1,2×T a 1,5×T. NÃO convertido em
  reais: T é desconhecido E não se sabe se a RP já emite ART/memorial. Agravante
  exclusivo: com 5 franqueados, a 1ª ação não é subir ticket, é PADRONIZAR o entregável
  — e quem assina a ART das vendas do franqueado é pergunta jurídica, não comercial.
- LTV com O&M (insight 5, +25–40%): NÃO DIMENSIONADO. Base instalada desconhecida; a
  estimativa "centenas, possivelmente >1.000" tem confiança baixa e veio do agente 1 com
  instrução expressa de não usar em cálculo financeiro. Respeitada.
- CAC com parcerias (insight 6, −30–60%): NÃO CALCULADO e não calculável. CAC de hoje
  não existe como número.
- Proposta visual (insight 4) e follow-up técnico (insight 7): ordem de prioridade, não
  reais. Ordem para a RP: 1º padronizar entregável nos 8 canais (sem percentual de
  benchmark nenhum, e ainda assim é o primeiro) · 2º presença técnica/GMB/portfólio ·
  3º proposta visual · 4º follow-up técnico (exige CRM, que não existe).

Hipótese de commoditização: EM ABERTO, NÃO TESTADA. Nenhum dos 3 motivos de perda foi
  declarado; não se sabe se perde, de quem, nem por quê. Um sinal FRACO joga contra a
  hipótese: viver de indicação por 6 anos não é comportamento de empresa escolhida por
  preço. A pergunta que fecha o eixo — "se o concorrente igualar seu preço amanhã, o que
  sobra?" — AINDA NÃO FOI FEITA. Anotar a resposta literal.

Premissas frágeis a validar antes de qualquer proposta:
 1. "~50 vendas/mês" — relato verbal, período não especificado, AMBÍGUO entre meta e
    realizado, e não se sabe se são só sistemas FV. TODO número deste relatório que usa
    50 (F1, F3, F4, custo da inação) desaba ou dobra conforme a resposta. É a premissa
    mais frágil e a mais usada.
 2. Base instalada "centenas" — estimativa condicional, confiança baixa, NÃO usada aqui
    e que NÃO deve ser usada adiante sem o número real.
 3. Split franqueado × interno — nunca levantado; define sobre que volume F1 e F2 incidem.
 4. Existência de erro de apuração — hipótese, não achado. Pode ser zero.
 5. Todos os percentuais do eixo 2 — referência setorial sem fonte, confiança baixa,
    nenhum medido na RP, nenhum somável, nenhum apresentável como projeção de resultado.
```

## 10.2 → Agente 3 (oportunidades-regionais)

- **Sua maior lacuna é a minha R5: o raio de atuação é desconhecido.** Sanclerlândia/GO é
  município pequeno e ~50 vendas/mês não saem de um mercado desse tamanho sozinhas. **A
  pergunta D8 é sua, e é a primeira:** quais cidades, quantos km, e onde atuam os 5
  franqueados (há exclusividade territorial? há canibalização entre canais?).
- **Não há faturamento, ticket nem margem para dimensionar mercado endereçável em reais.**
  Trabalhe em **unidades e em cidades**, não em R$, ou herda o mesmo bloqueio deste
  documento.
- **A dependência de indicação é geográfica.** Indicação funciona por proximidade; ela não
  atravessa 200 km sozinha. Se o volume vem de fora de Sanclerlândia, ou existe estrutura
  regional não declarada, ou o canal já é outro e a empresa não sabe.
- **O canal de menor custo do playbook para esta empresa é a base instalada** (D1/D2) — e
  ela é, por definição, regional. Cruze base instalada com raio de atuação.

## 10.3 → Agente 4 (perfil-cliente-ideal)

- **D9 é sua pergunta:** o mix real entre residencial, comercial, rural e industrial. A
  busca pública indica os quatro, on-grid e off-grid. **O mix muda ticket, ciclo de venda e
  argumento** — e é uma das explicações possíveis para os 6,25 fechamentos por
  vendedor/mês.
- **A pista mais forte que tenho para você, e é aritmética, não opinião:** 6,25 vendas
  fechadas por vendedor/mês é produtividade alta para venda complexa de sistema FV. As
  explicações possíveis são poucas e mutuamente exclusivas — (a) ticket baixo, kits
  pequenos, forte peso de off-grid rural; (b) as 50 incluem produtos que não são FV; (c) 50
  é meta, não realizado; (d) a operação é excepcionalmente boa. **Cada uma leva a um ICP
  diferente.** Não escolha uma no escuro.
- **O ICP da RP hoje provavelmente é "quem foi indicado por um cliente satisfeito"** —
  hipótese, não dado. Se for, o perfil real está na base instalada, não no funil de entrada.
- **Não use ticket nenhum.** Não existe.

## 10.4 → Agente 5 (analise-concorrentes)

- **D10 é sua:** contra quem a RP disputa, por nome, e para quem costuma perder. **Zero
  concorrentes foram citados no briefing.**
- **R2 é o teste que você fecha.** A hipótese de commoditização está **aberta, não
  descartada**. O motivo de perda não foi declarado. Sua análise externa é a segunda fonte
  para testá-la — se o mercado regional inteiro publicar só preço, sem prazo de instalação,
  garantia detalhada nem simulação de financiamento, isso sustenta a hipótese mesmo sem o
  dado interno.
- **Verifique o que a pesquisa do agente 1 não conseguiu:** site rpsolucoesinteligentes.com.br,
  Instagram e **Google Meu Negócio (nota e nº de avaliações)** ficaram como **não
  verificados** por bloqueio de rede. Presença técnica é o bloco 4 do Raio-X de
  posicionamento e é a prioridade 2 do meu item 6.4 — com custo quase zero e prazo de dias.
- **Olhe um concorrente que a RP não tem:** o modelo de franquia é incomum entre
  integradoras. Se houver outra operação regional com estrutura parecida, ela é a
  comparação mais informativa que você pode trazer.
- **Não compare preços.** Não temos o preço da RP.

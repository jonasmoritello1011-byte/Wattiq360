# 02 — Perdas Financeiras · LEOSOL

> Base: `diagnosticos/leosol/01-diagnostico.md` (passagem de bastão do agente 1) +
> `referencia/playbook-wattiq360.md`.
> Janela: **últimos 30 dias** (≈ 08/08/2026 a 07/09/2026).
> Unidade de conta usada em todo o documento: **ticket R$ 20.000 × margem 30% =
> R$ 6.000 de margem por contrato** (ambos informados pelo dono, confiança alta).
> **Nenhum número foi inventado.** O que depende de estimativa está marcado como
> estimativa na própria linha da conta.

---

## Aviso obrigatório sobre a precisão deste documento

A LEOSOL **não mede contato efetivo, qualificados nem diagnósticos**. Os 40 leads que
somem entre a entrada e a proposta **não podem ser atribuídos a uma etapa específica**.
Consequência direta no cálculo: **todas as perdas do trecho lead→proposta saem em faixa,
nunca em ponto, e a faixa é larga porque a empresa não mede o meio do funil.**

Isso não é um defeito do cálculo — é o retrato do problema. Uma empresa que mede o meio
do funil recebe deste relatório uma faixa estreita. A LEOSOL recebe uma faixa larga
porque essa é a informação que existe hoje.

Três coisas que este documento **não** faz, por falta de dado:
- **Não calcula custo por lead, custo por projeto nem ROI de mídia.** O investimento em
  marketing não foi informado. Sem investimento não há retorno para calcular. Não estimo.
- **Não converte "a maioria das vendas vem de indicação" em percentual.** "Maioria" foi o
  que o dono disse; percentual seria invenção minha.
- **Não projeta receita de reativação de base parada.** Clientes instalados e orçamentos
  antigos: zero informação. Projetar aqui seria número bonito e indefensável.

---

## 1. O número da capa

**No cenário conservador, a LEOSOL deixa R$ 10.900 de margem por mês na mesa — R$ 130.800
por ano — em dinheiro que já entrou no funil e vazou antes de virar contrato. Separado
disso, e sem sobrepor, outros R$ 48.000 de margem por mês simplesmente não acontecem
porque a agenda de um vendedor único comporta 20 propostas e a meta pede 43.**

Em faturamento: **R$ 36.300/mês** vazando (R$ 435.600/ano) e **R$ 160.000/mês** que nunca
entram no funil (R$ 1.920.000/ano).

São dois problemas diferentes, com dois preços diferentes e duas soluções diferentes. Eles
**não se somam** — explicação no item 5.

---

## 2. Tabela resumo

### 2.1 Perdas correntes — dinheiro que vaza do funil que já existe (somáveis)

| # | Perda | Mensal (margem) | Anual (margem) | Mensal (faturamento) | Confiança |
|---|---|---|---|---|---|
| P1 | Trecho cego lead → proposta (40 leads/mês sem rastro) | **R$ 8.400** | R$ 100.800 | R$ 28.000 | **Baixa-média** |
| P2 | Propostas que morrem sem cadência D+0→D+15 | **R$ 2.500** | R$ 30.000 | R$ 8.300 | **Baixa** |
| | **TOTAL CONSERVADOR** | **R$ 10.900/mês** | **R$ 130.800/ano** | R$ 36.300/mês | **Baixa-média** |

### 2.2 Quantificações que NÃO entram no total (para não contar o mesmo dinheiro duas vezes)

| # | Item | Valor | Por que não soma | Confiança |
|---|---|---|---|---|
| P3 | Resposta em 10 min vs. janela de 5 min | R$ 950/mês · R$ 11.400/ano | É um **mecanismo dentro de P1** — esses leads já estão contados nos 40 | Baixa |
| P4 | Teto de agenda do vendedor único | R$ 48.300/mês de margem não realizada | É o **gap inteiro da meta** visto pelo ângulo da capacidade; engloba P1 e P2 | Média |
| P5 | Horas do dono gastas triando lead que não vira proposta | ~17 h/mês | É **capacidade**, não receita; é o que torna P1 capturável | Baixa |
| R1 | Concentração em indicação acima de 50% | > R$ 10.500/mês de margem **exposta** | É **risco**, não perda corrente. Nada foi perdido ainda | Existência: alta · Tamanho: não quantificado |

### 2.3 O que não deu para calcular

**8 itens** — detalhados no bloco 7, cada um com a pergunta exata que destrava.

---

## 3. Detalhe de cada perda

### P1 — Trecho cego: 40 leads/mês que somem antes da proposta

**Perda estimada: R$ 8.400/mês (R$ 100.800/ano) de margem — R$ 28.000/mês de faturamento**

```
Conta:
  40 leads/mês que não viram proposta   (60 − 20, informado pelo cliente, confiança ALTA)
× 10% recuperáveis com SLA de resposta, roteiro de qualificação e registro das etapas
       (ESTIMADO — piso de uma faixa de 10% a 25%; confiança BAIXA, ver nota)
× 35% de proposta → contrato            (taxa real da empresa, informada, confiança ALTA)
× R$ 6.000 de margem por contrato       (R$ 20.000 × 30%, informados, confiança ALTA)
= R$ 8.400/mês
```

**Confiança do resultado: baixa-média.** Três dos quatro fatores são dados duros do
cliente. O fator que quebra a confiança é a taxa de recuperação — e ela é o fator que
multiplica tudo.

**A nota que precisa ser lida antes de discutir o número.** Não sei, e a empresa também
não sabe, **por que** os 40 leads somem. Podem ser quatro coisas com quatro correções e
quatro custos diferentes: nunca foram respondidos de verdade; foram respondidos e não
tinham perfil (nesse caso a qualificação está funcionando e a perda é de geração, não de
atendimento); tinham perfil e não avançaram; foram visitados e não receberam proposta.
**Uma parte desses 40 é lixo legítimo — lead sem telhado, sem titularidade, sem intenção.
Recuperar 100% seria mentira.** Por isso a faixa começa em 10%.

**Por que 10% no conservador e não mais.** Se dos 40 leads apenas 4 virarem proposta por
mês, a taxa lead→proposta sobe de 33,3% para 40%. É um ganho modesto e comum de se obter
só com SLA de resposta e um roteiro escrito de qualificação. O teto da faixa (25%, ou 10
propostas extras, levando a taxa a 50%) exige que boa parte dos 40 seja de leads com
perfil — o que **não está demonstrado**.

**Como confirmar (pergunta A1 e A2 do diagnóstico):** registrar por 30 dias, na ficha
semanal, quantos leads tiveram contato efetivo, quantos passaram nos 8 critérios mínimos
e quantos receberam diagnóstico. Com esses três números, esta faixa de 10–25% vira um
número único e a perda ganha confiança alta. **Sem eles, qualquer valor aqui é faixa.**

---

### P2 — Propostas que morrem sem cadência D+0 → D+15

**Perda estimada: R$ 2.500/mês (R$ 30.000/ano) de margem — R$ 8.300/mês de faturamento**

> **Premissa explícita e frágil:** este cálculo vale **se não houver cadência estruturada
> após a proposta**. A cadência da LEOSOL **não foi informada** — o diagnóstico registra a
> pergunta de controle nº 5 como "não informado", não como "não". **Não estou afirmando
> que a empresa não faz follow-up.** Estou calculando quanto vale o problema **caso** ele
> exista, para que a pergunta B2 na próxima call tenha um preço em cima dela.

```
Conta:
  13 propostas/mês não fechadas          (20 − 7, informado pelo cliente, confiança ALTA)
× 40% que morrem por silêncio, sem a sequência D+0→D+15
       (ESTIMADO — piso de uma faixa de 40% a 70%; confiança BAIXA)
× 8% recuperáveis com cadência estruturada
       (referência de mercado, NÃO É GARANTIA; piso da faixa 8%–15%; confiança BAIXA)
× R$ 6.000 de margem por contrato        (informado, confiança ALTA)
= R$ 2.496/mês → R$ 2.500/mês
```

**Confiança do resultado: baixa.** Dois fatores estimados em sequência, um deles
multiplicando o outro. É o número mais frágil deste relatório.

**Digo com todas as letras: esta perda é pequena, e isso contraria o padrão.** Na maioria
das integradoras a cadência pós-proposta é a maior perda isolada. Na LEOSOL não é — por um
motivo aritmético simples: **só existem 13 propostas perdidas por mês para recuperar.** Uma
cadência perfeita sobre uma base pequena rende pouco. O follow-up estruturado da LEOSOL vale
mais como **infraestrutura para quando o volume de propostas dobrar** do que como resgate do
volume de hoje. Inflar este número seria destruir a proposta na primeira pergunta do dono.

**Referência do playbook, que é referência e não garantia:** cadência de 6 a 8 tentativas
em 7 dias, e o comprador de solar compara **mais de 3 fornecedores** antes de decidir. Quem
não faz cadência entrega a decisão ao concorrente que faz.

**Como confirmar (pergunta B2):** "O que você faz quando o cliente não responde a proposta?
Quantas vezes você volta, e em quanto tempo?" E (pergunta B1): "Das 13 que não fecharam,
quantas foram perdidas para concorrente, quantas ficaram **sem resposta** e quantas viraram
'vou pensar'?" **Só a segunda pergunta separa perda por silêncio (que a cadência corrige) de
perda por preço (que a cadência não corrige).** Sem ela, os 40% acima são chute honesto.

---

### P3 — Resposta em 10 minutos contra a janela de 5 minutos *(não somada ao total)*

**Perda estimada: R$ 950/mês (R$ 11.400/ano) de margem**

```
Conta:
   9 leads/mês respondidos muito fora da janela
       (60 leads × 15% de cauda ESTIMADA — 10 min é MÉDIA, não teto; com vendedor único
        em obra, parte dos leads espera horas. Distribuição NÃO conhecida. Confiança BAIXA)
× +5 pontos percentuais de conversão lead→proposta com resposta imediata
       (ESTIMADO conservadoramente; confiança BAIXA)
× 35% de proposta → contrato             (informado, confiança ALTA)
× R$ 6.000 de margem por contrato        (informado, confiança ALTA)
= R$ 945/mês → R$ 950/mês
```

**Este número é pequeno de propósito, e o pequeno é o achado.**

**Por que não apliquei o benchmark dos 23%.** O playbook registra 23% de conversão
respondendo em até 1 minuto no WhatsApp contra 1% depois de um dia, e que só 7% das
empresas respondem em até 5 minutos. **São referências do material-base, não garantias de
resultado.** Aplicar os 23% sobre os 60 leads produziria "13,8 contratos por mês só
respondendo mais rápido" — um número que não sobrevive à primeira pergunta do dono, porque
o benchmark compara 1 minuto com **um dia**, e a LEOSOL está em **10 minutos**. Não existe
ponto de referência publicado para o delta entre 5 e 10 minutos. Inventar esse delta seria
o erro mais caro deste documento.

**Contexto honesto para o dono:** 10 minutos **não é um resultado ruim de mercado**. Se só
7% das empresas respondem em até 5 minutos, a LEOSOL com 10 minutos está longe do pior
cenário e perto da janela ideal. Fechar de 10 para menos de 5 é ganho real, é barato de
fazer e vale a pena — **mas não é aqui que estão os 40 leads perdidos.** Dez minutos não
derruba dois terços de um funil. Quem vender "resposta imediata" como solução do problema
da LEOSOL está vendendo a coisa errada.

**Por que não somo ao total:** os leads da cauda lenta **já estão dentro dos 40** contados
em P1. Somar seria contar o mesmo dinheiro duas vezes. P3 é uma **decomposição parcial de
P1**, não uma perda adicional.

**Como confirmar (pergunta C2 e C3):** qual o horário de atendimento, o que acontece com o
lead que chega 21h de sábado, e qual o pior tempo de resposta do mês — não a média.

---

### P4 — Teto de agenda: o dono é o único vendedor *(não somada ao total)*

**Receita não realizada por limite de capacidade: R$ 161.000/mês de faturamento —
R$ 48.300/mês de margem — R$ 579.600/ano de margem**

```
Conta:
  23 propostas/mês que a agenda não comporta
       (43 propostas exigidas pela meta − 20 propostas realizadas;
        43 = 15 contratos ÷ 35%, aritmética sobre dados do cliente, confiança ALTA
        20 = teto observado do dono, informado, confiança ALTA)
× 35% de proposta → contrato             (informado, confiança ALTA)
× R$ 20.000 de ticket médio              (informado, confiança ALTA)
= R$ 161.000/mês de faturamento → R$ 48.300/mês de margem (30%)
```

**Confiança do resultado: média.** A aritmética é sólida e todos os fatores são dados do
cliente. O que a rebaixa para média é uma premissa de comportamento: **que 20 propostas/mês
é de fato o teto do dono, e não uma escolha.**

**A premissa, dita com clareza:** 20 propostas/mês é aproximadamente **1 proposta por dia
útil**, feita pela mesma pessoa que responde o primeiro contato, qualifica, visita,
dimensiona, negocia, fecha, faz o handoff, **e ainda dirige uma empresa de 5 pessoas e
acompanha obra, banco e homologação**. Trato 20 como teto porque é o volume que ele
efetivamente entrega hoje com todo esse acúmulo. Se ele disser "eu consigo fazer 30 se me
tirarem a triagem", o número muda — e essa é exatamente a conversa que o item P5 abre.

**Por que este número NÃO se soma às perdas correntes.** R$ 48.300/mês de margem é
**exatamente o gap da meta** (R$ 300.000 − R$ 140.000 = R$ 160.000 de faturamento × 30% =
R$ 48.000; a diferença de R$ 300 é arredondamento). Ou seja: este valor **engloba** P1 e P2.
Somá-los daria um total inflado que o dono derruba em trinta segundos com uma pergunta:
"mas isso é mais do que eu deixei de faturar."

**O que P4 realmente diz, e é a frase mais importante deste relatório:** *nenhum ganho de
conversão, por maior que seja, entrega os R$ 300.000/mês dentro de uma agenda só.* Mesmo
com o funil corrigido, a meta exige 38 propostas/mês (ver item 4) e o dono comporta ~20.
**A meta de R$ 300.000 não é um problema de conversão nem de tráfego — é um problema de
capacidade que a conversão sozinha não resolve.**

**Risco de continuidade, que não tem preço mensal mas tem preço de evento:** se o dono
adoece, viaja ou entra numa obra grande, a receita comercial vai a zero naquela semana. Duas
semanas fora ≈ **R$ 70.000 de faturamento** (metade do mês). Não há redundância nem registro
que permita outra pessoa assumir uma oportunidade no meio. **Confiança: alta na mecânica,
não estimo probabilidade do evento.**

---

### P5 — Horas do dono gastas triando lead que não vira proposta *(não somada ao total)*

**Custo de oportunidade: ~17 horas/mês — equivalente a ~8 propostas de capacidade**

```
Conta:
  40 leads/mês que não viram proposta    (informado, confiança ALTA)
× ~25 minutos médios de triagem inicial por lead
       (ESTIMADO por mim — o dono NÃO informou esse tempo; confiança BAIXA)
= ~1.000 minutos = ~16,7 horas/mês do recurso mais caro e mais escasso da empresa

Traduzido em capacidade:
  17 horas ÷ ~2 horas por proposta (diagnóstico + dimensionamento + apresentação,
  ESTIMADO, confiança BAIXA) = ~8 propostas/mês de capacidade que hoje vão para triagem
```

**Confiança do resultado: baixa.** Os dois fatores de tempo são estimativa minha, não dado
do cliente. **Não converto isso em reais** — seria empilhar chute sobre chute. Fica em
horas e em propostas, que é a unidade em que o dono consegue conferir se faz sentido.

**Por que este item existe no relatório mesmo sendo frágil:** ele é o **mecanismo econômico
que torna P1 capturável**. P1 diz que existem propostas a mais para fazer; P4 diz que a
agenda não comporta. P5 é a ponte: **qualificação feita antes do dono devolve horas para a
agenda dele**. Sem esse item, P1 e P4 se contradizem.

**Como confirmar:** "Quanto tempo, em média, você gasta com um lead **antes** de decidir se
ele vira proposta? E com um que não vira?" Dois minutos de conversa fecham este número.

---

### R1 — Concentração em indicação: risco de receita exposta, não perda corrente

**Receita exposta: mais de R$ 70.000/mês de faturamento — mais de R$ 840.000/ano**
**Impacto de uma queda pela metade do canal: mais de R$ 35.000/mês de faturamento,
mais de R$ 10.500/mês de margem**

```
Conta:
  R$ 140.000/mês de faturamento          (informado, confiança ALTA)
× "mais de 50%" vindo de indicação
       (o dono disse "a maioria das vendas vem de indicação". "Maioria" significa,
        por definição, mais da metade. NÃO converto "maioria" em percentual —
        o percentual exato NÃO FOI QUANTIFICADO. Confiança: existência ALTA, tamanho NULO)
= mais de R$ 70.000/mês de faturamento dependente de um canal só

Se esse canal cair pela metade:
  R$ 70.000 × 50% = mais de R$ 35.000/mês de faturamento → mais de R$ 10.500/mês de margem
```

**Isto é risco, e apresento como risco.** Nada foi perdido. Nenhum real deste valor entra no
total de perdas. É a quantificação de uma exposição.

**A regra dos 50% do playbook:** nenhum canal isolado deveria representar mais da metade das
oportunidades de um mês — concentração é risco que só aparece quando o canal falha. **Por
declaração do próprio dono, a LEOSOL está fora dessa regra.**

**As duas leituras, e as duas valem:**
1. **É ativo real.** Indicação é o canal de menor custo e maior conversão do setor
   (playbook). Seis anos em Franca construíram isso. Não é sorte.
2. **É a razão pela qual a meta não sai.** Indicação **não é canal de volume controlável**.
   Não se compra mais indicação para bater setembro. Para sair de R$ 140k para R$ 300k a
   empresa precisa de um canal que ela consiga **ligar e desligar** — e hoje não tem, ou tem
   e não mediu.

**Um agravante barato de corrigir:** se a maioria das vendas vem de indicação **espontânea**,
o canal principal da empresa está rodando **sem sistema**. Não há programa estruturado de
pedido de indicação (não informado, pergunta C8). O canal que mais entrega é o único que
ninguém opera.

**Como dimensionar o risco (pergunta A3):** "Dos 60 leads, quantos vieram de indicação e
quantos de cada outra origem? E dos 7 contratos?" Com esses dois números, "mais de 50%" vira
um percentual, o risco ganha tamanho, e se descobre de quebra se indicação converte melhor
que o resto — o que muda a estratégia de geração inteira.

---

## 4. Meta reversa — o argumento central

Meta: **R$ 300.000/mês = 15 contratos/mês** (R$ 300.000 ÷ R$ 20.000, aritmética sobre dado
informado, confiança alta). Hoje: **7 contratos, R$ 140.000, 47% da meta.**

### 4.1 Com as taxas de hoje

```
15 contratos ÷ 35,0% (proposta→contrato de hoje)  = 42,9 → ~43 propostas/mês
43 propostas ÷ 33,3% (lead→proposta de hoje)      = 128,6 → ~129 leads/mês
premissa: assume as duas taxas atuais constantes
confiança: média (aritmética sobre dados do cliente, com premissa de taxas constantes)
```

### 4.2 Com as taxas corrigidas pelo plano

```
Taxa-alvo lead→proposta: 50% (hoje 33,3%)
premissa: SLA de resposta abaixo de 5 min + roteiro único de qualificação com os
8 critérios mínimos + registro das três etapas hoje cegas. Recupera cerca de metade
do vazamento evitável. É PROJEÇÃO, não promessa. Confiança BAIXA-MÉDIA.

Taxa-alvo proposta→contrato: 40% (hoje 35%)
premissa: cadência D+0→D+15 + proposta apresentada em reunião, não enviada por WhatsApp.
Ganho deliberadamente modesto (+5 pontos): esta etapa JÁ ESTÁ SAUDÁVEL, o dono fecha bem
o que apresenta. Prometer mais aqui seria inflar. Confiança BAIXA-MÉDIA.

15 contratos ÷ 40% = 37,5 → ~38 propostas/mês
38 propostas ÷ 50% = 75 leads/mês
```

### 4.3 O contraste — é aqui que a decisão é tomada

| Para 15 contratos/mês | Taxas de hoje | Taxas corrigidas | Diferença |
|---|---|---|---|
| **Leads/mês necessários** | **~129** | **~75** | **−54 leads/mês (−42%)** |
| **Propostas/mês necessárias** | ~43 | ~38 | −5 |
| Contratos/mês | 15 | 15 | — |
| **Aumento de leads exigido (partindo de 60)** | **+69 leads (+115%)** | **+15 leads (+25%)** | |
| Taxa lead→contrato implícita | 11,7% | 20,0% | |

**Leia deste jeito:** para bater a meta **sem mexer no processo**, a LEOSOL precisa **mais
que dobrar a geração de leads** — sair de 60 para 129 por mês. Num negócio cujo canal
principal é **indicação**, que não se compra e não se acelera, isso é inviável. Com o funil
corrigido, a mesma meta exige **75 leads/mês: 15 a mais do que já entram.** É a diferença
entre "preciso de uma máquina de aquisição que a empresa não tem" e "preciso de um quarto a
mais de leads e um processo que não deixe dois terços caírem no caminho".

**E a parte que o plano não pode esconder:** mesmo com as taxas corrigidas, a meta pede
**38 propostas/mês** e o dono comporta **~20**. **Conversão sozinha não entrega os
R$ 300.000.** A meta exige as três coisas juntas: processo (para converter), volume moderado
de leads (+25%) e **capacidade adicional de venda** — seja mais um par de mãos, seja a IA
devolvendo ao dono as ~17 horas/mês que ele gasta triando (P5). Ordem do playbook:
**processo primeiro, escala depois.**

### 4.4 Cenário intermediário: o que os 60 leads de hoje já entregam com o funil corrigido

```
60 leads (os que JÁ entram, sem comprar um a mais)
× 50% lead→proposta corrigido  = 30 propostas — acima do teto atual do dono
Limitando ao teto realista de ~26 propostas/mês (20 de hoje + parte das horas
liberadas por P5; ESTIMADO, confiança BAIXA):
26 propostas × 40% = 10,4 contratos/mês = R$ 208.000/mês de faturamento
                                        = R$ 62.400/mês de margem
Ganho sobre hoje: +R$ 68.000/mês de faturamento, +R$ 20.400/mês de margem
```

**Isto é projeção, não promessa contratual, e depende de três premissas de confiança baixa
(as duas taxas-alvo e o teto de 26).** Serve para uma coisa só: mostrar que existe um
caminho de **R$ 140k → ~R$ 208k sem comprar um lead a mais**, e que os R$ 300k exigem, além
disso, geração e gente.

---

## 5. Os três cenários

**Perdas correntes somáveis, em margem por mês.** Os itens não-somáveis (P3, P4, P5, R1)
ficam de fora dos totais por construção, para não contar o mesmo dinheiro duas vezes.

| Componente | Conservador | Provável | Otimista |
|---|---|---|---|
| **P1 — Trecho cego lead→proposta** | R$ 8.400 | R$ 12.600 | R$ 21.000 |
| *fator de recuperação usado* | *10% dos 40 leads* | *15%* | *25%* |
| **P2 — Propostas sem cadência** | R$ 2.500 | R$ 4.700 | R$ 8.200 |
| *fatores usados* | *40% morrem × 8% recuperáveis* | *55% × 11%* | *70% × 15%* |
| **TOTAL margem/mês** | **R$ 10.900** | **R$ 17.300** | **R$ 29.200** |
| **TOTAL margem/ano** | **R$ 130.800** | **R$ 207.600** | **R$ 350.400** |
| **TOTAL faturamento/mês** | R$ 36.300 | R$ 57.700 | R$ 97.300 |
| **Contratos/mês recuperados** | +1,8 | +2,9 | +4,9 |
| **Contratos/mês resultantes** | 8,8 | 9,9 | 11,9 |
| **Faturamento/mês resultante** | R$ 176.300 | R$ 197.700 | R$ 237.300 |

**Como cada cenário foi montado:**
- **Conservador** — piso de todas as faixas. Nenhum item de confiança baixa entra pelo teto,
  P3/P4/P5/R1 fora. **É o número que vai para a conversa.**
- **Provável** — meio das faixas. É o cenário que eu defendo se questionado.
- **Otimista** — teto de todas as faixas. Só se sustenta se a próxima call mostrar que boa
  parte dos 40 leads tinha perfil e que não existe cadência nenhuma hoje.

**Teste de sanidade, que o dono vai fazer e por isso faço antes:** mesmo no **otimista**, a
LEOSOL chega a ~R$ 237.000/mês — **abaixo da meta de R$ 300.000**. Isso é coerência, não
pessimismo: confirma que corrigir o funil, sozinho, não entrega a meta. Qualquer relatório
que fizesse a correção de processo chegar aos R$ 300.000 estaria mentindo ou ignorando o
teto de agenda.

---

## 6. Uma conta que não é perda, mas que pode ser maior que todas elas: desconto

**Não sei o desconto médio da LEOSOL. Ele não foi informado.** Mas o motivo de perda
declarado é **preço/concorrência**, o que torna quase certo que existe desconto. Então não
estimo o desconto — mostro a **sensibilidade**, que é aritmética pura sobre dados
informados, e deixo o dono preencher o número.

Ticket R$ 20.000 · margem 30% = R$ 6.000 de margem por contrato:

| Desconto dado | Sai do bolso | Margem que sobra | Margem perdida | Custo nas 7 vendas/mês |
|---|---|---|---|---|
| 3% | R$ 600 | R$ 5.400 | **−10,0%** | R$ 4.200/mês |
| 5% | R$ 1.000 | R$ 5.000 | **−16,7%** | R$ 7.000/mês |
| 8% | R$ 1.600 | R$ 4.400 | **−26,7%** | R$ 11.200/mês |
| 10% | R$ 2.000 | R$ 4.000 | **−33,3%** | R$ 14.000/mês |
| 15% | R$ 3.000 | R$ 3.000 | **−50,0%** | R$ 21.000/mês |

*(Aritmética sobre ticket e margem informados — confiança alta na conta, nula na
frequência: **não sei quantas vendas levam desconto nem de quanto**.)*

**A frase que importa:** se o desconto médio da LEOSOL for de **8%**, ele custa
**R$ 11.200/mês de margem — mais do que toda a perda conservadora de funil calculada neste
relatório (R$ 10.900).** Uma linha que não consigo medir pode ser maior que tudo que eu
medi. É por isso que a pergunta B4 é prioritária.

**Por que isso vira urgente no dia em que entrar um vendedor** (e a meta exige que entre).
O playbook é explícito: comissão **sobre margem**, nunca sobre faturamento. No exemplo do
playbook — venda de R$ 42 mil, comissão de 4%, desconto de 8% — a comissão sobre faturamento
cai 8% e a comissão sobre margem cai **73%**. **Traduzindo para os números reais da LEOSOL,
o efeito é menor, e é honesto dizer isso:** com margem de 30% (bem acima da margem implícita
no exemplo do playbook), um desconto de 8% numa venda de R$ 20.000 reduziria a comissão
sobre faturamento em 8% e a comissão sobre margem em **26,7%** — não 73%. Mas a direção é a
mesma e o princípio não muda: **sobre faturamento, dar desconto custa R$ 64 ao vendedor e
R$ 1.600 à empresa. Sobre margem, custa proporcionalmente a ele também.** O vendedor que não
sente o desconto, dá o desconto — e o motivo de perda declarado da LEOSOL é exatamente preço.

**Hoje isso não se aplica:** quem vende é o dono, e ele sente cada real. **A decisão precisa
estar tomada antes da primeira semana do primeiro vendedor**, não depois.

---

## 7. Não quantificável hoje — com a pergunta que destrava cada item

| # | O que não deu para calcular | Por que trava | Pergunta que destrava |
|---|---|---|---|
| 1 | **Onde exatamente morrem os 40 leads** | Sem contato efetivo, qualificados e diagnósticos, P1 fica em faixa de 10–25% em vez de número único. É o fator que multiplica a maior perda do relatório | **A1:** "Dos 60 leads do mês, em quantos você conseguiu falar de fato? Quantos tinham perfil (telhado, conta, decisor)? Em quantos você fez visita ou diagnóstico?" |
| 2 | **Leads que ficaram sem nenhuma resposta** | É a perda mais barata de corrigir e a mais fácil de calcular — e o número não existe | **A2:** "Quantos dos 60 leads ficaram sem nenhuma resposta?" |
| 3 | **Tamanho real da concentração em indicação** | "Maioria" não vira percentual. R1 fica preso em "mais de 50%" e o risco não ganha tamanho | **A3:** "Dos 60 leads, quantos vieram de indicação e quantos de cada outra origem? E dos 7 contratos?" |
| 4 | **Custo por lead, custo por projeto e ROI de mídia** | Investimento em marketing não informado. **Sem investimento não há retorno para calcular. Não estimo CPL de canal nenhum.** Dois KPIs do playbook ficam vazios e nenhuma correção de geração pode ser justificada por retorno | **A4:** "Quanto você investiu em marketing no mês, e em quê?" |
| 5 | **Desconto médio e a margem que ele consome** | Perda que **sei que existe** (motivo declarado é preço) e **não consigo medir**. Pela tabela do item 6, pode ser maior que todas as perdas somadas | **B4:** "Qual o desconto médio que você acaba dando para fechar? Em quantas das 7 vendas do mês houve desconto?" |
| 6 | **Motivos de perda 2 e 3 das 13 propostas** | Só "preço/concorrência" foi informado. **Não distribuo as 13 propostas entre causas sem esse dado** — perda por silêncio se corrige com cadência, perda por preço se corrige com argumento e financiamento. Custos diferentes | **B1:** "Das 13 que não fecharam, quantas foram para concorrente, quantas ficaram sem resposta e quantas viraram 'vou pensar'?" |
| 7 | **Base parada: instalados de 6 anos + orçamentos antigos** | **Zero informação. Não projeto receita de reativação.** É o canal de custo mais baixo do playbook, na empresa que mais depende de indicação, e o volume nem foi levantado | **A5:** "Quantos clientes instalados você tem no total dos 6 anos? E quantos orçamentos antigos não fechados estão guardados?" |
| 8 | **Leads fora do horário** | Cobertura de horário não informada. Com uma pessoa só, a hipótese é que o lead de sábado à noite espera até segunda — **mas é hipótese, e não entra como perda** | **C2:** "Qual o horário em que vocês respondem, e o que acontece com o lead que chega 21h de sábado?" |
| 9 | **Se o mês medido é típico** | **Todo este relatório se multiplica por ticket e margem.** Se os últimos 30 dias foram acima ou abaixo do normal, todos os números se deslocam junto | **B5:** "Os R$ 20.000 de ticket e os 30% de margem são de quais 30 dias? Foi um mês típico?" |

---

## 8. Custo da inação — 12 meses sem mudar nada

Se nada mudar, e mantidos ticket, margem e volume de leads de hoje:

| O que acontece em 12 meses | Valor |
|---|---|
| **Margem que continua vazando do funil** (conservador) | **R$ 130.800** |
| Faturamento correspondente | R$ 435.600 |
| **Margem da meta que não acontece** (gap × 12, não somável ao acima) | **R$ 576.000** |
| Faturamento da meta não realizado | **R$ 1.920.000** |
| **Leads que entram e somem sem rastro** | **480 leads** |
| **Propostas que não fecham sem motivo catalogado** | **156 propostas** |
| Contratos deixados na mesa (conservador, 1,8/mês) | ~22 contratos |
| Contratos deixados na mesa (provável, 2,9/mês) | ~35 contratos |

**O que os números não mostram e piora sozinho:**

- **A cegueira composta.** Em 12 meses sem instrumentação, a LEOSOL terá 480 leads perdidos
  e continuará sem saber onde. **Etapa que não se mede é a única que não melhora**, porque
  não há como saber se melhorou. Este é o único item da lista que **não** é resolvido com
  dinheiro depois — o histórico não volta.
- **A concentração não se dissolve, se aprofunda.** Sem canal controlável, cada mês que passa
  a receita depende mais de indicação espontânea. Mais de R$ 840.000/ano de faturamento
  seguem expostos a um canal que a empresa não opera e não pode acelerar. O dia em que ele
  oscilar, não há alavanca de reação — construir canal leva meses.
- **A meta vira ficção interna.** Meta que fica em 47% por doze meses deixa de ser meta e
  vira número de parede. Depois disso, qualquer meta na empresa perde credibilidade —
  inclusive as boas.
- **O gargalo continua sendo uma pessoa.** Doze meses a mais de funil inteiro na cabeça de
  um único vendedor que também dirige a empresa. Duas semanas de ausência dele custam
  **~R$ 70.000 de faturamento**, e a probabilidade de duas semanas de ausência em 12 meses
  não é pequena. Nada disso está registrado em lugar nenhum que permita outra pessoa
  assumir.
- **O custo de esperar para decidir a comissão.** Se um vendedor entrar antes de a base de
  comissão estar definida **sobre margem**, corrigir depois é conflito, não ajuste.

**Contraponto honesto, para o dono não ser levado por número grande:** a LEOSOL não é uma
empresa quebrada. Fecha **35% do que apresenta**, tem 6 anos de reputação em Franca,
responde em 10 minutos num mercado onde 93% das empresas demoram mais de 5, e vive de
indicação — que é o canal mais barato e de maior conversão que existe. **O problema dela não
é vender. É que só uma pessoa vende, e dois terços do que entra some num trecho que ninguém
mede.** São dois problemas resolvíveis, e nenhum deles é o produto.

---

## Passagem de bastão → plano-ideal

**Perda total (conservador):** **R$ 10.900/mês | R$ 130.800/ano** de margem
(R$ 36.300/mês | R$ 435.600/ano de faturamento).
*Este é o dinheiro que vaza do funil de hoje. **Não inclui** o gap da meta.*

**Gap da meta, separado e não somável:** R$ 48.000/mês | R$ 576.000/ano de margem
(R$ 160.000/mês | R$ 1.920.000/ano de faturamento).

**Top 3 perdas com valor e confiança:**
1. **Trecho cego lead → proposta** — R$ 8.400/mês (R$ 100.800/ano) — **confiança
   baixa-média**. Faixa real: R$ 8.400 a R$ 21.000/mês. A faixa é larga porque a empresa
   não mede contato efetivo, qualificação nem diagnóstico.
2. **Propostas sem cadência D+0→D+15** — R$ 2.500/mês (R$ 30.000/ano) — **confiança baixa**,
   e sob premissa explícita de que não existe cadência (não confirmado). **Perda pequena, e
   digo que é pequena:** só há 13 propostas perdidas/mês para trabalhar.
3. **Resposta em 10 min vs. 5 min** — R$ 950/mês (R$ 11.400/ano) — **confiança baixa**, e
   **contida em (1)**, não somada. Registrada aqui para deixar explícito que **é pequena** e
   que não se deve vender velocidade de resposta como a solução da LEOSOL.

**Gargalo dominante confirmado (ou corrigido) pelo dinheiro:**
**Confirmado, com uma correção de ênfase.** O dinheiro confirma o agente 1: o maior valor
vaza no trecho **lead → proposta** (R$ 8.400 a R$ 21.000/mês). **Mas o dinheiro acrescenta
uma coisa que o diagnóstico tratou como causa estrutural e que na verdade é restrição
dominante da meta: o teto de agenda do vendedor único.** Corrigir o funil ao máximo leva a
LEOSOL a ~R$ 237.000/mês no cenário otimista — **nunca aos R$ 300.000**, porque 38 propostas
não cabem numa agenda de 20. **O gargalo do resultado atual é o trecho cego. O gargalo da
meta é a capacidade. O plano precisa endereçar os dois, nessa ordem.**

**Meta reversa:** hoje exige **~129 leads/mês** e ~43 propostas/mês; com o funil corrigido
(lead→proposta 50%, proposta→contrato 40% — projeções de confiança baixa-média, não
promessas), exige **~75 leads/mês** e ~38 propostas/mês. **Diferença: 54 leads/mês a menos.
Em vez de +115% de geração, +25%.** Esse contraste é o argumento central da proposta.
**Ressalva que não pode cair da proposta:** 38 propostas continuam acima do teto de ~20 do
dono — a meta exige processo **e** capacidade.

**Perda endereçável por camada (cenário conservador):**
- **Geração (Agente de Marketing): R$ 0 quantificável hoje.** Sem investimento em marketing
  informado e sem origem dos leads, **não há CPL, custo por projeto nem ROI para calcular**.
  O que existe é **risco dimensionado**: mais de R$ 70.000/mês de faturamento exposto à
  indicação, mais de R$ 10.500/mês de margem em jogo se o canal cair pela metade. Destrava
  com as perguntas A3 e A4. **A meta exige um canal que se possa ligar e desligar — e é
  aqui que os +15 leads/mês da meta reversa corrigida têm que sair.**
- **Atendimento + Qualificação (Agente SDR): R$ 8.400/mês | R$ 100.800/ano** (faixa até
  R$ 21.000/mês). Inclui os R$ 950/mês de tempo de resposta, que **não devem ser somados
  por fora**. **É a maior perda endereçável e a de menor custo de ataque, porque começa com
  medição, não com ferramenta.** Ganho secundário e decisivo: devolve ~17 h/mês à agenda do
  dono (P5) — sem isso, a recuperação de leads não tem onde caber.
- **Cadência pós-proposta (Agente de Follow-up): R$ 2.500/mês | R$ 30.000/ano** (faixa até
  R$ 8.200/mês). **Não vender isto como a maior perda — na LEOSOL não é.** O valor real aqui
  é ser a infraestrutura pronta para quando as propostas passarem de 20 para ~38.
- **Venda + Gestão (Mentoria): o item de maior valor e o menos somável.** R$ 48.300/mês de
  margem não realizada por teto de agenda; instrumentação das três etapas cegas (que é o que
  transforma toda faixa deste relatório em número); definição da base de comissão **sobre
  margem** antes do primeiro vendedor; política de desconto — que pode valer R$ 11.200/mês
  se o desconto médio for 8%, mais que toda a perda de funil calculada.

**Premissas frágeis a validar antes da proposta:**
1. **10% a 25% de recuperação dos 40 leads (P1)** — estimativa minha, confiança baixa,
   multiplica a maior perda do relatório. Destrava com A1 e A2. **Se a resposta mostrar que
   a maioria dos 40 não tinha perfil, P1 despenca e o problema vira geração, não
   qualificação — e o plano inteiro muda de camada.**
2. **"40% das propostas morrem sem cadência" (P2)** — estimativa, e a cadência atual **não
   foi informada**. Não afirmar ausência de follow-up na reunião. Destrava com B1 e B2.
3. **20 propostas/mês como teto do dono (P4)** — trato como teto porque é o realizado com
   todo o acúmulo, mas é premissa de comportamento, não medição. Perguntar direto.
4. **Taxas-alvo de 50% e 40% (meta reversa corrigida)** — são **projeções, não promessas
   contratuais**. Apresentar sempre como cenário.
5. **25 min de triagem por lead e 2 h por proposta (P5)** — estimativa minha, o dono não
   informou. Dois minutos de conversa confirmam ou derrubam.
6. **Ticket de R$ 20.000 e margem de 30% como mês típico (B5)** — **todo este documento se
   multiplica por esses dois números.** Se o mês foi atípico, tudo se desloca junto.
7. **Desconto médio desconhecido (B4)** — perda que existe, não foi medida, e pela tabela de
   sensibilidade pode ser maior que todas as perdas quantificadas.
8. **"Maioria vem de indicação" (R1)** — não convertido em percentual e **não deve ser**
   até A3 ser respondida.

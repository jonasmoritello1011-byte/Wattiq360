# 04 — Perfil de Cliente Ideal (ICP) · RP Soluções Inteligentes

> Base: `01-diagnostico.md` e `02-perdas-financeiras.md` (agentes 1 e 2) +
> `referencia/playbook-wattiq360.md` + `referencia/insights-top-players.md` + pesquisa
> pública sobre Sanclerlândia/GO e a microrregião de Anicuns (18/09/2026).
>
> **Aviso que abre o documento, porque governa tudo o que vem depois:** a RP não tem
> ticket médio, não tem mix de clientes, não tem funil medido e não respondeu a pergunta
> D9 ("qual o segmento predominante?") deixada pelo agente 1. Este ICP **não é derivado de
> dado de venda da RP** — porque esse dado não existe — e sim de três fontes credíveis, mas
> indiretas: (1) o que a empresa **declara publicamente** que vende, (2) a **economia real
> de Sanclerlândia e da microrregião de Anicuns**, pesquisada com fonte, e (3) a **pista
> aritmética** do agente 1 (6,25 fechamentos/vendedor/mês). Cada afirmação abaixo carrega
> sua própria confiança. Onde a confiança é baixa, digo.

---

## 1. ICP primário em 5 linhas

O cliente que a RP deveria perseguir como prioridade estratégica é o **produtor rural de
porte médio da microrregião de Anicuns** — pecuária leiteira, grãos (soja/milho) ou
integração lavoura-pecuária — com conta de energia puxada por bombeamento, resfriamento de
leite, secador de grãos ou pivô de irrigação. Ele paga por **projeto**, não por preço: o
crédito rural que financia o sistema (Pronaf, FCO Rural, Finame) normalmente **exige ART e
memorial técnico para liberar** — então vender a esse cliente sem entregar engenharia não é
possível, é pré-requisito de acesso. Ele decide rápido quando o vendedor fala a língua da
propriedade (kWh de bomba, não kWh de tomada), indica outro produtor com a mesma força que o
cliente urbano indica um vizinho, e sustenta ticket mais alto porque a carga é maior. É
também o cliente que a RP já atende publicamente (rural, on-grid e off-grid) e nunca tratou
como prioridade — provavelmente porque, sem instrumentação nenhuma, ninguém na empresa
conseguiria dizer isso hoje.

---

## 2. A conta do tamanho de mercado

**Aviso de método:** nenhum dos números abaixo é dado da RP. Todos vêm de fonte pública
citada, com premissa explícita. Onde a fonte não foi localizada, está escrito
**"não localizado"**, com onde buscar. Nenhuma estimativa entra em cálculo financeiro sem a
mesma marcação de confiança do agente 2.

### 2.1 A praça, em camadas

```
Camada 1 — Sanclerlândia (sede)
população: ~7.550 a 8.100 habitantes, a divergência é de arredondamento entre snippets
premissa: IBGE, Censo Demográfico 2022 (IBGE Cidades — cidades.ibge.gov.br/brasil/go/
          sanclerlandia/panorama)
confiança: média — número oficial, mas não consultei a tabela primária diretamente
          (acesso à página bloqueado nesta pesquisa; usei busca indexada)

Camada 2 — Microrregião de Anicuns (13 municípios, incluindo Sanclerlândia)
municípios: Adelândia, Americano do Brasil, Anicuns, Aurilândia, Avelinópolis, Buriti de
Goiás, Firminópolis, Mossâmedes, Nazário, Sanclerlândia, Santa Bárbara de Goiás, São Luís
de Montes Belos, Turvânia
população agregada: ~103.000 habitantes
premissa: fonte indexada sem ano-base confirmado (provavelmente Censo 2010 ou 2020,
          NÃO confirmado como 2022) — tratar como ORDEM DE GRANDEZA, não número fechado
confiança: baixa — ano-base incerto
maior cidade vizinha: São Luís de Montes Belos, ~33.850–34.150 hab (2022, IBGE)
```

**Por que a Camada 2 importa mais do que a Camada 1 para este relatório.** O agente 1 já
registrou que ~50 vendas/mês não saem de uma cidade de ~8 mil habitantes sozinhas (achado
R5, passado ao agente 3). Isso significa que **o ICP da RP não pode ser dimensionado só
pela sede** — a operação real, com franqueados possivelmente em outras cidades, provavelmente
já vende na microrregião inteira. Uso as duas camadas lado a lado porque não sei qual é o
raio real (lacuna do agente 1/3), e apresentar só a Camada 1 subestimaria o mercado por um
fator de ~13x.

### 2.2 Domicílios residenciais-alvo

```
Domicílios em Sanclerlândia: ~2.820
premissa: ~7.900 hab (ponto médio da Camada 1) ÷ 2,8 moradores/domicílio
          (média nacional, Censo 2022, IBGE — dado local de Sanclerlândia não localizado)
confiança: baixa — usa proxy nacional, não dado do município

Domicílios residenciais-alvo em Sanclerlândia: ~590
premissa: 2.820 domicílios × 30% em faixa de renda compatível com conta de energia alta
          o bastante para payback atraente (estimativa própria, SEM dado local de
          distribuição de renda — a página do IBGE Cidades com essa tabela não pôde ser
          acessada nesta pesquisa) × 70% de casa própria (média nacional aproximada,
          Censo 2022 — sem dado local)
confiança: baixa — duas estimativas empilhadas sobre um dado já estimado

Domicílios residenciais-alvo na microrregião de Anicuns (se o raio real da RP cobrir
toda a região): ~7.730
premissa: ~103.000 hab ÷ 2,8 (mesma premissa nacional) × mesmas duas taxas de 30% e 70%
confiança: baixíssima — soma o ano-base incerto da Camada 2 às duas estimativas acima;
           é o número mais frágil deste documento, e digo isso de propósito
```

**Não localizado, e onde buscar:** distribuição de renda por faixa de salário mínimo em
Sanclerlândia (tabela existe no IBGE Cidades / SIDRA, tabela 3261 — a página não pôde ser
acessada por bloqueio de rede nesta pesquisa); taxa de casa própria local; número oficial de
domicílios (SIDRA, tabela 579).

### 2.3 Empresas — ICP comercial

```
Empresas ativas em Sanclerlândia: ~1.360 a 1.400
premissa: agregadores privados de CNPJ (Econodata, Empresaqui, cnpj.chat) — NÃO é fonte
          oficial do CEMPRE/IBGE, que não foi localizado para este município
confiança: média — três fontes privadas convergem na faixa, mas nenhuma é o cadastro
           oficial
CNAEs mais citados nas fontes consultadas: serviços domésticos, obras de alvenaria
          (construção civil), comércio varejista
```

Dentro desse total, uma fração pequena tem porte e consumo compatíveis com solar comercial
(padaria, mercado, posto, pequena indústria, clínica). **Não localizado:** quantas, por CNAE
e por faixa de consumo. Filtrar por atividade de consumo intensivo (frigorífico, laticínio,
panificação, avicultura, agroindústria) é o atalho mais barato — mais barato que qualquer
censo — e está no roteiro de qualificação, seção 6.

### 2.4 Produtores rurais — ICP primário

```
Número de estabelecimentos rurais em Sanclerlândia e na microrregião: NÃO LOCALIZADO
onde buscar: Censo Agropecuário 2017 (IBGE, SIDRA — sidra.ibge.gov.br/pesquisa/
             censo-agropecuario), tabela de estabelecimentos por município; o Censo
             Agropecuário 2027 provavelmente ainda não publicou dados municipais
```

O que **é** afirmável com fonte, mesmo sem contagem de propriedades:

- **Agropecuária responde por 20,3% do PIB de Sanclerlândia** (PIB municipal ~R$ 217,6
  milhões, 2023 — IBGE Cidades), o que equivale a ~R$ 44,2 milhões gerados no município só
  em produção agropecuária. Para uma cidade de ~7.900 habitantes, é uma fatia grande — a
  administração pública é 20,8% e o setor de serviços 42,8%, então a agropecuária empata
  com o setor público em peso relativo, algo incomum para o tamanho da população.
- Goiás como estado é dominado por soja, milho e pecuária (62% da receita agropecuária
  estadual vem desses três). Há caso documentado especificamente em Sanclerlândia de
  produtor que dobrou o rebanho leiteiro (35 → 81 cabeças) com integração lavoura-pecuária
  e apoio da Emater — evidência qualitativa de que existe produtor rural tecnificado e
  capitalizado na região, não só agricultura de subsistência.
- A RP já declara publicamente atender **rural, on-grid e off-grid** — off-grid é, em
  quase todos os casos no Brasil, uma característica de propriedade rural sem rede, o que
  sugere que a empresa já tem alguma prática nesse segmento, mesmo sem tê-la priorizado.

```
Confiança do argumento "agro pesa desproporcionalmente para o tamanho do município": média
Confiança do número de produtores endereçáveis: NULA — não localizado, não estimado
```

**Pergunta mais barata que qualquer censo, para a próxima call:** *quantos clientes rurais a
RP já tem hoje, e quantos dos 8 vendedores atendem esse público?* Uma resposta do dono vale
mais que qualquer extrapolação deste documento.

### 2.5 A régua de sensibilidade sobre a pista aritmética do agente 1

O agente 1 registrou: 50 vendas/mês ÷ 8 vendedores = 6,25 fechamentos/vendedor/mês, alta
produtividade para venda solar complexa, com quatro hipóteses mutuamente exclusivas. Não
escolho uma no escuro — cada uma implica um ICP diferente, e registro as quatro:

| Hipótese | O que explicaria a produtividade | ICP implícito | Compatível com a pesquisa externa? |
|---|---|---|---|
| (a) Ticket baixo / kits pequenos / forte peso de off-grid rural | Sistemas pequenos e simples fecham rápido, com menos objeção | Residencial de entrada + off-grid rural básico (bomba, cerca elétrica) | **Sim** — off-grid é confirmado publicamente; região tem produtores de porte pequeno-médio |
| (b) As 50 incluem produtos que não são sistema FV | "Soluções Inteligentes" sugere portfólio mais largo (automação, outros serviços) | Indefinido até confirmar o portfólio real | Não verificável com pesquisa pública nesta rodada |
| (c) 50 é meta, não realizado | Produtividade real é menor, a hipótese perde força | Qualquer ICP, mas o funil real é mais lento | Não verificável sem dado interno |
| (d) A operação é de fato excepcional | RP converte muito acima da média do setor | ICP amplo, força está no processo (indicação), não no perfil do cliente | Possível, mas não comprovável sem funil medido |

**Leitura que sustenta a escolha do ICP primário deste documento:** a hipótese (a) é a única
das quatro **compatível com a pesquisa externa que pude fazer** — a RP confirma
publicamente que atende off-grid, e a economia regional mostra presença real de produtor
rural de porte médio. Isso não prova (a); mostra que ela é plausível e que o rural não é uma
aposta às cegas. As hipóteses (b) e (c) só se resolvem com a pergunta direta ao dono
(bloco A do agente 2, já registrada). **Recomendação ao agente 6:** tratar a produtividade
alta como sinal a confirmar, não como prova de que o ICP atual já é o correto — porque o
volume alto também é plenamente compatível com "muita venda pequena e barata", que é
exatamente o padrão de commoditização que o insight 9 avisa para testar.

---

## 3. O eixo que mais importa: preço por Wp ou projeto?

**A RP deveria perseguir o eixo de projeto no segmento rural/agro, e manter o eixo de preço
como motor de volume no residencial de entrada.** Não é meio-termo por indecisão — é dois
negócios propositalmente diferentes dentro da mesma marca, cada um servindo a um papel:

**O número que sustenta a escolha do rural como o negócio de projeto:**

1. **Crédito rural exige ART.** Pronaf, FCO Rural e Finame — as linhas típicas de
   financiamento de energia solar para propriedade rural no Brasil — normalmente exigem
   projeto técnico assinado para liberar o crédito. Isso significa que, para vender a esse
   cliente, **a RP é obrigada a entregar engenharia** — não é uma escolha de
   posicionamento, é a porta de entrada do segmento. Isso resolve dois problemas ao mesmo
   tempo: fecha o insight 1 (projeto eleva ticket 20–50%, referência de mercado, sem fonte
   declarada, confiança baixa — mas aqui o projeto não é upsell, é pré-requisito) e reduz o
   risco de commoditização do insight 9, porque o preço deixa de ser a única variável na
   mesa quando o banco exige documento técnico antes de aprovar.
2. **Agropecuária pesa 20,3% do PIB de um município de ~7.900 habitantes** (seção 2.4) —
   desproporcional para o tamanho da população, sinal de capital disponível fora do circuito
   urbano pequeno e caro de disputar.
3. **A rede de indicação rural é paralela e não competida.** A RP já vive de indicação
   (agente 1/2); produtor rural indica produtor rural através de cooperativa, Emater,
   revenda de insumos e sindicato rural — um circuito social diferente do circuito urbano.
   Isso ataca diretamente o risco R1 do agente 2 (concentração em um único canal de
   indicação): não é um segundo canal, é uma **segunda rede dentro do mesmo canal**, o que
   é mais barato de montar do que abrir mídia paga.

**O que ela precisa montar para servir esse cliente — nada disso depende de dado que falta:**

- **Um responsável técnico único assinando ART e memorial em padrão único**, para os 8
  canais de venda (interno e franquia). Resolve ao mesmo tempo o risco R3 do agente 2
  ("uma marca, 8 posicionamentos") e a exigência de crédito rural.
- **Parceria formal com Emater, cooperativas agropecuárias, revendas de máquinas/insumos e
  agentes de crédito rural** — o equivalente rural aos "6 canais de parceria" do playbook
  (arquiteto/construtora vira Emater/cooperativa). É o canal de menor CAC do mapa,
  adaptado ao público certo.
- **Dimensionamento técnico para carga rural** (bomba, resfriador de leite, secador de
  grãos, pivô) — treinamento de vendedores e franqueados, porque a conta de luz rural não
  se lê como a residencial.
- **Linha de financiamento rural mapeada com taxa real simulável** (Pronaf, FCO Rural,
  Finame) — cumprindo a regra ética do playbook de nunca prometer parcela sem simular com a
  taxa real.
- **Portfólio técnico documentado das obras rurais já entregues** — fotos, geração medida,
  cliente disposto a servir de referência. É o insight 8 (moat estrutural) aplicado ao
  segmento certo: 6 anos de obra entregue, hoje "na gaveta" segundo o agente 1/2.

**O residencial não sai do mapa — muda de papel.** Ele continua sendo o motor de volume e de
indicação de baixo CAC (o playbook é explícito: indicação é o canal de maior conversão e
menor custo do setor, sempre priorizar). Mas ele compra **preço**: o comprador residencial de
uma cidade pequena do interior compara Wp e parcela, não laudo técnico. Vender projeto
completo a esse cliente hoje seria elevar o ciclo de venda de um segmento que já funciona bem
por indicação, sem necessariamente elevar o ticket dele na mesma proporção. A recomendação
não é parar de vender residencial — é parar de tratá-lo como se fosse o negócio principal.

---

## 4. ICP primário detalhado — Produtor rural de porte médio

**Quem é.** Proprietário ou arrendatário de propriedade rural na microrregião de Anicuns
(Sanclerlândia e cidades vizinhas), com atividade de pecuária leiteira, mista ou grãos
(soja/milho), porte médio — não latifúndio, não subsistência. Consumo puxado por
bombeamento de água, resfriador de leite, secador de grãos, cerca elétrica ou, em
propriedades maiores, pivô de irrigação. Muitas vezes sem rede elétrica de qualidade
constante — justificando sistemas híbridos ou off-grid, que a RP já declara atender.

**Consumo (kWh/mês) e faixa de conta.** Não medido pela RP nem localizado por propriedade
específica nesta pesquisa. Faixa de referência setorial para propriedade rural tecnificada
de porte médio: consumo mensal costuma superar o residencial urbano por causa de motor de
bomba e resfriador — **referência de mercado, sem fonte declarada nesta coleta, não medida
na RP; confiança baixa.** A pergunta de qualificação (seção 6) deve capturar o valor real,
não presumir.

**Perfil de decisão.** Em geral, o próprio produtor decide, muitas vezes com participação do
cônjuge (quando a propriedade é bem familiar) e, quando há financiamento rural envolvido, do
contador ou do agente de crédito do banco/cooperativa. Decisão tende a ser mais rápida que a
urbana quando o vendedor demonstra domínio técnico da carga da propriedade — o produtor
rural desconfia de quem "não entende de fazenda".

**Por que é o ideal — com número e premissa.**

```
Ticket: sem dado da RP. Referência setorial: sistemas rurais dimensionados para bombeamento
        e resfriamento tendem a ser maiores que o kit residencial padrão por causa da carga
        — referência de mercado, SEM FONTE DECLARADA nesta coleta, confiança BAIXA, NÃO
        multiplicar pelo que a RP faturaria
Margem: sem dado. A exigência de projeto técnico para liberar crédito rural estrutura o
        ticket em torno de um serviço de engenharia, não de um kit — o que tende a proteger
        margem melhor que a venda por preço puro (mecanismo, não valor medido)
Ciclo: potencialmente mais rápido que o comercial urbano quando o vendedor fala a língua
       técnica certa (hipótese, sem dado de ciclo da RP — nenhum ciclo foi medido)
Esforço: menor concorrência direta nesse nicho — poucos integradores da região se
         especializam em carga rural, ao contrário do residencial urbano, onde qualquer
         integrador de Goiânia compete (hipótese qualitativa, sem contagem de concorrentes
         rurais — cruzar com o agente 5)
```

**Tamanho na praça.** Não localizado em número de propriedades (seção 2.4). O que sustenta a
prioridade é o peso do agro no PIB local (20,3%, R$ 44,2 milhões, IBGE Cidades 2023) e a
evidência qualitativa de produtor tecnificado na região — não uma contagem de unidades.

**Onde encontra.** Emater regional, cooperativas agropecuárias e sindicatos rurais da
microrregião de Anicuns, revendas de máquinas e insumos agrícolas, agentes de crédito rural
de bancos e cooperativas de crédito (Sicoob/Sicredi têm forte presença no interior de
Goiás — confirmar localmente). Amarrar ao mapeamento de canais do agente 3 quando ele
concluir o levantamento regional — este documento não refaz aquela análise.

**O que dispara a compra.** Reajuste tarifário (a Equatorial Goiás teve reajuste homologado
de até 18,74% para B1 em outubro/2025 — evento real e recente, argumento de "por que agora"
válido para toda a praça, não só para o rural), expansão de rebanho ou de área plantada
(mais carga = mais consumo), safra recém-vendida (capital disponível), renovação de
financiamento agro do ciclo produtivo.

**Quem decide junto.** Cônjuge (em propriedade familiar), contador rural, agente de crédito
do banco/cooperativa quando há financiamento — presumir mais de um influenciador, como o
playbook indica para venda complexa.

**Compra preço ou compra projeto.** Projeto — o crédito rural, quando presente, exige. E
quando a compra é à vista, o produtor rural tecnificado tende a valorizar garantia e
confiabilidade da carga crítica (não quer resfriador de leite parando) mais do que o menor
preço por Wp. O que ele quer ver na proposta: dimensionamento da carga real da propriedade
(bomba, resfriador, secador), simulação com a taxa real da linha de crédito rural (nunca
prometer parcela sem simular — regra ética do playbook), e prazo de instalação compatível
com a safra ou o ciclo de produção.

**Quem decide junto no lado técnico.** Emater (assistência técnica pública, presença
confirmada na região), cooperativa agropecuária, revenda de insumos/máquinas que já tem
relação de confiança com o produtor. É o equivalente rural do "arquiteto que abre a porta
mais barata" do insight 6 — a RP ainda não tem esse canal formalizado, segundo o Raio-X de
posicionamento do agente 1 (bloco 7: não informado).

**Objeção principal e resposta que funciona.** "Não confio em empresa de fora / não conheço
vocês" — comum em rede social fechada como o meio rural. Resposta: prova social geográfica
específica ("sistema parecido na fazenda de fulano, a X km daqui" — playbook, banco de
argumentos) e, sempre que possível, a indicação de um produtor que já é cliente, que é
exatamente o canal que a RP já sabe operar bem no meio urbano.

**Critérios eliminatórios.** Propriedade fora do raio real de atuação da RP (raio ainda não
definido — lacuna do agente 1/3); carga insuficiente para justificar sistema (propriedade
muito pequena, sem bomba/resfriador/pivô relevante); decisor ausente e sem previsão de
envolvimento; nenhuma fonte de pagamento identificada (nem à vista, nem linha de crédito
rural elegível).

---

## 5. ICPs secundários

### 5.1 Secundário — Residencial de renda média-alta, casa própria, Sanclerlândia e cidades vizinhas

**Quem é.** Família proprietária do imóvel, conta de energia alta o bastante para payback
atraente, na sede de Sanclerlândia ou nas cidades vizinhas da microrregião de Anicuns.

**Por que é o ideal.** É o motor de volume e de indicação de baixo CAC que sustenta a RP há
6 anos (agente 1/2: "vive principalmente de indicação"). Ticket, margem e ciclo: sem dado da
RP — não uso nenhum número. **É o segmento onde a produtividade de 6,25 fechamentos/vendedor
faz mais sentido** se a hipótese (a) da seção 2.5 for verdadeira (ticket baixo, kit
padronizado, venda rápida por indicação de vizinho).

**Tamanho na praça.** ~590 domicílios residenciais-alvo em Sanclerlândia; até ~7.730 se o
raio real cobrir toda a microrregião (seção 2.2 — confiança baixa a baixíssima, premissas
explícitas ali).

**Onde encontra.** Indicação de cliente satisfeito (canal já comprovado) — amarrar ao
levantamento de canais do agente 3.

**O que dispara a compra.** Reajuste tarifário recente (18,74% em B1, Equatorial Goiás,
out/2025 — o mesmo gatilho do ICP primário, mas com apelo residencial direto: "sua conta
subiu quase 19%").

**Quem decide junto.** Cônjuge — decisão de casal é a norma no residencial, não a exceção.

**Compra preço ou compra projeto.** Preço. O que ele quer ver na proposta: comparação clara
de parcela × conta atual, prova social de vizinho ("um sistema parecido a duas quadras
daqui" — banco de argumentos do playbook), e prazo de instalação.

**Quem decide junto no lado técnico.** Construtora ou pedreiro/empreiteiro local, quando a
instalação é feita durante reforma ou construção — canal do playbook (lojas de material de
construção, construtoras) ainda não formalizado, segundo o Raio-X de posicionamento.

**Objeção principal e resposta.** "Vou pegar outros orçamentos" — resposta do playbook:
"quer que eu te mostre os pontos que vale comparar?", ajudando a comparar corretamente em
vez de brigar só por preço.

**Critérios eliminatórios.** Imóvel alugado sem autorização do proprietário; telhado
inadequado sem alternativa de solo; conta de energia baixa demais para justificar o
investimento; decisor (cônjuge) recusando participar da conversa.

### 5.2 Secundário — Pequeno comércio e agroindústria local

**Quem é.** Estabelecimento comercial ou pequena agroindústria de Sanclerlândia e região —
mercado, padaria, posto, laticínio, frigorífico de pequeno porte, avicultura — com consumo
diurno compatível com geração solar.

**Por que é o ideal.** Consumo concentrado no horário de geração solar (vantagem técnica
clássica do comercial sobre o residencial) e decisão profissionalizada (dono + contador),
o que costuma acelerar a análise financeira. Ticket, margem e ciclo: sem dado da RP.

**Tamanho na praça.** Fração não quantificada dos ~1.360–1.400 CNPJs ativos em Sanclerlândia
(seção 2.3) — filtrar por CNAE de consumo intensivo é o próximo passo, não uma contagem que
este documento pode fazer.

**Onde encontra.** Associação comercial local, contadores da região (canal do playbook —
"já têm confiança para falar de investimento"), amarrar ao mapeamento do agente 3.

**O que dispara a compra.** Reajuste tarifário; abertura de nova unidade; conta de energia
que virou linha relevante do orçamento do negócio.

**Quem decide junto.** Contador — no comercial pequeno, o contador costuma validar o
investimento antes do dono assinar.

**Compra preço ou compra projeto.** Misto, pendendo para preço no comércio pequeno e para
projeto na agroindústria (laticínio, frigorífico) por causa da carga elevada e da eventual
exigência de financiamento com garantia técnica.

**Quem decide junto no lado técnico.** Nenhum canal técnico formal identificado; oportunidade
não explorada.

**Objeção principal e resposta.** "Não é o momento" — resposta do playbook: "é timing ou tem
outro ponto pesando?", isolando a causa real antes de insistir.

**Critérios eliminatórios.** Consumo baixo demais para o investimento se pagar dentro de um
prazo razoável; imóvel alugado sem cláusula que permita a instalação; ausência do
decisor (dono) e do contador na conversa quando o valor justifica múltiplos influenciadores.

---

## 6. Anti-ICP

**Quem a RP deveria recusar ou despriorizar, e por quê:**

- **Residencial de conta baixa (kit mínimo, payback longo, fora do raio real de atuação).**
  Não há dado de taxa de fechamento por faixa de conta na RP (não medido) para provar que
  esse segmento "consome 3 visitas e fecha 4%" com número próprio — **não invento esse
  número**. O que sustenta a recomendação é lógica de custo de oportunidade: com 6,25
  fechamentos/vendedor/mês já ocupando a agenda de 8 pessoas (agente 1), tempo gasto num
  ticket pequeno é tempo que não vai para o rural, onde o ticket referência é maior
  (seção 4). **Confirmar com o dono, na call, se já existe uma faixa de conta que
  historicamente não fecha — essa resposta substitui esta estimativa.**
- **Lead fora do raio real de atuação da RP.** O raio não está definido (lacuna do agente
  1, passada ao agente 3) — até ele ser confirmado, qualquer lead fora da microrregião de
  Anicuns deveria ser tratado como exceção, não como padrão, porque indicação não atravessa
  distância sozinha (achado do agente 2, seção 10.2).
- **Propriedade rural sem carga relevante (sem bomba, sem resfriador, sem pivô, consumo
  baixo).** O ICP primário depende de carga que justifique sistema de porte médio; sem ela,
  a venda vira kit pequeno e perde a vantagem de ticket que sustenta a prioridade do
  segmento.
- **Lead sem decisor identificável e sem previsão de envolvê-lo.** Válido para os três ICPs
  — venda complexa não fecha sem decisor, e insistir sem ele é o erro mais comum do
  playbook aplicado à qualificação.
- **Franqueado ou interno disputando o mesmo lead sem regra de distribuição (achado P9 do
  agente 2).** Não é um tipo de cliente a recusar, é uma prática a eliminar: cada colisão
  entre canais custa reputação na rede de indicação, que é o ativo mais caro que a RP tem.

---

## 7. Roteiro de qualificação para o agente SDR

Os 8 critérios mínimos do playbook, traduzidos para os três ICPs da RP. **Regra de conversa,
sem exceção:** uma pergunta por mensagem, explicar por que o dado é necessário, parar
assim que um critério eliminatório reprovar, registrar tudo no CRM (que hoje não existe —
achado do agente 1/2, e é a primeira coisa a montar).

**Antes da primeira pergunta, a IA identifica o segmento** com uma única pergunta de
triagem, porque o resto do roteiro muda de vocabulário conforme a resposta:

> *"Pra te ajudar melhor: o sistema é para a sua casa, para um comércio/empresa ou para uma
> propriedade rural?"*
> Por que perguntar: define o vocabulário e os critérios seguintes — carga de bomba e
> resfriador não têm equivalente na conta residencial, e a IA precisa saber qual roteiro
> seguir.

| # | Critério | Pergunta exata | Por que o dado é necessário (o que a IA explica) | O que reprova o lead ali | O que **não** perguntar |
|---|---|---|---|---|---|
| 1 | **Consumo** | *"Pode me mandar uma foto da sua última conta de energia? É o jeito mais rápido de eu calcular o tamanho certo do sistema, sem chute."* (Rural: complementar com *"a propriedade tem bomba d'água, resfriador de leite, secador de grãos ou pivô de irrigação?"*) | Define o dimensionamento e se o ticket justifica visita técnica | Consumo baixo demais para justificar investimento (limiar a definir pelo dono, ainda não existe na RP) | Não perguntar o valor da conta em R$ se a foto já veio — está nela |
| 2 | **Titularidade** | *"O imóvel é seu, ou você aluga?"* (Rural: *"a propriedade é sua, arrendada ou de outro familiar?"*) | Sistema em imóvel de terceiro exige autorização formal, e financiamento rural exige documentação da posse | Imóvel alugado sem autorização do proprietário; propriedade rural sem documentação de posse clara | — |
| 3 | **Local** | *"Em que cidade fica o imóvel/propriedade?"* | Define se está dentro do raio real de atuação da RP (raio ainda não confirmado internamente — até lá, todo lead fora de Sanclerlândia e cidades vizinhas da microrregião de Anicuns é sinalizado como atenção, não descartado de imediato) | Fora do raio confirmado, quando esse raio existir | — |
| 4 | **Estrutura** | *"Pode me mandar uma foto do telhado (ou da área onde pensa em instalar)?"* | Define viabilidade técnica antes de agendar visita | Telhado ou área sem condição estrutural, sem alternativa viável | Não perguntar o tipo de telhado por texto se a foto responde |
| 5 | **Motivação** | *"O que te fez pensar em energia solar agora?"* | Abre o gatilho de compra (reajuste de tarifa, expansão, conta que estourou) e alimenta o vendedor com contexto real para a reunião | Curiosidade sem intenção concreta de avançar em prazo razoável | — |
| 6 | **Decisor** | *"Além de você, mais alguém participa dessa decisão — cônjuge, sócio, contador?"* (Rural: incluir *"o financiamento, se houver, passa por algum agente de crédito ou cooperativa?"*) | Venda complexa tem mais de um influenciador quase sempre; o vendedor precisa saber quem falta na sala | Decisor ausente e sem previsão de envolvimento | — |
| 7 | **Prazo** | *"Você pensa em instalar em quanto tempo — semanas, meses, ainda sem data?"* | Define prioridade de atendimento e cadência de follow-up | Prazo indefinido sem nenhum gatilho declarado (tratar como C, não descartar) | — |
| 8 | **Pagamento** | *"Você pensa em pagar à vista ou financiado?"* (Rural: *"pensa em usar alguma linha de crédito rural, tipo Pronaf ou FCO?"*) | Define se a proposta precisa incluir simulação de financiamento com taxa real — nunca prometer parcela sem simular (regra ética do playbook) | Nenhuma fonte de pagamento identificada, nem à vista nem financiamento elegível | Não perguntar a taxa de juros que o cliente "acha" que vai conseguir — isso é trabalho do vendedor na simulação |

**Nota sobre o critério eliminatório de consumo/ticket mínimo.** A RP não tem, hoje, um
limiar definido de conta de energia abaixo do qual não vale a pena atender (não medido). O
roteiro acima assume que esse limiar existe e será definido pelo dono na configuração do
agente — sem ele, a IA não deve reprovar por consumo, só sinalizar como C (seção 8).

---

## 8. Cartão de oportunidade

Modelo preenchido, com os campos do playbook, para o ICP primário (rural) — o vendedor
recebe este cartão e **não repete** as 8 perguntas já feitas pela IA.

```
CARTÃO DE OPORTUNIDADE

Cliente: [nome]
Segmento: Rural — pecuária leiteira / grãos / misto  [preenchido pela pergunta de triagem]
Consumo (R$/mês): [valor extraído da conta] | Carga declarada: [bomba / resfriador /
                  secador / pivô]
Local: [propriedade + cidade — dentro do raio confirmado? sim/não]
Conta (recebida?): [sim/não — foto anexada]
Estrutura (foto?): [sim/não — telhado ou área de solo]
Decisor: [produtor + cônjuge/sócio + agente de crédito, se financiamento]
Prazo: [semanas / meses / sem data]
Pagamento: [à vista / financiamento — linha declarada, ex.: Pronaf/FCO/à confirmar]
Motivação: [gatilho declarado — reajuste, expansão de rebanho/área, safra recém-vendida]
Temperatura: [A/B/C — critério abaixo]
```

### Critério de temperatura A/B/C, definido para a RP

**A — vai para o vendedor hoje.**
Todos os 8 critérios preenchidos **e** pelo menos dois destes três sinais fortes: (1) lead
veio por indicação de cliente já instalado (canal comprovado da RP); (2) consumo/carga
compatível com sistema de porte médio ou maior (não kit mínimo); (3) decisor confirmado na
conversa, incluindo agente de crédito quando há financiamento rural. **Por que esses dois
sinais e não outro:** são os dois fatores que, segundo a seção 3 deste documento, mais
correlacionam com o ICP primário — indicação (canal já validado) e carga relevante (ticket
que sustenta a prioridade do rural).

**B — vai para o vendedor com nota, sem urgência.**
6 a 7 dos 8 critérios preenchidos, com no máximo um sinal forte de A. Inclui o residencial
de renda média sem gatilho declarado forte, e o comercial pequeno sem contador confirmado
na conversa.

**C — nutrição, não descarta.**
Menos de 6 critérios preenchidos, ou consumo/carga abaixo do limiar (quando o dono definir
um), ou prazo "sem data" sem nenhum gatilho declarado. Entra na cadência de nutrição do
playbook (D+15, longo prazo) em vez de ir para o vendedor — não é lixo, é lead cedo demais.

**Critério eliminatório, em qualquer temperatura:** imóvel/propriedade fora do raio
confirmado de atuação, ou decisor que recusa explicitamente participar da conversa. Esses
dois páram a qualificação imediatamente, por regra de conversa do playbook.

---

## 9. Fontes

- [IBGE Cidades — Sanclerlândia, Panorama](https://cidades.ibge.gov.br/brasil/go/sanclerlandia/panorama) — população, PIB e composição setorial (acesso indireto via busca indexada; página bloqueada para leitura direta nesta pesquisa)
- [IBGE Cidades — São Luís de Montes Belos, Panorama](https://cidades.ibge.gov.br/municipio/522010) — população da maior cidade vizinha
- [Microregion of Anicuns — Wikipedia](https://en.wikipedia.org/wiki/Microregion_of_Anicuns) — composição dos 13 municípios da microrregião
- [Bandeiras Tarifárias — Equatorial Energia Goiás](https://go.equatorialenergia.com.br/bandeiras-tarifarias/) e [Valor de tarifas e serviços — Equatorial Energia Goiás](https://go.equatorialenergia.com.br/valor-de-tarifas-e-servicos/) — tarifa B1 e sistema de bandeiras
- [Tarifa de energia da Equatorial Goiás sobe até 19% — O Hoje](https://ohoje.com/2025/10/22/aumento-energia-equatorial-goias-aneel/) e [ANEEL — Novas tarifas da Equatorial Goiás são aprovadas](https://www.gov.br/aneel/pt-br/assuntos/noticias/2025/novas-tarifas-da-equatorial-goias-sao-aprovadas-pela-aneel) — reajuste de outubro/2025, gatilho de compra
- [Agrolink — Com apoio da Emater Goiás, produtor dobra rebanho em Sanclerlândia](https://www.agrolink.com.br/noticias/com-apoio-da-emater-goias--produtor-transforma-propriedade-em-renda-e-dobra-rebanho-em-sanclerlandia_511836.html) — evidência qualitativa de produtor tecnificado na região
- [Brasil 61 — Goiás: produção agropecuária tem soja, bovinos e milho como destaques](https://brasil61.com/n/goias-producao-agropecuaria-tem-como-principais-destaques-soja-bovinos-e-milho-bras238756) — perfil agropecuário estadual
- [Econodata — Lista de Empresas em Sanclerlândia](https://www.econodata.com.br/empresas/go-sanclerlandia) e [Empresaqui — Listas de Empresas em Sanclerlandia](https://www.empresaqui.com.br/listas-de-empresas/GO/SANCLERLANDIA) — contagem de empresas ativas e CNAEs dominantes (fonte privada, não oficial)
- [RP Soluções Inteligentes — site institucional](https://rpsolucoesinteligentes.com.br/) e [Facebook RP Soluções Inteligentes](https://www.facebook.com/rpsolucoesinteligentes/) — confirmação pública de segmentos atendidos (residencial, comercial, rural, on-grid, off-grid); conteúdo detalhado do site **não pôde ser lido nesta pesquisa** (bloqueio de rede persistente, mesma limitação registrada pelo agente 1)
- [Instagram — @rpsolucoesinteligentes](https://www.instagram.com/rpsolucoesinteligentes/) — perfil confirmado existir; conteúdo não acessível via busca ou fetch nesta rodada
- Censo Agropecuário 2017 (IBGE/SIDRA) — **não localizado o dado municipal de Sanclerlândia nesta pesquisa**; indicado como fonte a consultar diretamente em `sidra.ibge.gov.br/pesquisa/censo-agropecuario`
- Tabela 3261 (SIDRA/IBGE) — distribuição de renda por faixa de salário mínimo — **não localizada nesta pesquisa**, página bloqueada para acesso direto

**Limitação de pesquisa registrada, como no agente 1:** o acesso direto (WebFetch) a
`rpsolucoesinteligentes.com.br`, `cidades.ibge.gov.br` e `meumunicipio.org.br` foi bloqueado
pelo proxy de rede em todas as tentativas desta sessão. Toda a informação dessas fontes veio
de resultados de busca indexados (WebSearch), que são menos confiáveis que o documento
primário. Onde isso importa, marquei a confiança como média em vez de alta.

---

## 10. Passagem de bastão → plano-ideal

```
ICP primário em 1 frase: produtor rural de porte médio (pecuária leiteira/mista ou grãos)
  na microrregião de Anicuns, com carga elevada por bombeamento/resfriamento/secagem, que
  compra PROJETO porque o crédito rural exige ART — não escolha de posicionamento, requisito
  de acesso ao segmento.

Tamanho de mercado (com premissa): número de propriedades rurais NÃO LOCALIZADO (Censo
  Agropecuário 2017/SIDRA não acessado nesta pesquisa). O que sustenta a prioridade:
  agropecuária = 20,3% do PIB de Sanclerlândia (~R$ 44,2 milhões, IBGE Cidades 2023),
  desproporcional para uma cidade de ~7.900 hab. Residencial-alvo: ~590 domicílios em
  Sanclerlândia a ~7.730 se o raio cobrir a microrregião de Anicuns (~103 mil hab, ano-base
  incerto) — confiança baixa a baixíssima, premissas na seção 2.2. Comercial: fração não
  quantificada de ~1.360–1.400 empresas ativas (fonte privada, confiança média).

Ticket e ciclo esperados no ICP × média atual: NÃO COMPARÁVEL — a RP não tem ticket médio
  nem ciclo medido (agente 1/2, confirmado). Qualquer ticket citado neste documento para o
  segmento rural é referência setorial, sem fonte declarada, confiança baixa, e NÃO deve
  entrar em nenhum cálculo financeiro sem o dado real da RP.

Critérios eliminatórios para configurar o agente SDR: imóvel/propriedade fora do raio real
  de atuação (raio ainda não confirmado — lacuna do agente 1/3); decisor ausente sem
  previsão de envolvimento; imóvel alugado sem autorização; estrutura/carga inviável; nenhuma
  fonte de pagamento identificada. Falta o dono definir um limiar mínimo de consumo/conta —
  hoje esse limiar não existe na RP.

Regra de temperatura A/B/C definida: A = 8 critérios completos + pelo menos 2 de 3 sinais
  fortes (indicação de cliente instalado, carga/ticket de porte médio ou maior, decisor
  confirmado incluindo agente de crédito quando há financiamento rural). B = 6–7 critérios,
  no máximo 1 sinal forte. C = menos de 6 critérios ou consumo abaixo do limiar (quando
  definido) ou prazo sem gatilho — vai para nutrição, não é descarte.

Quem descartar e por quê (impacto no tempo do vendedor): residencial de conta baixa fora do
  raio de atuação; propriedade rural sem carga relevante; qualquer lead sem decisor
  identificável e sem previsão de envolvê-lo. Nenhum desses tem taxa de fechamento própria
  medida na RP — a recomendação é lógica de custo de oportunidade sobre uma agenda de 8
  vendedores já ocupada (6,25 fechamentos/vendedor/mês, agente 1), não uma perda comprovada.
  Confirmar com o dono se já existe, na prática, uma faixa que historicamente não fecha —
  essa resposta substitui esta estimativa.

Alerta que carrego de todo o documento: este ICP foi construído com dado econômico regional
  e uma pista aritmética, não com dado de venda da RP — porque esse dado não existe. Ele é o
  melhor ICP defensável com o que está disponível hoje, não uma certeza. A pergunta mais
  barata para confirmá-lo ("quantos clientes rurais a RP já tem, e quem são?") ainda não foi
  feita ao dono.
```

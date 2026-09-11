# Formulário padrão de coleta — Diagnóstico Wattiq 360

`diagnostico-360-formulario.html` é o instrumento **padrão** de primeiro contato.
Mande o link para o cliente preencher antes da call, ou preencha junto com ele ao
telefone — tem barra de progresso, botão de copiar as respostas em texto e botão de
salvar em PDF. Sem servidor, sem dependência: abre e funciona em qualquer navegador.

**Ele substitui o `diagnosticos/_modelo/00-briefing.md` como ponto de partida.** O
briefing em markdown continua existindo para quando não há como mandar um link (call
não agendada, cliente sem paciência para formulário) — mas o padrão agora é este.

## As 10 perguntas do formulário → os dois eixos do diagnóstico

O formulário comprime os dois Raio-X (`playbook-wattiq360.md` e
`insights-top-players.md`) em 10 perguntas objetivas. Nem tudo cabe — o que fica de
fora vira a lista de perguntas da próxima call, do jeito que o agente 1 já faz.

| # | Pergunta do formulário | Eixo | Onde entra |
|---|---|---|---|
| 1 | O funil em quatro números (leads, qualificados, propostas, contratos) | Conversão | Blocos 1, 4, 6, 7 do Raio-X. **Atenção:** o formulário pula contato efetivo e diagnóstico/visita — o funil de 4 etapas aqui é uma versão comprimida do funil de 6 etapas do playbook. Se o cliente também souber separar essas duas, pergunte; se não, registre como lacuna igual ao caso LEOSOL |
| 2 | Ticket médio e meta de faturamento | Conversão | Bloco 8 + a meta declarada, que alimenta a meta reversa do agente 2 |
| 3 | Investimento em mídia e canais | Conversão | Bloco de marketing (playbook) — investimento e canais ativos |
| 4 | Origem dos leads (anúncio × indicação/orgânico) | Conversão | Regra dos 50% — dá para calcular a concentração de canal direto daqui, sem precisar da resposta vaga "a maioria vem de indicação" |
| 5 | Tempo de resposta | Conversão | Pergunta de controle 1 do playbook |
| 6 | Os três motivos de perda | Conversão | Bloco 9 do Raio-X — aqui o formulário já força três motivos, o que evita o problema do caso LEOSOL original (só "preço/concorrência" veio) |
| 7 | Formato da proposta + existe follow-up | Conversão | Perguntas de controle 4 e 5 |
| 8 | Raio de atuação + segmento predominante | Conversão / ICP | Fecha uma lacuna que se repetiu em toda rodada anterior (raio de atendimento nunca vinha). O segmento predominante (residencial/comercial/rural/industrial/misto) já entrega o corte que o agente 4 monta manualmente entre comprador de preço e comprador de projeto |
| 9 | Base instalada + ação de indicação | Posicionamento | Blocos 6 (O&M) e 9 (histórico documentado) do raio-x de posicionamento |
| 10 | Laudo/ART/memorial + contrato de manutenção | Posicionamento | Blocos 1, 2 e 6 — **é a pergunta que decide o Ramo A × Ramo B do agente 6** (engenharia guardada na gaveta × capacidade a construir). No caso LEOSOL, isso só foi respondido numa call separada; agora entra no primeiro contato |

## O que o formulário não cobre — continua sendo pergunta de call

- Contato efetivo e diagnóstico/visita como etapas separadas (funil de 6, não de 4)
- Parcerias com arquitetos e construtoras (insight 6)
- Contra quem se perde e o que o concorrente entregava (fecha o bloco 10 do raio-x de
  posicionamento)
- A pergunta que fecha o eixo de posicionamento: *"se o concorrente igualar seu preço
  amanhã, o que sobra?"*
- Desconto médio concedido

O agente 1 recebe as respostas do formulário como **dado do cliente, confiança alta**
nos campos preenchidos, e trata os campos vazios como lacuna declarada — nunca como
zero. A lista de perguntas da próxima call que ele já produz cobre exatamente os
pontos acima.

## Uso

1. Envie `diagnostico-360-formulario.html` para o cliente (arquivo por e-mail/WhatsApp,
   ou publique como Artifact se quiser um link).
2. Peça para exportar em PDF ou copiar as respostas — o botão "Copiar respostas" já
   formata como `Rótulo: valor`, uma linha por campo preenchido.
3. Cole o texto exportado direto no prompt do agente `diagnostico`, junto com qualquer
   coisa que o formulário não cobriu.

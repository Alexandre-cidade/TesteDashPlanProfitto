# Preço: planejamento financeiro por assinatura

Fontes: painel de 50 compradores simulados (`panel/results.md`, `pricing-curve.md`), concorrentes (`competitors.md`). **A margem não foi calculada**: falta `founder/numbers.json`, que é feito pelo `/founder-cfo`. Respostas simuladas servem para escolher o que testar, não provam nada.

## Antes de tudo: o painel deu 0 de 50, e parte disso é culpa do pitch

Nenhum dos 50 compradou o Assistido a R$ 350. Os motivos foram confiança (24), hábito (14) e preço (12). Mas o pitch dizia, por honestidade, que "a empresa não informou se há fidelidade ou como funciona o cancelamento", e **49 de 50** citaram exatamente isso. Logo, o 0% mede uma oferta incompleta, não o serviço. Mesmo assim, três sinais se sustentam independentemente do pitch:

1. **R$ 350 está acima da faixa aceitável** para a média: PME de R$ 300, e metade disse que R$ 350 ou menos já é "caro demais".
2. **32 de 50 pediram para começar por um diagnóstico avulso** ou um primeiro mês de teste antes de assinar.
3. **13 de 50 pediram, por escrito, "sem comissão"** e 10 pediram planejador CFP. Querem saber se o planejador ganha vendendo produto.

## 1. A faixa do painel (Van Westendorp, Assistido)

| ponto | R$/mês |
|---|---:|
| Barato demais (PMC) | 81 |
| Menor resistência (OPP) | 103 |
| Indiferença (IPP) | 179 |
| Caro demais (PME) | 300 |

**Faixa aceitável: R$ 81 a R$ 300.** O Assistido a R$ 350 fica acima dela.

**Por segmento** (medianas: barganha / começa a ficar caro / caro demais):

| segmento | n | barganha | caro | caro demais |
|---|---:|---:|---:|---:|
| Profissional liberal de alta renda | 10 | 200 | **450** | 700 |
| Família de classe média com filhos | 17 | 120 | 250 | 400 |
| Pré-aposentado | 5 (ralo) | 120 | 220 | 350 |
| Jovem profissional sem investimentos | 18 | 100 | 200 | 300 |

**R$ 350 só cabe no profissional liberal de alta renda.** Isso bate com o conselho, que pediu um nicho, e é o segmento onde a conta tem mais chance de fechar.

## 2. Contra os concorrentes

- Ável Estratégico: R$ 299,90; Ável Essencial: R$ 149,90 (levantamento do fundador, não verificado). Ambos em Porto Alegre e com humano.
- Consultor CVM com fee fixo: exemplo de ~R$ 500/mês, incluindo carteira e análise tributária.
- Apps: R$ 13 a R$ 69/mês.

O PME do painel (R$ 300) é quase igual ao preço da Ável Estratégico. O mercado local e os compradores simulados apontam para o mesmo teto no público geral.

## 3. A recomendação

**Não é baixar o preço para todo mundo. É escolher para quem o preço é R$ 350 e mudar a porta de entrada.**

| degrau | para quem | preço | por que subir |
|---|---|---|---|
| **Diagnóstico Financeiro** (avulso, sem assinatura) | todos | **testar R$ 490 vs R$ 790**, abatido 100% se assinar em 30 dias | É o que 32/50 pediram: ver valor antes de assinar |
| **Assistido** | famílias de classe média | **R$ 297/mês**, sem fidelidade | Dentro da faixa (≤ PME de 300), empata com a Ável e se diferencia por ser sem fidelidade e sem comissão |
| **Assistido Profissional** (Assistido + tributação, previdência e PJ/PF) | profissionais liberais de alta renda (**nicho sugerido**) | **R$ 390/mês** (teste contra R$ 450) | Abaixo do "caro" desse segmento (R$ 450); entrega o que o banco não entrega |
| Personalizado | alta complexidade | R$ 750+ (manter) | Não testado no painel |
| Private/Family | patrimônio e sucessão | sob consulta, R$ 1.500+ | Não testado no painel |

**Digital (R$ 100):** o painel não testou esse plano. Pelos concorrentes (Ável Essencial com humano a R$ 149,90, apps até R$ 69), ele só se sustenta com algum toque humano, como uma sessão de onboarding e check-in trimestral, ou então indo para ~R$ 49–69 como app puro. Decidir em `/founder-offer`.

**Sobre margem:** nada disso foi checado contra o custo da hora do planejador, a capacidade por planejador ou o custo do Dashplan por cliente. Antes de publicar qualquer preço, rode `/founder-cfo` com R$ 297, R$ 350 e R$ 390. Se o Assistido a R$ 297 não der lucro, a resposta é **subir de nicho** (Assistido Profissional), não baixar o preço.

## 4. Oferta de abertura (sem treinar desconto)

**"Turma fundadora": as 30 primeiras famílias** (escassez real: capacidade do time)
- Diagnóstico abatido integralmente da assinatura
- Preço travado por 12 meses
- **Sem fidelidade, cancelamento online em um clique, por escrito** na página de venda (a objeção nº 1, em 49 de 50)
- Termina numa data fixa (por exemplo, 31/01/2027) ou quando fechar a 30ª vaga, o que vier primeiro

Sem "de R$ X por R$ Y": nenhum preço "cheio" foi cobrado ainda, então não há âncora honesta.

## 5. O que testar com pessoas reais

1. **Duas landing pages** com o mesmo texto, incluindo a política de cancelamento e "sem comissão", e preços diferentes:
   - Assistido a R$ 297 vs R$ 350, para famílias
   - Assistido Profissional a R$ 390 vs R$ 450, para profissionais liberais (anúncio segmentado ou indicação)
2. **Pré-venda do Diagnóstico** a R$ 490 vs R$ 790. Medir a conversão de diagnóstico em assinatura em 30 dias.
3. Meta para decidir: ao menos 10 diagnósticos pagos por variação antes de fixar o preço.

## 6. Objeções de preço, nas palavras do painel (para o marketing)

1. "R$ 350 por mês, todo mês, é mais de R$ 4 mil por ano para alguém me dizer o que eu já ouço de graça no YouTube. E ainda sem saber se tem fidelidade, eu não assino." (P005)
2. "Meu gerente do banco já me orienta de graça. Pagar R$ 350 todo mês para uma empresa nova que nem diz como cancelar não faz sentido para mim agora." (P001)
3. "Eu tô com cartão e cheque especial rodando, R$ 350 todo mês é praticamente uma parcela de dívida a mais. Pagar isso pra alguém me dizer pra gastar menos não fecha a conta agora." (P009)

São falas de compradores simulados, não depoimentos de clientes.

## Próximos passos

- `/founder-cfo`: margem a R$ 297, R$ 350 e R$ 390. Precisa do custo do Dashplan por cliente, do custo-hora ou salário do planejador e de quantos clientes ele atende.
- `/founder-offer`: política de cancelamento, "sem comissão", diagnóstico como porta de entrada e o Digital com toque humano. Depois, re-testar com `/founder-consumer --quick` usando o pitch corrigido.

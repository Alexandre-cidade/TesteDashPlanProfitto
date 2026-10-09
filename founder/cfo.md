# Nota do CFO (v3: com PMT da plataforma e CEO)

> **Entradas do fundador:** Dashplan a R$ 20 por cliente, planejador com 20% da receita, **PMT da plataforma de R$ 5.000/mês**, **CEO com adiantamento de lucros de R$ 10.000/mês** e R$ 100 mil de caixa.
>
> **Estimativas:** imposto (~11%), cobrança (~3,5%), contador (R$ 600), ferramentas (R$ 300), marketing (R$ 3.000), investimento inicial (R$ 15 mil) e a rampa de clientes. Ver `cfo-sources.md`.
>
> **Dúvida:** os R$ 5 mil de PMT somam-se aos R$ 20 por cliente ou substituem esse valor? Aqui considerei os dois. Sem os R$ 20 por cliente, o break-even cai de 109 para 98 clientes.
>
> A ferramenta escreve "$", mas tudo é **R$**; "a day" deve ser lido como "clientes ativos no mês". Isto não é aconselhamento financeiro, contábil ou jurídico. Um contador precisa validar o tratamento do adiantamento de lucros: só existe lucro para distribuir se houver lucro apurado, e adiantar sem lucro pode ter efeito fiscal.

## A margem

- **Por cliente:** cada cliente-mês a R$ 297 continua deixando **R$ 174,53 (59%)**.
- **Custos fixos:** saltaram para **R$ 18.900/mês** (plataforma R$ 5 mil + CEO R$ 10 mil + marketing R$ 3 mil + contador e ferramentas).
- **Break-even: 109 clientes ativos** a R$ 297, ou 81 clientes a R$ 390. Com 80 clientes, a margem é **−21%**.

## Caixa: os R$ 100 mil não chegam com a rampa atual

Com a rampa de 3 → 55 clientes, o ano 1 fecha em **−R$ 168.507**. O caixa necessário é de **R$ 183.507**, e o acumulado passa de **−R$ 100 mil no mês 5** (−R$ 100.075). **Sem mudança, o dinheiro acaba por volta do mês 5.**

| cenário (rodado na ferramenta) | break-even | resultado ano 1 | caixa necessário |
|---|---:|---:|---:|
| Base: R$ 297, rampa 3 → 55 | 109 | −R$ 168.507 | **R$ 183.507** |
| R$ 390, mesma rampa | 81 | −R$ 148.160 | R$ 163.160 |
| R$ 350, rampa 5 → 95 | 91 | −R$ 102.715 | R$ 118.694 |
| R$ 297, **rampa rápida 10 → 135** | 109 | −R$ 71.294 | **R$ 95.043** |
| R$ 390, rampa rápida 10 → 135 | 81 | −R$ 17.014 | R$ 73.069 |
| **CEO a R$ 5 mil** até o break-even, rampa base | 80 | −R$ 108.507 | R$ 123.507 |
| **CEO a R$ 5 mil + rampa rápida** | 80 | −R$ 11.294 | **R$ 57.385** |

A rampa rápida, com 10 clientes no mês 1 e 135 no mês 12, significa **~10 clientes novos por mês sem perder ninguém**. Isso é 2,5 vezes a rampa base e ainda não foi validado por nenhuma conversão real.

## A linha que mais pesa

**Fixos contra a velocidade de clientes.** Com R$ 18.900 de fixos, cada mês de atraso custa ~R$ 15–18 mil no início. Os R$ 15 mil de plataforma e CEO são 79% dos fixos.

## Três formas de caber nos R$ 100 mil (rodadas na ferramenta)

1. **Adiantamento do CEO atrelado a marcos:** R$ 5 mil até o break-even e R$ 10 mil depois. Na rampa base, o caixa necessário cai de **R$ 183.507 para R$ 123.507**. Com rampa rápida, cai para **R$ 57.385**.
2. **Rampa rápida via rede dos sócios e turma fundadora:** com ~10 clientes novos por mês, o caixa necessário cai para **R$ 95.043**, mesmo a R$ 297 e com CEO a R$ 10 mil.
3. **Mix de preço mais alto** (Assistido Profissional a R$ 390) com rampa rápida: o ano 1 fica em **−R$ 17.014** e o caixa necessário em **R$ 73.069**.

Fora do modelo, mas ajudam:
- A **receita de diagnósticos**: cada um a R$ 297 deixa R$ 174,53 e não foi somado aqui.
- **Renegociar a PMT da plataforma**: carência ou valor escalonado por número de clientes.
- Os planos **Personalizado** (R$ 750) e **Private** (R$ 1.500), que entram no mesmo custo fixo.

## Recomendação do CFO

**Não lançar com R$ 18.900 de fixos e a rampa base.** O caixa acaba no mês 5. Antes de começar, escolher pelo menos duas destas:
- (a) CEO a R$ 5 mil até o break-even;
- (b) meta de ~10 clientes novos por mês, com pré-venda da turma fundadora **antes** de começar a pagar os fixos;
- (c) renegociar a PMT da plataforma para crescer junto com a base de clientes.

## Condições de dinheiro do conselho

- [x] **Unit economics por cliente positiva:** sim, 59% de contribuição.
- [ ] **Negócio paga os fixos no ano 1:** **não**. Break-even em 109 clientes, contra 55 no mês 12 da rampa base.
- [ ] **Caixa suficiente:** **não** na rampa base (R$ 183,5 mil necessários contra R$ 100 mil disponíveis). Sim em alguns cenários (CEO a R$ 5 mil + rampa rápida: R$ 57,4 mil).
- [ ] **Custo por cliente medido:** em aberto.

---

# Unit economics: Planejamento financeiro por assinatura — Acompanhamento para famílias

Every number below comes from the input file. Nothing is looked up or guessed.

## One cliente-mês

| line | per cliente-mês |
| --- | ---: |
| Price | $297.00 |
| Planejador: 20% da receita do cliente [FUNDADOR] | -$59.40 |
| Dashplan por cliente [FUNDADOR] | -$20.00 |
| Imposto sobre receita ~11% (Simples, serviços) [ESTIMATIVA — contador] | -$32.67 |
| Taxa de cobrança ~3,5% [ESTIMATIVA] | -$10.40 |
| **Contribution** (what each cliente-mês leaves to pay the fixed costs) | **$174.53** (59%) |

## The margin that matters

Fixed costs: $18,900 a month (Marketing [ESTIMATIVA — não informado] $3,000, Contador [ESTIMATIVA] $600, Ferramentas (CRM, agenda, assinatura eletrônica) [ESTIMATIVA] $300, Plataforma: PMT mensal [FUNDADOR] $5,000, CEO: adiantamento de lucros [FUNDADOR] $10,000).

- **Break-even: 109 cliente-mêss a day.** Below that you lose money every month.
- **Profit margin at your plan** (80 a day): **-21%** of every sale, after every cost.
- Capacity: 160 a day.

## Year 1, month by month

| month | cliente-mêss a day | revenue | profit | cumulative (after $15,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 3 | $891 | -$18,376 | -$33,376 |
| 2 | 6 | $1,782 | -$17,853 | -$51,229 |
| 3 | 10 | $2,970 | -$17,155 | -$68,384 |
| 4 | 15 | $4,455 | -$16,282 | -$84,666 |
| 5 | 20 | $5,940 | -$15,409 | -$100,075 |
| 6 | 25 | $7,425 | -$14,537 | -$114,612 |
| 7 | 30 | $8,910 | -$13,664 | -$128,276 |
| 8 | 35 | $10,395 | -$12,791 | -$141,068 |
| 9 | 40 | $11,880 | -$11,919 | -$152,986 |
| 10 | 45 | $13,365 | -$11,046 | -$164,033 |
| 11 | 50 | $14,850 | -$10,174 | -$174,206 |
| 12 | 55 | $16,335 | -$9,301 | -$183,507 |

- **Year 1 operating profit: -$168,507** on $99,198 of revenue.
- After the $15,000 startup spend: -$183,507.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$183,507**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | -21% | 109 | -$168,507 |
| Price -10% | -34% | 131 | -$178,427 |
| Volume -20% | -41% | 109 | -$180,166 |
| Unit costs +15% | -27% | 122 | -$174,643 |

## Red flags

- Year 1 loses money on operations (-$168,507).
- The startup spend is not earned back within year 1.

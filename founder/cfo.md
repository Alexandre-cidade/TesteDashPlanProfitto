# Nota do CFO (v4: PMT da plataforma cobre até 400 acessos)

> **Entradas do fundador:**
> - Planejador com 20% da receita.
> - **Plataforma Dashplan com PMT de R$ 5.000/mês, que cobre até 400 acessos.** Acima disso, R$ 20 por acesso extra, e a PMT sobe proporcionalmente. Como a capacidade planejada é de 160 clientes, **não há custo de plataforma por cliente** neste modelo.
> - **CEO com adiantamento de lucros de R$ 10.000/mês.**
> - R$ 100 mil de caixa.
>
> **Estimativas:** imposto (~11%), cobrança (~3,5%), contador (R$ 600), ferramentas (R$ 300), marketing (R$ 3.000), investimento inicial (R$ 15 mil) e a rampa de clientes (`cfo-sources.md`).
>
> A ferramenta escreve "$", mas tudo é **R$**; "a day" deve ser lido como "clientes ativos no mês". Isto não é aconselhamento financeiro, contábil ou jurídico. Um contador precisa validar o regime tributário e o adiantamento de lucros: só existe lucro para distribuir se houver lucro apurado.

## A margem

- **Por cliente:** cada cliente-mês a R$ 297 deixa **R$ 194,53 (65%)**.
- **Custos fixos:** **R$ 18.900/mês**, dos quais R$ 15 mil são plataforma + CEO (79%).
- **Break-even: 98 clientes ativos** a R$ 297, ou 74 a R$ 390. Com 80 clientes, a margem é de **−14%**.

## Caixa: com a rampa atual, os R$ 100 mil acabam no mês 5

Com a rampa base (3 → 55 clientes), o ano 1 fecha em **−R$ 161.827** e o caixa necessário é de **R$ 176.827**. O acumulado chega a **−R$ 98.995 no mês 5** e a −R$ 113.032 no mês 6.

| cenário (rodado na ferramenta) | break-even | resultado ano 1 | caixa necessário |
|---|---:|---:|---:|
| Base: R$ 297, rampa 3 → 55, CEO R$ 10 mil | 98 | −R$ 161.827 | **R$ 176.827** |
| R$ 390, rampa base | 74 | −R$ 141.480 | R$ 156.480 |
| CEO R$ 5 mil, rampa base | 72 | −R$ 101.827 | R$ 116.827 |
| R$ 297, **rampa rápida 10 → 135** | 98 | −R$ 53.474 | **R$ 86.248** |
| R$ 390, rampa rápida | 74 | **+R$ 806** | R$ 68.369 |
| **CEO R$ 5 mil + rampa rápida** | 72 | **+R$ 6.526** | **R$ 52.685** |

Rampa rápida significa ~10 clientes novos por mês, sem cancelamentos, até 135 no mês 12. Ainda não foi validada por nenhuma conversão real.

## A linha que mais pesa

**Velocidade de clientes contra os fixos.** Cada cliente ativo vale ~R$ 195/mês contra R$ 18.900 de fixos. A diferença entre a rampa base e a rápida, com tudo o mais igual, é de **R$ 108 mil** no resultado do ano 1 (−R$ 161.827 contra −R$ 53.474).

## Três formas de caber nos R$ 100 mil (rodadas na ferramenta)

1. **Adiantamento do CEO atrelado a marcos:** R$ 5 mil até o break-even. Na rampa base, o caixa necessário cai de R$ 176.827 para **R$ 116.827**. Com a rampa rápida, cai para **R$ 52.685**, e o ano 1 fica positivo (+R$ 6.526).
2. **Rampa rápida:** pré-venda da turma fundadora **antes** de começar a pagar o CEO, e ~10 clientes novos por mês. Só isso já leva a necessidade para **R$ 86.248**, dentro dos R$ 100 mil, mas com pouca folga.
3. **Mix de preço maior** (Assistido Profissional a R$ 390) com rampa rápida: ano 1 de **+R$ 806** e caixa necessário de **R$ 68.369**.

Fora do modelo, mas ajudam: a receita dos diagnósticos (~R$ 195 de contribuição a R$ 297, sem custo de plataforma) e os planos Personalizado e Private, que usam a mesma estrutura fixa.

## Recomendação do CFO

Não começar a pagar os R$ 15 mil de fixos (plataforma + CEO) sem **pelo menos uma destas**:
- (a) CEO a R$ 5 mil até o break-even;
- (b) ~20–30 clientes pré-vendidos na turma fundadora;
- (c) carência ou escalonamento da PMT nos primeiros meses.

**A combinação (a) + (b) é a que cabe com folga nos R$ 100 mil.**

## Condições de dinheiro do conselho

- [x] **Unit economics positiva por cliente:** 65% de contribuição.
- [ ] **Paga os fixos no ano 1:** **não** na rampa base (break-even de 98 clientes, contra 55 no mês 12). Sim nos cenários com rampa rápida e CEO a R$ 5 mil, ou com R$ 390.
- [ ] **Caixa suficiente:** **não** na rampa base. Sim com (a) + (b).
- [ ] **Custo por cliente medido:** em aberto.

---

# Unit economics: Planejamento financeiro por assinatura — Acompanhamento para famílias

Every number below comes from the input file. Nothing is looked up or guessed.

## One cliente-mês

| line | per cliente-mês |
| --- | ---: |
| Price | $297.00 |
| Planejador: 20% da receita do cliente [FUNDADOR] | -$59.40 |
| Imposto sobre receita ~11% (Simples, serviços) [ESTIMATIVA — contador] | -$32.67 |
| Taxa de cobrança ~3,5% [ESTIMATIVA] | -$10.40 |
| **Contribution** (what each cliente-mês leaves to pay the fixed costs) | **$194.53** (65%) |

## The margin that matters

Fixed costs: $18,900 a month (Marketing [ESTIMATIVA — não informado] $3,000, Contador [ESTIMATIVA] $600, Ferramentas (CRM, agenda, assinatura eletrônica) [ESTIMATIVA] $300, Plataforma Dashplan: PMT mensal, cobre até 400 acessos; acima, R$ 20/acesso extra [FUNDADOR] $5,000, CEO: adiantamento de lucros [FUNDADOR] $10,000).

- **Break-even: 98 cliente-mêss a day.** Below that you lose money every month.
- **Profit margin at your plan** (80 a day): **-14%** of every sale, after every cost.
- Capacity: 160 a day.

## Year 1, month by month

| month | cliente-mêss a day | revenue | profit | cumulative (after $15,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 3 | $891 | -$18,316 | -$33,316 |
| 2 | 6 | $1,782 | -$17,733 | -$51,049 |
| 3 | 10 | $2,970 | -$16,955 | -$68,004 |
| 4 | 15 | $4,455 | -$15,982 | -$83,986 |
| 5 | 20 | $5,940 | -$15,009 | -$98,995 |
| 6 | 25 | $7,425 | -$14,037 | -$113,032 |
| 7 | 30 | $8,910 | -$13,064 | -$126,096 |
| 8 | 35 | $10,395 | -$12,091 | -$138,188 |
| 9 | 40 | $11,880 | -$11,119 | -$149,306 |
| 10 | 45 | $13,365 | -$10,146 | -$159,453 |
| 11 | 50 | $14,850 | -$9,174 | -$168,626 |
| 12 | 55 | $16,335 | -$8,201 | -$176,827 |

- **Year 1 operating profit: -$161,827** on $99,198 of revenue.
- After the $15,000 startup spend: -$176,827.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$176,827**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | -14% | 98 | -$161,827 |
| Price -10% | -27% | 115 | -$171,747 |
| Volume -20% | -34% | 98 | -$174,822 |
| Unit costs +15% | -19% | 106 | -$166,961 |

## Red flags

- Year 1 loses money on operations (-$161,827).
- The startup spend is not earned back within year 1.

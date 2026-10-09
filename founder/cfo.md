# Nota do CFO (v2, com números do fundador)

> Entradas do fundador: **Dashplan a R$ 20 por cliente**, **planejador remunerado com 20% da receita do cliente**, **outros custos fixos praticamente zero** e **R$ 100 mil disponíveis**. Continuam como **estimativa**: imposto (~11%), taxa de cobrança (~3,5%), contador (R$ 600), ferramentas (R$ 300), marketing (R$ 3.000/mês), investimento inicial (R$ 15 mil) e a rampa de clientes (`cfo-sources.md`). A ferramenta escreve "$", mas tudo é **R$**. Como a unidade é o cliente-mês, "a day" deve ser lido como "clientes ativos no mês". Não é aconselhamento financeiro, contábil ou jurídico: um contador precisa validar regime tributário, encargos e a forma de pagar o planejador (PJ, CLT ou sócio).

## A margem

- **Acompanhamento a R$ 297:** sobram **R$ 174,53 por cliente-mês (59%)** depois de pagar planejador, Dashplan, imposto e cobrança.
- **Break-even: 23 clientes ativos.** No plano de 80 clientes, a **margem é de 42%**.
- **Ano 1:** +R$ 11.493 operacional. Contando o investimento inicial, fecha em −R$ 3.507, ou seja, **quase se paga no primeiro ano**.

Comparado com a v1, que estimava planejador por hora e Dashplan a R$ 60, o resultado virou. Pagar o planejador por percentual transforma a hora do planejador em problema de **capacidade e de atração de planejadores**, e deixa de ser problema de margem (ver abaixo).

## A linha que mais pesa: marketing e velocidade de clientes

| cenário (rodado na ferramenta) | resultado ano 1 | caixa necessário |
|---|---:|---:|
| Base (R$ 297, marketing de R$ 3 mil, rampa 3 → 55) | +R$ 11.493 | R$ 25.075 |
| Volume −20% | −R$ 166 | — |
| Preço −10% | +R$ 1.573 | — |
| **Marketing de R$ 6 mil/mês** com a mesma rampa | −R$ 24.507 | R$ 45.068 |
| **Rampa lenta** (2 → 23 clientes) | −R$ 21.493 | R$ 36.607 |
| **Assistido Profissional a R$ 390** | **+R$ 31.840**, investimento volta no **mês 11** | R$ 22.595 |

O negócio depende de **quantos clientes cada real de marketing traz**, e isso ainda não foi medido. Com volume 20% menor, o lucro do ano 1 já some.

## O planejamento doméstico (gastos do dia a dia, iFood etc.)

Sim, o serviço inclui o controle dos gastos domésticos: a plataforma, o diagnóstico e o check-in mensal. Com o planejador em 20%, isso **não muda a margem da empresa**, mas **muda quanto o planejador ganha por hora**:

- 20% de R$ 297 = **R$ 59,40 por cliente por mês** para o planejador.
- Com 1 h/mês por cliente, ele ganha R$ 59,40/h. Com 2 h, **R$ 29,70/h**.
- Para pagar R$ 70/h, o tempo precisa ficar em **~50 min por cliente-mês**.

Se o acompanhamento doméstico for "linha a linha" (revisar cada gasto de iFood, mercado, assinaturas), o tempo sobe e fica difícil atrair e manter bons planejadores a 20%. A saída é deixar **a plataforma fazer a categorização** e o planejador olhar só **3 números do mês** (por exemplo, gasto com delivery e restaurantes contra a meta). Isso também é um ótimo **gancho de marketing**: *"quanto você gastou de iFood este ano?"*.

## O diagnóstico agora dá lucro

Contribuição com planejador a 20% e Dashplan a R$ 20:
- R$ 197: **+R$ 109,03 (55%)**
- R$ 297: **+R$ 174,53 (59%)**
- R$ 490: **+R$ 300,95 (61%)**

**Recomendação:** testar o diagnóstico a **R$ 197 vs R$ 297**, como o painel pediu. Os dois dão margem. A garantia de qualidade (devolução se o plano for genérico) custa a contribuição perdida mais as horas já pagas. Com 10% de devoluções a R$ 297, são ~R$ 30 por diagnóstico vendido, o que é suportável.

## Caixa

Os **R$ 100 mil cobrem com folga** os ~R$ 25 mil que o cenário base precisa, e também os ~R$ 45 mil do cenário com marketing de R$ 6 mil. Sugestão: **separar ~R$ 30 mil** para os 12 primeiros meses e guardar o resto como reserva. Só aumentar o marketing **depois** de medir o custo por cliente no piloto.

## Três formas de melhorar (rodadas na ferramenta)

1. **Preço de R$ 390 para profissionais liberais:** contribuição de **R$ 235,45**, break-even de **17**, ano 1 com **+R$ 31.840** e investimento de volta no **mês 11**.
2. **Diagnóstico pago como porta de entrada:** cada diagnóstico a R$ 297 deixa **R$ 174,53**. Isso financia parte do marketing antes de o cliente assinar.
3. **Controlar o marketing pela conversão, não por verba fixa:** o salto de R$ 3 mil para R$ 6 mil sem mais clientes leva o ano 1 de **+R$ 11.493 para −R$ 24.507**.

## Condições de dinheiro do conselho

- [x] **Unit economics do Assistido com margem positiva:** **atendida** (59% de contribuição, break-even de 23), com as entradas do fundador.
- [x] **Garantia que o caixa aguente:** **atendida** com o diagnóstico a partir de R$ 197.
- [ ] **Plano para os primeiros 100 clientes com custo por cliente:** **em aberto**. A conversão e o custo por cliente precisam ser medidos no piloto (`/founder-marketing` e `/founder-launch`).
- [ ] **Capacidade e atratividade do planejador:** **nova condição**. Garantir ~50 min por cliente-mês para que os 20% paguem bem o planejador.

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

Fixed costs: $3,900 a month (Marketing [ESTIMATIVA — não informado] $3,000, Contador [ESTIMATIVA] $600, Ferramentas (CRM, agenda, assinatura eletrônica) [ESTIMATIVA] $300, Outros fixos: 'praticamente zero' [FUNDADOR] $0).

- **Break-even: 23 cliente-mêss a day.** Below that you lose money every month.
- **Profit margin at your plan** (80 a day): **42%** of every sale, after every cost.
- Capacity: 160 a day.

## Year 1, month by month

| month | cliente-mêss a day | revenue | profit | cumulative (after $15,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 3 | $891 | -$3,376 | -$18,376 |
| 2 | 6 | $1,782 | -$2,853 | -$21,229 |
| 3 | 10 | $2,970 | -$2,155 | -$23,384 |
| 4 | 15 | $4,455 | -$1,282 | -$24,666 |
| 5 | 20 | $5,940 | -$409 | -$25,075 |
| 6 | 25 | $7,425 | $463 | -$24,612 |
| 7 | 30 | $8,910 | $1,336 | -$23,276 |
| 8 | 35 | $10,395 | $2,209 | -$21,068 |
| 9 | 40 | $11,880 | $3,081 | -$17,986 |
| 10 | 45 | $13,365 | $3,954 | -$14,033 |
| 11 | 50 | $14,850 | $4,826 | -$9,206 |
| 12 | 55 | $16,335 | $5,699 | -$3,507 |

- **Year 1 operating profit: $11,493** on $99,198 of revenue.
- After the $15,000 startup spend: -$3,507.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$25,075**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 42% | 23 | $11,493 |
| Price -10% | 36% | 27 | $1,573 |
| Volume -20% | 38% | 23 | -$166 |
| Unit costs +15% | 36% | 25 | $5,357 |

## Red flags

- The startup spend is not earned back within year 1.

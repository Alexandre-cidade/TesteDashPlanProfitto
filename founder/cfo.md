# Nota do CFO

> **Atenção:** quase todos os custos abaixo são **ESTIMATIVAS** minhas, porque os números reais ainda não foram informados (fontes e raciocínio em `cfo-sources.md`). A ferramenta escreve "$", mas todos os valores são **R$**. Como a unidade é o "cliente-mês", "a day" na tabela deve ser lido como "clientes ativos no mês". Não é aconselhamento financeiro, contábil ou jurídico: um contador precisa validar o regime tributário (Simples, anexo III ou V), os encargos e o contrato antes de qualquer dinheiro mudar de mão.

## A margem

- **Acompanhamento a R$ 297, com 2 h de planejador por cliente por mês:** a contribuição é de **R$ 53,93 por cliente-mês (18%)**. O break-even fica em **91 clientes ativos**. No plano de 80 clientes, a margem é de **−2%**. **Do jeito que está desenhado, não fecha.**
- O ano 1, com a rampa de 3 a 55 clientes, termina com **−R$ 40.787 operacional** e **−R$ 55.787** contando o investimento inicial.

## A linha que mais pesa: horas do planejador por cliente

Com R$ 70/h, **cada meia hora por cliente-mês vale R$ 35**. Rodando a ferramenta a R$ 297:

| horas/cliente | Dashplan | contribuição | break-even | margem no plano | resultado ano 1 |
|---|---|---:|---:|---:|---:|
| 2 h | R$ 60 | R$ 53,93 | 91 | −2% | −R$ 40.787 |
| 1,5 h | R$ 60 | R$ 88,93 | 56 | 9% | −R$ 29.097 |
| 2 h | R$ 30 | R$ 83,93 | 59 | 8% | −R$ 30.767 |
| 1,5 h | R$ 30 | R$ 118,93 | 42 | 19% | −R$ 19.077 |

Os cenários do arquivo base ("preço −10%" dá break-even de 203; "custos +15%" dá 281) mostram como o resultado é sensível. **O preço e as horas decidem tudo.**

## O diagnóstico como porta de entrada dá prejuízo abaixo de R$ 490

Contribuição por diagnóstico (planejador a R$ 70/h, imposto de 11%, cobrança de 3,5%):

| preço | 4 h de trabalho | 6 h de trabalho |
|---|---:|---:|
| R$ 197 | −R$ 111,57 | −R$ 251,57 |
| R$ 297 | −R$ 26,07 | −R$ 166,07 |
| R$ 490 | **+R$ 138,95** | −R$ 1,05 |

O painel pediu um diagnóstico de R$ 150–200, mas a conta só fecha a R$ 490 **e** com no máximo ~4 h de trabalho. Abaixo disso, o diagnóstico vira **custo de aquisição**. Isso só se justifica se uma parte suficiente dos clientes converter para o acompanhamento, uma taxa que ainda não temos e que precisa ser medida no piloto.

## Caixa

Com os números base, vocês precisam de **~R$ 55.800** antes de a operação se pagar, e o investimento inicial **não volta no ano 1**. No melhor cenário testado (abaixo), a necessidade cai para **~R$ 28.800**.

## Três formas de melhorar a margem (rodadas na ferramenta)

1. **Subir para o nicho de profissionais liberais a R$ 390** (o painel aceitou até ~R$ 450 nesse segmento). Com 2 h e Dashplan a R$ 60, a contribuição vai de R$ 53,93 para **R$ 133,45**, o break-even de 91 para **37** clientes e o ano 1 de −R$ 40.787 para **−R$ 14.228**.
2. **Cortar as horas por cliente para 1,5 h/mês** com um check-in padronizado e o WhatsApp concentrado. A R$ 297, a contribuição vai para **R$ 88,93** e o break-even para **56**.
3. **Negociar o Dashplan para ~R$ 30 por cliente** (ou uma licença fixa que dilua com escala). A R$ 297 com 2 h, a contribuição vai para **R$ 83,93** e o break-even para **59**.

**Juntando as três** (R$ 390, 1,5 h, Dashplan a R$ 30): contribuição de **R$ 198,45 (51%)**, break-even de **25 clientes**, margem de **35%** no plano, **ano 1 operacional de +R$ 7.482** e caixa necessário de **R$ 28.784**. Mesmo assim, o investimento inicial não volta dentro do ano 1.

## Condições de dinheiro do conselho

- [ ] **Unit economics do Assistido com margem positiva:** **não atendida** a R$ 297 com 2 h (−2%). Passa a ser atendida a R$ 390, ou com 1,5 h, ou com o Dashplan mais barato, desde que os números reais confirmem as estimativas.
- [ ] **Garantia que o caixa aguente:** o diagnóstico a R$ 490 com 4 h deixa R$ 138,95. Com 10% de devoluções, o custo é de ~R$ 49 por diagnóstico vendido mais as horas já gastas, o que consome boa parte da margem. Só vale com o diagnóstico a R$ 490 e um limite de horas.
- [ ] **Plano para os primeiros 100 clientes com custo por cliente:** marketing de R$ 3.000/mês é uma estimativa. O custo por cliente (CAC) ainda não foi medido.

## O que eu preciso de vocês para trocar estimativa por número

1. **O custo real do Dashplan** (por cliente ou fixo).
2. **O custo do planejador:** se os sócios atendem, quanto querem de pró-labore. Se contratarem, o salário com encargos ou o repasse.
3. **Horas reais** por diagnóstico e por cliente-mês, cronometradas nos primeiros clientes.
4. **Regime tributário** com o contador.
5. **Verba de marketing e o investimento inicial disponível.**

---

# Unit economics: Planejamento financeiro por assinatura (nome a definir) — Acompanhamento para famílias

Every number below comes from the input file. Nothing is looked up or guessed.

## One cliente-mês

| line | per cliente-mês |
| --- | ---: |
| Price | $297.00 |
| Tempo do planejador: 2 h/cliente/mês (check-in 30 min + preparo + WhatsApp) × R$ 70/h [ESTIMATIVA] | -$140.00 |
| Dashplan por cliente [ESTIMATIVA, ref. Meu Vista R$ 599 / 10 famílias] | -$60.00 |
| Imposto sobre receita ~11% (Simples, serviços) [ESTIMATIVA — confirmar com contador] | -$32.67 |
| Taxa de cobrança recorrente ~3,5% [ESTIMATIVA] | -$10.40 |
| **Contribution** (what each cliente-mês leaves to pay the fixed costs) | **$53.93** (18%) |

## The margin that matters

Fixed costs: $4,900 a month (Marketing (anúncios + conteúdo) [ESTIMATIVA] $3,000, Coworking / sala para atendimento presencial em POA [ESTIMATIVA] $1,000, Contador [ESTIMATIVA] $600, Ferramentas (CRM, agenda, assinatura eletrônica, WhatsApp Business) [ESTIMATIVA] $300, Pró-labore dos sócios fora do tempo de atendimento [NÃO INFORMADO — R$ 0 por ora] $0).

- **Break-even: 91 cliente-mêss a day.** Below that you lose money every month.
- **Profit margin at your plan** (80 a day): **-2%** of every sale, after every cost.
- Capacity: 160 a day.

## Year 1, month by month

| month | cliente-mêss a day | revenue | profit | cumulative (after $15,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 3 | $891 | -$4,738 | -$19,738 |
| 2 | 6 | $1,782 | -$4,576 | -$24,315 |
| 3 | 10 | $2,970 | -$4,361 | -$28,675 |
| 4 | 15 | $4,455 | -$4,091 | -$32,766 |
| 5 | 20 | $5,940 | -$3,821 | -$36,588 |
| 6 | 25 | $7,425 | -$3,552 | -$40,140 |
| 7 | 30 | $8,910 | -$3,282 | -$43,422 |
| 8 | 35 | $10,395 | -$3,012 | -$46,434 |
| 9 | 40 | $11,880 | -$2,743 | -$49,177 |
| 10 | 45 | $13,365 | -$2,473 | -$51,650 |
| 11 | 50 | $14,850 | -$2,204 | -$53,854 |
| 12 | 55 | $16,335 | -$1,934 | -$55,787 |

- **Year 1 operating profit: -$40,787** on $99,198 of revenue.
- After the $15,000 startup spend: -$55,787.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$55,787**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | -2% | 91 | -$40,787 |
| Price -10% | -14% | 203 | -$50,707 |
| Volume -20% | -8% | 91 | -$44,390 |
| Unit costs +15% | -15% | 281 | -$52,965 |

## Red flags

- Year 1 loses money on operations (-$40,787).
- The startup spend is not earned back within year 1.

# Planejamento financeiro por assinatura (nome a definir) · Business plan

**Verdict: Not yet**

- ✓ Each cliente-mês earns $194.53 before fixed costs (65% contribution).
- ✗ Year 1 operating LOSS: $161,827.
- ✓ Break-even is 98 cliente-mêss a day against a capacity of 160.
- ✗ 0 of 50 simulated buyers buy (0%, the bar is 25%).

| key number | |
| --- | ---: |
| Price | $297.00 a cliente-mês |
| Profit margin at plan | -14% per cliente-mês |
| Break-even | 98 cliente-mêss a day |
| Year 1 operating profit | $-161,827 |
| Startup spend | $15,000 |
| Cash needed before it pays for itself | $176,827 |
| Startup money earned back | not in year 1 |
| Buyer panel | 0 buy · 50 pass |

## The idea

- O que é: empresa de planejamento e consultoria financeira por assinatura, que combina uma plataforma digital (Dashplan) com acompanhamento humano personalizado para pessoas e famílias organizarem as finanças, decidirem melhor e construírem patrimônio.
- Para quem: pessoas e famílias que reconhecem o valor de um planejamento financeiro estruturado e estão dispostas a pagar por ele, de quem ainda não investe até famílias de alta renda. O segmento a priorizar no início ainda não foi definido.
- O que vende e por quanto (assinatura mensal):
  - Digital: a partir de R$ 100/mês. Plataforma, organização, controle, metas e projeções; o cliente usa sozinho.
  - Planejamento Assistido: cerca de R$ 350/mês. Diagnóstico individual, orientação profissional e acompanhamento periódico.
  - Planejamento Personalizado: a partir de R$ 750/mês (preliminar). Consultoria completa e acompanhamento próximo.
  - Private / Family: a partir de R$ 1.500/mês (preliminar). Planejamento patrimonial e familiar complexo.
  - Os dois primeiros planos são o foco inicial.
- Onde e como: sede em Porto Alegre/RS, atendimento digital em todo o Brasil e presencial para clientes estratégicos. Aquisição por indicações, relacionamento comercial, parcerias, marketing digital e o ecossistema financeiro em que os fundadores já atuam. Entrega pela plataforma Dashplan (já contratada) mais atendimento humano conforme o plano.
- Orçamento e restrições: estrutura enxuta; os fundadores têm experiência no mercado financeiro e rede de relacionamentos. Investimento inicial, equipe, capacidade de atendimento e metas comerciais ainda não definidos (serão definidos no planejamento financeiro). Prioridades: escalabilidade, receita recorrente, alta retenção e equilíbrio entre tecnologia, personalização e rentabilidade.

## Summary

**Veredito: Not yet** (calculado pelo `compile.py`). Duas checagens falham:
- **Ano 1 dá prejuízo operacional de R$ 161.827** com a rampa atual.
- **0 de 50 compradores simulados compraram** no pitch v1 (a barra é 25%). No re-teste com a oferta nova (v2, 20 compradores), foram **2 de 20 (10%)**, ainda abaixo da barra.

**O que precisa mudar, e qual etapa muda:**
1. **Clientes mais rápido e fixos menores no início** (`/founder-cfo`, `/founder-launch`). O CFO mostra que, com o CEO a R$ 5 mil até o break-even e ~10 clientes novos por mês, o ano 1 vira **+R$ 6.526** e o caixa necessário cai para **R$ 52.685**. Isso só vale se a pré-venda provar esse ritmo.
2. **Demanda real** (`/founder-launch`). A pré-venda da turma fundadora (meta: ≥ 20 diagnósticos pagos em 4 semanas) substitui o painel simulado como prova.
3. **Oferta para o nicho que comprou** (`/founder-offer`, `/founder-marketing`): profissionais liberais e casais, com os ganchos "pare de brigar por dinheiro" e "saia do cheque especial com um plano escrito".

**O negócio:** planejamento financeiro por assinatura, de Porto Alegre para o Brasil. Um planejador faz um diagnóstico com plano escrito em 15 dias (incluindo o orçamento doméstico, até o iFood) e depois acompanha o cliente todo mês pela plataforma Dashplan, sem fidelidade e sem comissão.

**Os três números:**
- **Margem por cliente:** R$ 194,53 por mês (65%) no Acompanhamento a R$ 297.
- **Break-even:** 98 clientes ativos (74 a R$ 390).
- **Ano 1:** −R$ 161.827 na rampa base (3 → 55 clientes).

**Onde o conselho e o painel concordaram:**
- Falta nicho.
- A oferta precisa de confiança: cancelamento fácil, sem comissão, prova.
- R$ 350 é caro para o público geral; só o profissional liberal aceita.

**Onde divergiram:** o conselho valorizava a escada de 4 planos, enquanto o painel mostrou que ninguém compra a mensalidade de cara, só o diagnóstico. Dentro do conselho, a lente de Produto queria cortar para 2 planos e a de Oferta, manter os 4.

**Maior risco:** o caixa de R$ 100 mil acabar no mês ~5, porque R$ 18.900/mês de fixos (79% são plataforma + CEO) chegam antes dos clientes. **O que fazer:** não ligar o adiantamento do CEO nem o marketing pago antes da decisão de 09/11 sobre a pré-venda. Depois disso, o CEO começa a R$ 5 mil até o break-even.

**Para começar:** ~R$ 53 mil a R$ 86 mil de caixa, conforme o ritmo de clientes (há R$ 100 mil disponíveis), e o teste da pré-venda de 12/10 a 08/11.

**A única coisa a fazer esta semana:** decidir o **escopo CVM**, ou seja, se o planejador vai recomendar investimentos, e confirmar com o contador o **CNPJ que vai faturar a pré-venda**. Sem isso, nada vai ao ar.

_O painel é de compradores simulados e os números são projeções a partir de estimativas e das entradas do fundador. Clientes e cotações reais confirmam ou derrubam tudo isso. Não é aconselhamento financeiro, jurídico ou tributário._

## What the board said

Memorandos completos em `board/offers.md`, `board/monopoly.md` e `board/product.md`. As lentes resumem frameworks publicados; não falam pelos autores.

### 1. O voto

**3 FUND IF, 0 PASS.** Nota média **4,7/10** (Oferta 5, Monopólio 4, Produto 5).

Ninguém rejeitou a ideia, mas ninguém a financiaria como está. As notas baixas vêm das mesmas lacunas, não de uma falha de fundo.

### 2. Riscos levantados por mais de um membro

1. **Sem nicho, sem foco (os 3).** O público vai "de quem não investe até alta renda", com quatro planos. A Oferta vê isso virar commodity e briga de preço; o Monopólio não vê mercado pequeno para dominar; o Produto vê uma experiência que não encanta ninguém.
2. **O plano Assistido pode não fechar a conta, e o humano não escala (os 3).** Custo-hora do planejador, clientes por planejador, custo da Dashplan por cliente, CAC e churn são desconhecidos. Crescer em planos com humano pode aumentar o prejuízo.
3. **Diferencial frágil sobre plataforma de terceiros (Monopólio e Produto).** Qualquer concorrente pode contratar a mesma Dashplan. Fica a dúvida de quanto da experiência leva a marca da empresa, e qual é o plano B se o fornecedor subir o preço ou sair.
4. **O plano Digital "o cliente usa sozinho" tende a ser abandonado (Oferta e Produto).** Compete com apps baratos ou gratuitos e depende da disciplina do cliente.
5. **Regulação e conflito de interesse em aberto (os 3).** Certificações (CFP, CEA, consultor CVM) e se haverá comissão sobre investimentos não foram informados. Isso muda a confiança do cliente e a margem.

### Onde os membros discordam

- **Distribuição:** o Monopólio vê na rede dos fundadores um ponto de partida real para os primeiros clientes. A Oferta trata a rede como fácil de alcançar, mas cobra prova (piloto pago, casos) antes de escalar. Nenhum dos dois tem números.
- **O que cortar:** o Produto quer lançar só Digital e Assistido e tirar Personalizado e Private da oferta pública. A Oferta valoriza justamente a escada de quatro degraus para subir o ticket de quem já confia.
- **O que é a vantagem:** a Oferta acha que a vantagem pode vir de uma oferta melhor (garantia, resultado em 90 dias). O Monopólio exige algo durável e acumulativo (metodologia, marca no nicho, dados, parcerias exclusivas), porque uma oferta se copia.

### 3. Condições (checklist para o resto do pacote)

- [ ] Escolher **um segmento inicial** estreito e nomeado, com justificativa de por que dá para dominá-lo (`/founder-competitors`, `/founder-consumer`)
- [ ] Escrever a **promessa em uma frase**, com um **resultado mensurável em ~90 dias** (`/founder-consumer`, `/founder-offer`)
- [ ] Montar a **pilha de valor do Assistido** a partir dos obstáculos do cliente (`/founder-offer`)
- [ ] Definir uma **garantia real** que o caixa aguente (`/founder-offer`, `/founder-cfo`)
- [ ] **Unit economics por plano**, sobretudo o Assistido a ~R$ 350: custo-hora, capacidade por planejador, custo Dashplan, CAC, churn, mostrando margem positiva (`/founder-cfo`)
- [ ] Tirar o Digital do "usa sozinho": **onboarding guiado** ou um toque humano mínimo, e um hábito que segure o cliente no 2º mês (`/founder-offer`, `/founder-ops`)
- [ ] **Desenhar a jornada inteira**, do primeiro anúncio ao primeiro relatório mensal, com responsável e prazo em cada passagem entre plataforma e planejador (`/founder-ops`)
- [ ] **Conhecer a Dashplan a fundo:** marca própria possível, custo por cliente, lock-in e plano B (`/founder-ops`, `/founder-cfo`)
- [ ] **Declarar a vantagem durável** a construir e como ela se acumula (`/founder-competitors`, `/founder-marketing`)
- [ ] **Plano para os primeiros 100 clientes**, com canal e custo por cliente (`/founder-marketing`, `/founder-cfo`)
- [ ] **Piloto pago** com resultados documentados antes de escalar (`/founder-launch`)
- [ ] Esclarecer **enquadramento regulatório** (certificações, registro CVM) e **modelo de receita** (só assinatura ou também comissões) antes de lançar (`/founder-ops`)
- [ ] Decidir se Personalizado e Private ficam **fora da oferta pública** no 1º ano (disputa entre Produto e Oferta; decisão do fundador)

### 4. A versão mais forte que o conselho enxerga

Não é a que foi apresentada. O conselho vê mais força num **planejamento financeiro com humano, para um único tipo de família de Porto Alegre e região**, por exemplo profissionais liberais de alta renda ou casais com filhos pequenos. Seria vendido pela rede dos fundadores, com uma promessa mensurável (um plano completo entregue em X dias e uma meta atingida em 90) e uma garantia. O plano Assistido seria o produto principal e o Digital funcionaria como porta de entrada guiada, não como app solto. A Dashplan seria o motor, mas a marca, o método e o ritual de acompanhamento seriam da empresa, e é isso que se acumula como vantagem. Os planos Personalizado e Private viriam depois, como upgrade para quem já confia. Antes de tudo isso, a conta do Assistido precisa fechar.

## The competition

Levantamento de 09/10/2026, combinando o mapeamento do fundador com buscas públicas. **Limitação:** o acesso direto aos sites (Reclame Aqui, Grão, Ável, Portfel etc.) foi bloqueado neste ambiente. Por isso:
- Os preços marcados como *levantamento do fundador* não foram verificados por mim.
- Os demais preços vêm de trechos de páginas indexados pela busca, sem leitura completa da página.
- Notas e número de avaliações não foram coletados. Taglines só foram copiadas quando apareceram literalmente.

Detalhes e links em `competitors.csv`.

### 0. O achado mais importante: a plataforma não é diferencial

- A **Grão (Grupo Primo)** entrega o planejamento pelo **Dashplan**. Na resposta a uma reclamação, ela diz que o serviço incluía "duas reuniões individuais com o planejador financeiro e dois meses de acesso ao Dashplan" ([Reclame Aqui](https://www.reclameaqui.com.br/o-primo-rico/insatisfacao-grupo-primo-grao-planejamento_EZN0t7fFtgjZQ-wF/)).
- O Dashplan é desenvolvido pela Serafin, e a [Exame](https://exame.com/negocios/dashplan-conquista-2-mil-profissionais-em-1-ano-e-consolida-nova-carreira-no-mercado-financeiro/) fala em **mais de 2 mil profissionais** usando a plataforma em um ano.
- O Grupo Primo também vende uma [Formação de Planejador Financeiro](https://pv.oprimorico.com.br/fpf/index/) por R$ 4.997, o que coloca ainda mais planejadores no mercado.

Ou seja: o cliente pode receber a mesma ferramenta de milhares de outros planejadores, inclusive do maior nome de educação financeira do país. Isso confirma o risco que as lentes de Monopólio e de Produto levantaram no conselho. O diferencial precisa estar no nicho, no método, na marca e no atendimento, nunca na plataforma.

### 1. Quem compete (do mais direto ao menos)

| Concorrente | Tipo | Onde | Preço comparável | O que vende |
|---|---|---|---|---|
| **Ável Planejamento** (Grupo Ável, rede XP) | Direto | **Porto Alegre** + online | Essencial R$ 149,90/mês; Estratégico R$ 299,90/mês; inicial ~R$ 3.500 *(fundador)* | Planejamento personalizado com acompanhamento profissional |
| **Grão Planejamento** (Grupo Primo) | Direto | Online, Brasil | Não público | 2 reuniões + 2 meses de Dashplan; 1 ano de acompanhamento à parte |
| Planejadores independentes com Dashplan | Direto | Online, Brasil | Varia | A mesma plataforma, 2 mil+ profissionais |
| Fernanda Prado | Direto | Não confirmado | Não encontrado | Planejadora independente de famílias desde 2010 |
| Santiago Finanças | Direto | Online | Plano inicial R$ 997 + acompanhamento opcional | Planejamento com consultor |
| Unolife | Direto | Online | R$ 79,99 por sessão | Consultor online avulso, sem mensalidade |
| Consultor CVM com fee fixo (ex.: Renova Invest) | Indireto | Online | Exemplo de R$ 500/mês | Carteira + planejamento + análise tributária, sem comissão |
| Portfel | Indireto | Porto Alegre + online | % sobre ativos | Consultoria de investimentos independente |
| Propósito Partners | Indireto (vs. Private/Family) | Porto Alegre | Não encontrado | Family office e sucessão |
| Assessores XP e bancos | Indireto | Porto Alegre + Brasil | Sem mensalidade explícita | Assessor como "CFO da vida financeira" ([InfoMoney](https://www.infomoney.com.br/?p=3422347)) |
| Warren | Indireto | Online | % sobre ativos, mín. R$ 7,50/mês *(fundador)* | Gestão de investimentos |
| Finclass | Substituto | Online | A partir de R$ 79,90/mês no anual *(fundador)* | Educação financeira |
| Organizze | Substituto | App | R$ 35 / 45 / 69 por mês *(fundador)* | Controle financeiro |
| Meu Planner Financeiro | Substituto | App + WhatsApp | R$ 19,90 e R$ 34,90/mês (12x) | App com assistente de IA |
| Mobills | Substituto | App | R$ 159,90/ano (blog de 2024) | Controle de gastos |
| Planilha, gerente do banco, fazer sozinho | Substituto | — | R$ 0 | O que a maioria já faz |

### 2. Faixa de preço

**Planejamento com humano, por mês** (Ável, Renova, referência da Serasa, referência da Anbima):
- Menor: R$ 149,90 (Ável Essencial)
- Mediana aproximada: ~R$ 300 (Ável Estratégico R$ 299,90; referência da Anbima de ~R$ 2.400/ano, ou ~R$ 200/mês)
- Maior: a partir de R$ 800/mês, uma estimativa antiga da [Serasa](https://www.serasa.com.br/premium/blog/descubra-se-a-consultoria-financeira-pessoal-e-para-voce/) para mensalidade de consultoria

A Anbima cita uma faixa de R$ 300 a R$ 10.000 por ano e consultas avulsas de R$ 200 a R$ 1.000, segundo trecho de busca da página [Como Investir](https://comoinvestir.anbima.com.br/noticia/quanto-custa-ter-um-planejador-financeiro/).

**Apps e educação, por mês:** de ~R$ 13 (Mobills no anual) a R$ 79,90 (Finclass).

**Comparando com os seus planos:**

| Seu plano | Preço | Contra quem compete | Leitura |
|---|---|---|---|
| Digital | R$ 100 | Apps de R$ 13 a R$ 69 **e** Ável Essencial a R$ 149,90 *com* humano | **Zona perigosa:** é 1,5 a 7 vezes mais caro que os apps, e por mais R$ 50 a Ável promete acompanhamento profissional. Sem um toque humano, é difícil justificar. |
| Assistido | ~R$ 350 | Ável Estratégico R$ 299,90; consultor CVM ~R$ 500 | **Acima da Ável local.** Precisa de uma entrega claramente superior, ou de preço igual ou menor. |
| Personalizado | R$ 750+ | Faixa da Serasa (R$ 800+); consultores CVM | Faz sentido se a entrega for de consultoria completa. |
| Private/Family | R$ 1.500+ | Propósito, Portfel, family offices, assessores de banco | Enfrenta quem cobra % do patrimônio ou "não cobra" (comissão). Exige especialização em sucessão e tributação. |

### 3. Mapa de posicionamento (texto)

Eixos: **quanto humano o cliente recebe** (vertical) × **preço mensal** (horizontal).

```
 muito humano │                         Ável Estratégico   Consultor CVM   Propósito/Portfel
              │                           (R$300)            (~R$500)       (% patrimônio)
              │        Ável Essencial (R$150)       [SEU ASSISTIDO R$350]   [PERSONALIZADO 750] [PRIVATE 1.500]
              │  Assessor XP/banco ("grátis", comissão)
              │        Grão (2 reuniões + app; preço não público)
              │  Unolife (sessão R$80)
 pouco humano │  Planilha  Apps R$13–69  Finclass R$80        [SEU DIGITAL R$100]
              └──────────────────────────────────────────────────────────────────
                 barato                                                    caro
```

O Digital fica sozinho no canto "caro e pouco humano", que é o pior lugar do mapa.

### 4. Do que os clientes reclamam

Contagens não foram feitas: as páginas do Reclame Aqui não abriram neste ambiente. Os temas abaixo combinam o seu levantamento com trechos de busca. Todos são **ralos** até serem contados.

1. **Cancelamento difícil e renovação automática**: Organizze, Mobills, Meu Planner, Finclass *(fundador)*, e Grão: "o cliente não tem autonomia para cancelar o serviço por conta própria" ([Reclame Aqui, Grão/Diin](https://www.reclameaqui.com.br/diin/insatisfacao-com-o-servico-de-planejamento-financeiro-e-solicitacao-de-reem_saLIH555d0oPIjbc/)).
2. **O que foi vendido ≠ o que foi entregue**: um cliente da Grão esperava um planejamento anual e recebeu dois meses de app e duas reuniões, com a renovação cobrada à parte ([Reclame Aqui](https://www.reclameaqui.com.br/o-primo-rico/insatisfacao-grupo-primo-grao-planejamento_EZN0t7fFtgjZQ-wF/)). No setor de "consultoria financeira" em geral, o padrão é taxa antecipada e reembolso negado (vários casos de 2026 em resultados de busca).
3. **Falta de acompanhamento humano e troca de profissional sem aviso**: Ável *(fundador; a reclamação é da Ável Investimentos, não necessariamente do planejamento)*.
4. **Falhas da própria plataforma Dashplan**: "itens duplicados, lentidão e demora para retorno" (cliente da Grão, mesmo link do item 1). **Isso afeta vocês diretamente**, porque é a mesma ferramenta.
5. **Importação de extratos e integrações falhando**: Organizze, Meu Planner *(fundador)*.
6. **Suporte lento e pouco resolutivo**: Mobills, Meu Planner *(fundador)*.

### 5. O gap

Existe, mas é estreito e é de **execução**, não de produto:

1. **Planejamento com humano, preço fechado e entregas escritas, com cancelamento em um clique.** As reclamações 1 e 2 mostram que o setor perde confiança em contrato e cancelamento. Uma página que diga exatamente o que o cliente recebe em cada mês, sem fidelidade escondida, é rara e fácil de provar.
2. **Ritual de acompanhamento que não depende da disciplina do cliente.** A Grão vende 2 reuniões e deixa o cliente com o app; os apps deixam o cliente sozinho. Um toque humano fixo (por exemplo, um check-in mensal curto) é o que separa vocês dos dois lados.
3. **Nicho local em Porto Alegre que a Ável não ocupa.** A Ável é generalista e ligada à XP, ou seja, ligada a produtos. Um posicionamento "sem comissão, só assinatura" para um segmento específico (médicos, servidores, casais com filhos pequenos...) pode ser defendido. **Isso só vale se vocês realmente não receberem comissão**, e o conselho já pediu essa definição.
4. **Suporte ao Dashplan feito por vocês.** Se a ferramenta falha, quem responde rápido ganha a confiança.

**O que não é gap:** ter plataforma, ter planos em níveis e "planejamento personalizado". A Ável e a Grão já fazem os três.

### 6. A ameaça

- **Ável:** é a mais perigosa. Está em Porto Alegre, tem a marca e a rede da XP, já vende planejamento mais barato que o seu Assistido e tem time de planejamento ([vaga em Porto Alegre](https://bebee.com/br/jobs/consultor-de-planejamento-financeiro-mercado-financeiro-grupo-avel-porto-alegre-rio-grande-do-sul--theirstack-692676849)). Se vocês acharem um nicho, ela pode copiar a mensagem em semanas.
- **Grão / Grupo Primo:** tem audiência gigante, a mesma plataforma e uma fábrica de planejadores. Pode baixar preço e inundar o digital nacional. A defesa é o atendimento local e de nicho, que ela não faz bem em escala.
- **Os outros 2 mil usuários do Dashplan:** qualquer um pode lançar amanhã a mesma escada de planos.

### Próximos passos

- `/founder-consumer`: usar as reclamações acima como objeções reais e testar se o seu público paga R$ 100 pelo Digital sem humano.
- `/founder-pricing`: reposicionar Digital e Assistido em relação à Ável (R$ 149,90 e R$ 299,90).
- **Verificar à mão:** os preços atuais da Ável e da Grão, e as notas no Reclame Aqui da Ável, da Grão e do Dashplan/Serafin.

### Fontes

- [Anbima – Quanto custa um planejador](https://comoinvestir.anbima.com.br/noticia/quanto-custa-ter-um-planejador-financeiro/)
- [Serasa – Consultoria financeira pessoal](https://www.serasa.com.br/premium/blog/descubra-se-a-consultoria-financeira-pessoal-e-para-voce/)
- [Renova Invest – Fee fixo](https://renovainvest.com.br/blog/vantagens-fee-fixo/)
- [Exame – Dashplan 2 mil profissionais](https://exame.com/negocios/dashplan-conquista-2-mil-profissionais-em-1-ano-e-consolida-nova-carreira-no-mercado-financeiro/)
- [Reclame Aqui – Grão (Grupo Primo)](https://www.reclameaqui.com.br/o-primo-rico/insatisfacao-grupo-primo-grao-planejamento_EZN0t7fFtgjZQ-wF/)
- [Reclame Aqui – Grão (Diin)](https://www.reclameaqui.com.br/diin/insatisfacao-com-o-servico-de-planejamento-financeiro-e-solicitacao-de-reem_saLIH555d0oPIjbc/)
- [InfoMoney – XP e o assessor como CFO](https://www.infomoney.com.br/?p=3422347)
- [Formação de Planejador – O Primo Rico](https://pv.oprimorico.com.br/fpf/index/)
- [Unolife](https://unolife.com.br/consultor-financeiro-online/) · [Santiago Finanças](https://www.alexandresantiago.com.br/) · [Meu Planner Financeiro](https://meuplannerfinanceiro.com.br/) · [Portfel](https://portfel.com.br/) · [Propósito Partners](https://proposito.partners/) · [Fernanda Prado](https://fernandaprado.com.br/)
- Levantamento do fundador: Ável, Organizze, Mobills, Meu Planner, Finclass, Warren (links no CSV)

## The buyer panel

**0 buy · 50 pass** (0% buy) out of 50 simulated buyers. Seed 998290, so the same cards can be dealt again.

These are simulated buyers, not customers. Use this to find objections and weak spots, then confirm the big ones with real people before you spend.

### By segment

| group | buyers | buy rate |
| --- | ---: | ---: |
| Jovem profissional, ainda sem investimentos | 18 | 0% |
| Família de classe média com filhos | 17 | 0% |
| Pré-aposentado ou aposentado | 5 | 0%  (thin) |
| Profissional liberal de alta renda (médico, advogado, empresário) | 10 | 0% |

### By buying behaviour

| group | buyers | buy rate |
| --- | ---: | ---: |
| Confia no gerente ou assessor do banco | 9 | 0% |
| Faz planilha sozinho | 10 | 0% |
| Contrata por indicação | 5 | 0%  (thin) |
| Segue influenciador de finanças | 7 | 0%  (thin) |
| Endividado buscando saída | 5 | 0%  (thin) |
| Já usou app e largou | 8 | 0% |
| Pesquisa no Reclame Aqui antes de comprar | 6 | 0%  (thin) |

### By income

| group | buyers | buy rate |
| --- | ---: | ---: |
| under $136,000 | 16 | 0% |
| $246,000 and up | 17 | 0% |
| $136,000 to $246,000 | 17 | 0% |

### Why they pass

| reason | buyers | in their words |
| --- | ---: | --- |
| trust | 24 | "Meu gerente do banco já me orienta de graça. Pagar R$ 350 todo mês para uma empresa nova que nem diz como cancelar não faz sentido para mim agora." (P001) · "Eu só contrato quem alguém de confiança me indicou, e ninguém que eu conheço usou essa empresa nova. Além disso, R$ 350 por mês sem saber se tem fidelidade ou como cancelar me parece arriscado demais." (P004) |
| habit | 14 | "Já controlo tudo na minha planilha e sei para onde vai meu dinheiro. Pagar R$ 350 todo mês, R$ 4.200 por ano, é dinheiro que eu prefiro colocar direto na meta do apartamento." (P002) · "Eu já controlo tudo na minha planilha e funciona; já tentei app e larguei, e pagar R$ 350 por mês para alguém me dizer o que eu já anoto não faz sentido pra mim." (P003) |
| price | 12 | "R$ 350 por mês, todo mês, é mais de R$ 4 mil por ano para alguém me dizer o que eu já ouço de graça no YouTube. E ainda sem saber se tem fidelidade, eu não assino." (P005) · "Eu tô com cartão e cheque especial rodando, R$ 350 todo mês é praticamente uma parcela de dívida a mais. Pagar isso pra alguém me dizer pra gastar menos não fecha a conta agora." (P009) |

### Why they buy

| reason | buyers | in their words |
| --- | ---: | --- |

### What would flip a no

- Cancelamento livre a qualquer momento, sem multa, escrito de forma clara, e um primeiro mês ou diagnóstico gratuito para eu ver se vale a pena.
- Um diagnóstico avulso, pago uma vez só e sem fidelidade, que me mostrasse um erro ou ganho concreto no meu plano do imóvel que eu não teria visto sozinho.
- Um diagnóstico avulso, sem assinatura, que me mostrasse em números algo que minha planilha não mostra, como quanto eu deixo de ganhar em investimento ou imposto.
- Uma amiga ou colega de confiança me contar que usou, que o planejador ajudou de verdade e que dá para cancelar quando quiser.
- Uma primeira sessão de diagnóstico a preço baixo, com nós dois juntos, e cancelamento livre a qualquer momento escrito na oferta.
- Cancelamento sem fidelidade e sem multa, escrito claramente, com um primeiro mês de diagnóstico grátis ou barato para eu ver se o plano realmente me ajuda a comprar o imóvel mais rápido do que com o gerente.
- Um primeiro mês gratuito ou sem fidelidade, com cancelamento a qualquer hora, e uma conta clara de quanto eu economizaria ou ganharia a mais em comparação com o que meu gerente já faz.
- Um primeiro mês de diagnóstico focado em sair do cheque especial, sem fidelidade e com cancelamento fácil por escrito, com o planejador me cobrando ativamente em vez de eu ter que lembrar de abrir a plataforma.
- Um plano mais barato focado em sair das dívidas, sem fidelidade, ou que só cobre depois que eu economizar pelo menos o valor da mensalidade.
- Cancelamento a qualquer momento por escrito, sem multa, e um planejador independente com certificação (CFP) que me mostre por escrito que não ganha comissão de produto, ao contrário do meu assessor.
- Uma indicação de alguém de confiança que usou e viu resultado concreto, mais cancelamento livre a qualquer momento sem multa.
- Se o planejador servisse de mediador neutro numa conversa com meu marido sobre metas, com uma primeira sessão de diagnóstico gratuita e cancelamento livre a qualquer momento.

50 buyers gave all four price answers. Run founder-pricing's van_westendorp.py on the answers folder.

## Pricing

Fontes: painel de 50 compradores simulados (`panel/results.md`, `pricing-curve.md`), concorrentes (`competitors.md`). **A margem não foi calculada**: falta `founder/numbers.json`, que é feito pelo `/founder-cfo`. Respostas simuladas servem para escolher o que testar, não provam nada.

### Antes de tudo: o painel deu 0 de 50, e parte disso é culpa do pitch

Nenhum dos 50 comprou o Assistido a R$ 350. Os motivos foram confiança (24), hábito (14) e preço (12). Mas o pitch dizia, por honestidade, que "a empresa não informou se há fidelidade ou como funciona o cancelamento", e **49 de 50** citaram exatamente isso. Logo, o 0% mede uma oferta incompleta, não o serviço. Mesmo assim, três sinais se sustentam independentemente do pitch:

1. **R$ 350 está acima da faixa aceitável** para a média: PME de R$ 300, e metade disse que R$ 350 ou menos já é "caro demais".
2. **32 de 50 pediram para começar por um diagnóstico avulso** ou um primeiro mês de teste antes de assinar.
3. **13 de 50 pediram, por escrito, "sem comissão"** e 10 pediram planejador CFP. Querem saber se o planejador ganha vendendo produto.

### 1. A faixa do painel (Van Westendorp, Assistido)

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

### 2. Contra os concorrentes

- Ável Estratégico: R$ 299,90; Ável Essencial: R$ 149,90 (levantamento do fundador, não verificado). Ambos em Porto Alegre e com humano.
- Consultor CVM com fee fixo: exemplo de ~R$ 500/mês, incluindo carteira e análise tributária.
- Apps: R$ 13 a R$ 69/mês.

O PME do painel (R$ 300) é quase igual ao preço da Ável Estratégico. O mercado local e os compradores simulados apontam para o mesmo teto no público geral.

### 3. A recomendação

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

### 4. Oferta de abertura (sem treinar desconto)

**"Turma fundadora": as 30 primeiras famílias** (escassez real: capacidade do time)
- Diagnóstico abatido integralmente da assinatura
- Preço travado por 12 meses
- **Sem fidelidade, cancelamento online em um clique, por escrito** na página de venda (a objeção nº 1, em 49 de 50)
- Termina numa data fixa (por exemplo, 31/01/2027) ou quando fechar a 30ª vaga, o que vier primeiro

Sem "de R$ X por R$ Y": nenhum preço "cheio" foi cobrado ainda, então não há âncora honesta.

### 5. O que testar com pessoas reais

1. **Duas landing pages** com o mesmo texto, incluindo a política de cancelamento e "sem comissão", e preços diferentes:
   - Assistido a R$ 297 vs R$ 350, para famílias
   - Assistido Profissional a R$ 390 vs R$ 450, para profissionais liberais (anúncio segmentado ou indicação)
2. **Pré-venda do Diagnóstico** a R$ 490 vs R$ 790. Medir a conversão de diagnóstico em assinatura em 30 dias.
3. Meta para decidir: ao menos 10 diagnósticos pagos por variação antes de fixar o preço.

### 6. Objeções de preço, nas palavras do painel (para o marketing)

1. "R$ 350 por mês, todo mês, é mais de R$ 4 mil por ano para alguém me dizer o que eu já ouço de graça no YouTube. E ainda sem saber se tem fidelidade, eu não assino." (P005)
2. "Meu gerente do banco já me orienta de graça. Pagar R$ 350 todo mês para uma empresa nova que nem diz como cancelar não faz sentido para mim agora." (P001)
3. "Eu tô com cartão e cheque especial rodando, R$ 350 todo mês é praticamente uma parcela de dívida a mais. Pagar isso pra alguém me dizer pra gastar menos não fecha a conta agora." (P009)

São falas de compradores simulados, não depoimentos de clientes.

### Próximos passos

- `/founder-cfo`: margem a R$ 297, R$ 350 e R$ 390. Precisa do custo do Dashplan por cliente, do custo-hora ou salário do planejador e de quantos clientes ele atende.
- `/founder-offer`: política de cancelamento, "sem comissão", diagnóstico como porta de entrada e o Digital com toque humano. Depois, re-testar com `/founder-consumer --quick` usando o pitch corrigido.

## The offer

Método: lente de Oferta (`../.claude/skills/founder-board/lenses.md`), um resumo do framework publicado em *$100M Offers*. Entradas: o painel v1 (50 compradores), os concorrentes, o conselho e o pricing.

**Custos:** ainda não existe `numbers.json`. A coluna "custo" abaixo é uma estimativa relativa (1 = quase nada, 5 = caro), baseada no tempo do planejador. Tudo precisa ser validado no `/founder-cfo`.

### 1. Lista de problemas (nas palavras do comprador)

**Antes de comprar**
1. "E se eu quiser cancelar? Essas empresas complicam." (49/50 no v1)
2. "Empresa nova, não tem nada no Reclame Aqui."
3. "Ninguém que eu conheço usou; só contrato por indicação."
4. "Meu gerente do banco já faz isso de graça."
5. "Como sei que o planejador não vai me empurrar produto?"
6. "O planejador é certificado?"
7. "R$ 350/mês é mais de R$ 4 mil por ano."
8. "Uma planilha resolve."
9. "Vejo isso de graça no YouTube."
10. "Vou abrir todas as minhas contas para uma empresa que acabou de nascer?"

**Durante**
11. "Já baixei app e larguei; vou pagar e não usar."
12. "Depois das primeiras reuniões, o que muda no mês seguinte?"
13. "Vou ter que lembrar de abrir a plataforma."
14. "O plano vai ser genérico: cortar gastos e investir mais."
15. "Toda conversa sobre dinheiro com meu cônjuge vira briga."
16. "Estou com cheque especial rodando; preciso sair disso primeiro."
17. "Demoram para responder" (reclamação real de concorrentes).
18. "A plataforma trava ou duplica itens" (reclamação real do Dashplan, cliente da Grão).

**Depois**
19. "Como vou saber se está funcionando?"
20. "E se o plano não servir para nada?"
21. "Não sei se compensa versus o que o gerente me cobra em taxas escondidas."

### 2. Soluções, pontuadas

| # | solução | resolve | valor (1–5) | custo (1–5) | fica? |
|---|---|---|---:|---:|---|
| A | **Sem fidelidade, cancelamento online, sem multa, por escrito** | 1 | 5 | 1 | ✅ core |
| B | **Diagnóstico avulso antes de assinar**, com prazo e plano escrito | 7, 8, 9, 20 | 5 | 3 | ✅ porta de entrada |
| C | **"Remunerado só pela assinatura, sem comissão"** (*só se for verdade*) | 4, 5, 21 | 4 | 1 | ✅ se verdadeiro |
| D | **Sessão do casal** dentro do diagnóstico (os dois juntos, planejador como terceiro neutro) | 15 | 4 | 2 | ✅ bônus |
| E | **Raio-X de custos do banco**: taxas, tarifas e produtos que o cliente já paga | 4, 21 | 5 | 2 | ✅ bônus |
| F | **Plano exemplo anonimizado** publicado no site | 2, 14 | 4 | 1 | ✅ prova |
| G | **Check-in mensal ativo** (o planejador procura o cliente, não o contrário) | 11, 12, 13 | 5 | 3 | ✅ core |
| H | **Painel de 1 número por mês** ("quanto você avançou na meta") | 12, 19 | 4 | 2 | ✅ core |
| I | **Resposta por WhatsApp em até 1 dia útil** | 17, 18 | 4 | 2 | ✅ core |
| J | **Garantia de qualidade do diagnóstico** (ver §3) | 14, 20 | 5 | 2 | ✅ garantia |
| K | Trilha "sair do cheque especial em 90 dias" | 16 | 4 | 2 | 🔶 variação para endividados |
| L | Planejador com CFP | 6 | 3 | 4 | 🔶 só se já tiver; não prometer |
| M | Termo de confidencialidade e LGPD simples na contratação | 10 | 3 | 1 | ✅ |
| N | Indicação com benefício (1 mês grátis para quem indica e para o indicado) | 3 | 3 | 2 | ✅ depois do piloto |
| O | Reuniões semanais | 12 | 3 | 5 | ❌ caro demais |
| P | Garantia de retorno ou resultado financeiro | 20 | 5 | 5 | ❌ **proibido**: não se promete rentabilidade |

### 3. A oferta montada

#### Nome: **"Plano Claro em 15 Dias"** (provisório, para o `/founder-brand` refinar)

**O core: "Em 15 dias você sabe exatamente para onde vai seu dinheiro e quais são os próximos 3 passos. Depois, um planejador te acompanha todo mês, sem fidelidade."**

1. **Diagnóstico Financeiro** (pagamento único): análise de contas, dívidas, investimentos e metas, e um **plano por escrito com as 3 primeiras ações**, em até 15 dias.
   - Preço testado no re-teste: R$ 490. **Sinal do re-teste: baixar para ~R$ 197–297** (7/20 pediram R$ 150–200). Testar R$ 197 vs R$ 297 com gente real.
2. **Acompanhamento** (opcional): R$ 297/mês para famílias, com o valor do diagnóstico abatido.
   - Check-in mensal de 30 minutos **marcado pelo planejador**
   - Um número-chave do mês (avanço na meta)
   - WhatsApp com resposta em até 1 dia útil
   - Plataforma de controle e metas
3. **Assistido Profissional** (R$ 390/mês) para profissionais liberais: o mesmo, mais revisão tributária PF/PJ e previdência. *Não testado no re-teste.*

**Bônus** (cada um mata uma objeção):
- **Sessão do casal**: no diagnóstico, uma reunião com os dois e o planejador como terceiro neutro. Responde à objeção 15, que foi o motivo de uma das duas compras no re-teste.
- **Raio-X do banco**: uma lista das tarifas, taxas de fundos e seguros que o cliente já paga. Responde a "meu gerente faz de graça".
- **Plano exemplo**: um diagnóstico real, anonimizado e com autorização, publicado no site. Responde a "vai ser genérico".

**Garantia (duas partes):**
1. Se o plano não for entregue em 15 dias, devolve 100%. *(Já estava no v2.)*
2. **Novo:** se, na reunião de entrega, o cliente achar o plano genérico, devolve 100% do diagnóstico. 6/20 disseram que a garantia v2 cobria só o atraso.
   - **Custo:** com uma taxa de pedido realista de 5–10%, custa de 5% a 10% da receita de diagnósticos mais as horas gastas. Modelar no `/founder-cfo` antes de prometer.

Nunca garantir rentabilidade ou resultado financeiro. Isso é vedado na publicidade de investimentos e seria impossível de cumprir.

**Urgência e escassez (verdadeiras):**
- Turma fundadora com 30 vagas, limitadas pela capacidade real do time
- Preço travado por 12 meses
- Até 31/01/2027 ou até fechar a 30ª vaga

**Prova** (sem inventar nada):
- Plano exemplo anonimizado
- Quem é o planejador: nome, formação, anos de mercado
- Depoimentos **só depois** do piloto, com clientes reais e autorizados

**Avisos de conformidade** (não é aconselhamento jurídico):
- "Sem comissão" e "não vende produtos" só podem ir ao ar se forem verdade.
- Recomendar investimentos específicos de forma independente exige registro de consultor na CVM (Res. CVM 19/2021). Sem registro, o plano fica em organização financeira e alocação genérica.
- Compra online tem direito de arrependimento de 7 dias (art. 49 do CDC) de qualquer forma. A garantia precisa ir além disso para valer como argumento.

### 4. Equação de valor (antes → depois)

| elemento | v1 | oferta | o que moveu |
|---|---:|---:|---|
| Resultado dos sonhos | 6 | 7 | Diagnóstico com 3 ações concretas; trilhas de imóvel, dívidas e casal |
| Probabilidade percebida | 2 | 6 | Sem fidelidade, sem comissão, plano exemplo, garantia de qualidade |
| Tempo até o resultado | 3 | 7 | Plano em 15 dias, em vez de "acompanhamento periódico" vago |
| Esforço e sacrifício | 3 | 6 | Check-in marcado pelo planejador; o cliente não precisa lembrar de abrir o app |

### 5. Re-teste (20 compradores, mesma semente)

Pitch v2 em `pitch.md`; v1 guardado em `pitch-v1.md`. A v2 testou o core, a garantia de prazo, o sem fidelidade e o sem comissão. **Os bônus (casal, raio-X, plano exemplo) e a garantia de qualidade foram desenhados depois, a partir das respostas, e ainda não foram testados.**

| | v1 (50) | v2 (20) |
|---|---:|---:|
| Compram | **0%** | **10%** (2 de 20, ambos só o diagnóstico) |
| Passam por confiança | 48% | 20% |
| Passam por hábito | 28% | 35% |
| Passam por preço | 24% | 25% |

- **O que caiu:** o cancelamento deixou de ser objeção. Vários disseram que "gostaram que é pelo site e sem multa", mas que isso não bastava.
- **Por que os dois compraram:**
  - "R$ 490 com devolução se não entregarem no prazo é um risco pequeno perto dos juros que já pago" (P003, endividada)
  - "Ter um terceiro neutro com um plano por escrito para levar ao meu marido" (P018)
- **O que sobrou:**
  - "Meu gerente faz de graça" e "a planilha resolve" (hábito)
  - Diagnóstico caro para quem ainda não investe
  - Falta de prova social, porque a empresa é nova
- **Leitura:** a oferta funcionou como **porta de entrada**, já que os compradores compram o diagnóstico, não a mensalidade. Para virar assinatura, o diagnóstico precisa provar valor. A dor do **casal** e a das **dívidas** são os ganchos que converteram, e valem mais que "organizar finanças". Simulação tende a ser otimista: trate 10% como teto.

### Próximos passos

- `/founder-cfo`: custo do diagnóstico em horas, margem a R$ 197, R$ 297 e R$ 490, custo da garantia e margem do acompanhamento a R$ 297 e R$ 390.
- `/founder-marketing`: posicionar pelos ganchos que converteram ("pare de brigar por dinheiro", "saia do cheque especial com um plano escrito") e pelo "sem comissão".

## The numbers

> **Entradas do fundador:**
> - Planejador com 20% da receita.
> - **Plataforma Dashplan com PMT de R$ 5.000/mês, que cobre até 400 acessos.** Acima disso, R$ 20 por acesso extra, e a PMT sobe proporcionalmente. Como a capacidade planejada é de 160 clientes, **não há custo de plataforma por cliente** neste modelo.
> - **CEO com adiantamento de lucros de R$ 10.000/mês.**
> - R$ 100 mil de caixa.
>
> **Estimativas:** imposto (~11%), cobrança (~3,5%), contador (R$ 600), ferramentas (R$ 300), marketing (R$ 3.000), investimento inicial (R$ 15 mil) e a rampa de clientes (`cfo-sources.md`).
>
> A ferramenta escreve "$", mas tudo é **R$**; "a day" deve ser lido como "clientes ativos no mês". Isto não é aconselhamento financeiro, contábil ou jurídico. Um contador precisa validar o regime tributário e o adiantamento de lucros: só existe lucro para distribuir se houver lucro apurado.

### A margem

- **Por cliente:** cada cliente-mês a R$ 297 deixa **R$ 194,53 (65%)**.
- **Custos fixos:** **R$ 18.900/mês**, dos quais R$ 15 mil são plataforma + CEO (79%).
- **Break-even: 98 clientes ativos** a R$ 297, ou 74 a R$ 390. Com 80 clientes, a margem é de **−14%**.

### Caixa: com a rampa atual, os R$ 100 mil acabam no mês 5

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

### A linha que mais pesa

**Velocidade de clientes contra os fixos.** Cada cliente ativo vale ~R$ 195/mês contra R$ 18.900 de fixos. A diferença entre a rampa base e a rápida, com tudo o mais igual, é de **R$ 108 mil** no resultado do ano 1 (−R$ 161.827 contra −R$ 53.474).

### Três formas de caber nos R$ 100 mil (rodadas na ferramenta)

1. **Adiantamento do CEO atrelado a marcos:** R$ 5 mil até o break-even. Na rampa base, o caixa necessário cai de R$ 176.827 para **R$ 116.827**. Com a rampa rápida, cai para **R$ 52.685**, e o ano 1 fica positivo (+R$ 6.526).
2. **Rampa rápida:** pré-venda da turma fundadora **antes** de começar a pagar o CEO, e ~10 clientes novos por mês. Só isso já leva a necessidade para **R$ 86.248**, dentro dos R$ 100 mil, mas com pouca folga.
3. **Mix de preço maior** (Assistido Profissional a R$ 390) com rampa rápida: ano 1 de **+R$ 806** e caixa necessário de **R$ 68.369**.

Fora do modelo, mas ajudam: a receita dos diagnósticos (~R$ 195 de contribuição a R$ 297, sem custo de plataforma) e os planos Personalizado e Private, que usam a mesma estrutura fixa.

### Recomendação do CFO

Não começar a pagar os R$ 15 mil de fixos (plataforma + CEO) sem **pelo menos uma destas**:
- (a) CEO a R$ 5 mil até o break-even;
- (b) ~20–30 clientes pré-vendidos na turma fundadora;
- (c) carência ou escalonamento da PMT nos primeiros meses.

**A combinação (a) + (b) é a que cabe com folga nos R$ 100 mil.**

### Condições de dinheiro do conselho

- [x] **Unit economics positiva por cliente:** 65% de contribuição.
- [ ] **Paga os fixos no ano 1:** **não** na rampa base (break-even de 98 clientes, contra 55 no mês 12). Sim nos cenários com rampa rápida e CEO a R$ 5 mil, ou com R$ 390.
- [ ] **Caixa suficiente:** **não** na rampa base. Sim com (a) + (b).
- [ ] **Custo por cliente medido:** em aberto.

---

## Unit economics: Planejamento financeiro por assinatura — Acompanhamento para famílias

Every number below comes from the input file. Nothing is looked up or guessed.

### One cliente-mês

| line | per cliente-mês |
| --- | ---: |
| Price | $297.00 |
| Planejador: 20% da receita do cliente [FUNDADOR] | -$59.40 |
| Imposto sobre receita ~11% (Simples, serviços) [ESTIMATIVA — contador] | -$32.67 |
| Taxa de cobrança ~3,5% [ESTIMATIVA] | -$10.40 |
| **Contribution** (what each cliente-mês leaves to pay the fixed costs) | **$194.53** (65%) |

### The margin that matters

Fixed costs: $18,900 a month (Marketing [ESTIMATIVA — não informado] $3,000, Contador [ESTIMATIVA] $600, Ferramentas (CRM, agenda, assinatura eletrônica) [ESTIMATIVA] $300, Plataforma Dashplan: PMT mensal, cobre até 400 acessos; acima, R$ 20/acesso extra [FUNDADOR] $5,000, CEO: adiantamento de lucros [FUNDADOR] $10,000).

- **Break-even: 98 cliente-mêss a day.** Below that you lose money every month.
- **Profit margin at your plan** (80 a day): **-14%** of every sale, after every cost.
- Capacity: 160 a day.

### Year 1, month by month

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

### What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | -14% | 98 | -$161,827 |
| Price -10% | -27% | 115 | -$171,747 |
| Volume -20% | -34% | 98 | -$174,822 |
| Unit costs +15% | -19% | 106 | -$166,961 |

### Red flags

- Year 1 loses money on operations (-$161,827).
- The startup spend is not earned back within year 1.

## Operations

Base: `offer.md` (Diagnóstico + Acompanhamento), `numbers.json` (CFO v4) e `pricing.md`. Onde não achei preço público, está marcado **cotar**. Regras e licenças variam por lugar e mudam com o tempo: confirme cada uma com o órgão ou com um profissional. Nada disto é aconselhamento jurídico ou contábil.

### 1. O ciclo de trabalho

O negócio não tem "abrir a loja". O ciclo é a **semana** e o **mês** de cada cliente. 👁 = o cliente vê.

**Todo dia**
1. Responder os leads novos (WhatsApp, Instagram, site) em até 4 h úteis 👁
2. Responder os clientes ativos no WhatsApp em até **1 dia útil**, que é a promessa da oferta 👁
3. Conferir os pagamentos do dia (diagnósticos e mensalidades) e acionar quem falhou 👁
4. Registrar no CRM tudo o que foi falado com cada cliente

**Diagnóstico (15 dias, prometido na oferta)**
1. Dia 0: pagamento → contrato e termo de LGPD assinados eletronicamente → convite para a plataforma 👁
2. Dias 1–3: cliente envia extratos e faturas, ou conecta as contas → planejador confere se está completo 👁
3. Dias 3–7: **sessão do casal** (60–90 min, vídeo ou presencial em Porto Alegre) 👁
4. Dias 7–12: planejador monta o plano: gastos do dia a dia por categoria (delivery, mercado, assinaturas), dívidas, reserva, metas e **raio-X de tarifas do banco**
5. Dias 12–15: **reunião de entrega** com o plano escrito e as 3 primeiras ações 👁 → oferta do Acompanhamento → garantia de qualidade se o cliente achar genérico 👁

**Acompanhamento (todo mês)**
1. Semana 1: a plataforma fecha o mês e o planejador olha **3 números** (por exemplo, gasto com delivery/restaurante contra a meta, valor guardado, dívida restante)
2. Semana 2: **check-in de 30 min marcado pelo planejador** 👁
3. Envio do "número do mês" por WhatsApp 👁
4. Meta de tempo: **~50 min por cliente-mês**. Acima disso, os 20% pagam menos de R$ 70/h ao planejador (ver `cfo.md`)

**Toda semana:** revisão de pipeline (leads → diagnósticos → assinaturas), revisão da qualidade de 1 plano por amostragem e cobrança dos inadimplentes.

**Todo mês:** fechamento financeiro com o contador, repasse dos 20% aos planejadores e checagem dos acessos da plataforma contra o limite de 400.

### 2. Fornecedores

| item | opções | preço público | fonte / observação |
|---|---|---|---|
| Plataforma de planejamento | **Dashplan** (já contratada) | R$ 5.000/mês até 400 acessos; R$ 20 por acesso extra | Fundador. **Pedir por escrito:** SLA de suporte, prazo de correção de bugs (há [relato de itens duplicados e lentidão](https://www.reclameaqui.com.br/diin/insatisfacao-com-o-servico-de-planejamento-financeiro-e-solicitacao-de-reem_saLIH555d0oPIjbc/)), possibilidade de marca própria, exportação dos dados dos clientes e regra de saída do contrato |
| Cobrança recorrente | **Asaas**; Iugu; Pagar.me | Asaas: Pix R$ 0,99 por cobrança nos 3 primeiros meses e R$ 1,99 depois; boleto sem taxa de emissão; **taxa de cartão não encontrada, cotar** | [blog Asaas](https://blog.asaas.com/taxas-asaas/). Se a maioria pagar por Pix, o custo fica abaixo dos ~3,5% estimados pelo CFO |
| Assinatura eletrônica | **ZapSign**; Clicksign | ZapSign: R$ 29,90–39,90/mês no plano Profissional (fonte inconsistente) e R$ 89,90 no Team; Clicksign: **cotar** | [blog ZapSign](https://blog.zapsign.com.br/en/melhor-plataforma-assinatura-eletronica/), [Clicksign](https://www.clicksign.com/en/tabela-comparativa) |
| Contador | Escritórios de Porto Alegre e contabilidades online | **cotar** (CFO estima R$ 600/mês) | Pedir que cotem já com o enquadramento do CNAE e o tratamento do adiantamento de lucros |
| Seguro de RC profissional | Corretoras com RC profissional para a área financeira | Faixa genérica de R$ 60–250/mês para coberturas de R$ 100–500 mil (autônomos, não é específico) | [guia](https://www.freelasemcrise.com.br/blog/seguro-rc-profissional-quem-precisa). **Cotar** para consultoria financeira |
| Sala para atendimento presencial | Coworking com sala de reunião por hora | **cotar** | Só quando houver cliente presencial; o fundador disse que os fixos são "praticamente zero" |
| WhatsApp, agenda e CRM | WhatsApp Business (gratuito); agenda do Google ou Calendly; CRM simples | **cotar** | Cabe nos R$ 300/mês de ferramentas estimados pelo CFO |

**Para o CFO:** nenhum preço encontrado contradiz `numbers.json`. A taxa de cobrança pode ser **menor** que a estimada se o Pix dominar. Re-rodar quando houver a cotação de cartão do gateway.

### 3. Pessoas

| papel | quem | remuneração | carga |
|---|---|---|---|
| CEO: vendas, parcerias, marketing, financeiro | sócio | R$ 10.000/mês de adiantamento de lucros (fundador). O CFO recomenda R$ 5 mil até o break-even | integral |
| Planejador(es) | sócios e/ou contratados | **20% da receita do cliente** (fundador), "talvez mais um fixo" | por cliente |
| Contador | externo | ver acima | mensal |

**Capacidade por planejador** (estimativa): ~128 h úteis por mês dedicadas a clientes.
- Com ~50 min por cliente-mês, um planejador atende **~150 clientes de acompanhamento**, ou menos se fizer diagnósticos.
- Cada diagnóstico leva ~4 h. Com 10 diagnósticos por mês, são 40 h, e sobra espaço para ~100 clientes de acompanhamento.

**Escala semanal no 1º mês (3–10 clientes)**

| | seg | ter | qua | qui | sex |
|---|---|---|---|---|---|
| CEO | prospecção na rede, parcerias | conteúdo | reuniões comerciais | parcerias (contadores) | pipeline e financeiro |
| Planejador | diagnósticos | sessões do casal | montagem dos planos | entregas | WhatsApp e qualidade |

**No plano (~80–100 clientes):** 1 planejador em tempo integral, ou 2 em meio período. O CEO para de atender e só vende. Abrir uma 2ª vaga de planejador ao passar de ~120 clientes.

**Para o contador:** os encargos dependem de o planejador ser PJ (repasse dos 20%), CLT ou sócio. A diferença pode ser grande, e o CFO usou 20% "limpo".

### 4. Rotinas (uma página cada)

#### R1. Entrada de um cliente novo (Diagnóstico)
1. Confirmar o pagamento no gateway.
2. Enviar em até 2 h: contrato + termo de LGPD (assinatura eletrônica) + convite da plataforma + link de agenda da sessão do casal.
3. Mensagem de boas-vindas no WhatsApp com o nome do planejador e o prazo: "seu plano fica pronto até dd/mm".
4. Criar o cliente no CRM com a data-limite de 15 dias.
5. No dia 3, se os documentos não chegaram, lembrar o cliente. **O prazo de 15 dias só começa a contar com os documentos completos**, e isso precisa estar escrito no contrato.

#### R2. Entrega do plano
1. Revisão por um segundo planejador ou pelo CEO: o plano tem que ter **números do cliente**, não frases genéricas.
2. Reunião de 45 min: os 3 números de hoje, as 3 primeiras ações e o que muda em 90 dias.
3. Oferecer o Acompanhamento com o valor do diagnóstico abatido.
4. Perguntar diretamente: "Isto foi útil para você?" Se a resposta for não, aplicar a **garantia de qualidade** (R4).

#### R3. Check-in mensal
1. Na semana anterior, conferir na plataforma os 3 números do mês.
2. Planejador marca o horário (**o cliente não precisa lembrar**).
3. 30 min: o que aconteceu, a 1 decisão do mês e a próxima ação.
4. Registrar no CRM e mandar o "número do mês" no WhatsApp.

#### R4. Reclamação, cancelamento ou garantia
1. Responder em até 1 dia útil, sem discutir.
2. **Cancelamento:** o cliente faz pelo site, sem multa. Confirmar por escrito e perguntar o motivo (uma pergunta só).
3. **Garantia** (atraso ou plano genérico): devolver 100% do diagnóstico em até 7 dias.
4. Registrar o motivo numa planilha de motivos de cancelamento, revisada todo mês.
5. Reclamação pública (Reclame Aqui, Google): responder em público em até 2 dias úteis e resolver no privado.

#### R5. Fechamento do mês
1. Exportar os recebimentos do gateway e conferir os inadimplentes.
2. Calcular os 20% de cada planejador por cliente pago.
3. Contar os acessos ativos na plataforma contra o limite de 400.
4. Mandar os documentos ao contador.
5. Atualizar os indicadores: clientes ativos, novos, cancelados, diagnósticos e conversão.

### 5. Ferramentas (stack mínima)

| função | ferramenta | por quê |
|---|---|---|
| Planejamento, gastos e metas | Dashplan | já contratado |
| Cobrança recorrente e Pix | Asaas (ou similar) | recorrência e cartão, Pix e boleto num lugar só |
| Contratos | ZapSign (ou Clicksign) | contrato e termo de LGPD em minutos |
| Agenda | Google Agenda / Calendly | sessão do casal e check-ins |
| Atendimento | WhatsApp Business | onde o cliente já está |
| CRM | planilha no início; um CRM simples a partir de ~50 clientes | prazos de 15 dias e histórico |
| Contabilidade | contador | regime, notas, repasses |

### 6. Licenças, registros e seguros (checklist)

| item | o que é | onde confirmar |
|---|---|---|
| CNPJ e registro na Junta | abrir a empresa | [Redesim (gov.br)](https://www.gov.br/empresas-e-negocios/pt-br/redesim) e JucisRS |
| **CNAE e anexo do Simples** | define o imposto (Anexo III ou V; o V parte de 15,5%, segundo fontes contábeis) | Contador e [Portal do Simples Nacional](https://www8.receita.fazenda.gov.br/simplesnacional/). O CFO usou 11%, o que **pode estar baixo** se cair no Anexo V |
| Inscrição municipal, ISS e alvará em Porto Alegre | prestação de serviço na cidade | [Prefeitura de Porto Alegre](https://prefeitura.poa.br) (licenciamento) |
| **Enquadramento na CVM** | A Res. CVM 19 **não se aplica** a quem atua *exclusivamente* como planejador (sucessão, previdência, finanças gerais) **sem recomendar investimentos**. Se o planejador recomendar ativos ou classes de ativos, precisa de **registro de consultor de valores mobiliários** | [Res. CVM 19 consolidada](https://conteudo.cvm.gov.br/export/sites/cvm/legislacao/resolucoes/anexos/001/resol019consolid.pdf). **Decidir antes de lançar** e alinhar o contrato e o marketing |
| "Sem comissão" | só pode ser dito se for verdade, inclusive para os planejadores parceiros | contrato com planejadores |
| LGPD | contrato, termo de consentimento, quem é o encarregado, segurança dos extratos | [ANPD](https://www.gov.br/anpd) |
| Código de Defesa do Consumidor | direito de arrependimento de 7 dias em vendas online (art. 49); informação clara sobre cancelamento | [CDC](https://www.planalto.gov.br/ccivil_03/leis/l8078compilado.htm) |
| Certificação CFP (opcional) | credencial que o painel valorizou | [Planejar](https://planejar.org.br) |
| Seguro de RC profissional | erro ou omissão em orientação | corretora; ver fornecedores |

### 7. Registro de riscos

| # | risco | prob. | impacto | plano |
|---|---|---|---|---|
| 1 | **Clientes chegam devagar e o caixa acaba no mês ~5** (CFO) | alta | crítico | Pré-venda da turma fundadora antes de ligar os fixos; CEO a R$ 5 mil até o break-even; checar a meta de clientes novos por semana |
| 2 | **Dashplan falha** (lentidão, duplicação) ou sobe o preço | média | alto | SLA por escrito; exportação de dados garantida; plano B de planilha para o mês corrente; o planejador avisa o cliente antes que ele perceba |
| 3 | Planejador sai ou adoece | média | alto | Histórico de cada cliente no CRM; planos num formato padrão; segundo planejador treinado a partir de ~60 clientes |
| 4 | Tempo por cliente passa de 50 min e o planejador fica mal pago com 20% | alta | médio | Medir o tempo nos 10 primeiros clientes; padronizar os 3 números; WhatsApp em blocos de horário |
| 5 | Problema com a CVM por recomendar investimento sem registro | média | crítico | Decidir o escopo antes do lançamento; treinar a equipe; revisar o texto de marketing |
| 6 | Vazamento de dados financeiros dos clientes | baixa | crítico | Acesso mínimo; nada de extrato no WhatsApp pessoal; termo de LGPD; senhas e 2FA |
| 7 | Reclamação pública (Reclame Aqui) logo no início | média | alto | R4; responder rápido; cancelamento fácil já evita o motivo nº 1 do setor |
| 8 | Plano "genérico" e muitas devoluções da garantia | média | médio | Revisão por um segundo par de olhos (R2); amostragem semanal |
| 9 | Inadimplência na mensalidade | média | médio | Cartão recorrente como padrão; lembrete automático; pausa do acesso após 15 dias |
| 10 | Imposto maior que o estimado (Anexo V em vez de III) | média | médio | Contador define antes da abertura; re-rodar o CFO com a alíquota real |

### Perguntas em aberto

1. O planejador vai **recomendar investimentos**? Se sim, quem tem registro de consultor na CVM?
2. Planejadores: **sócios, PJ ou CLT**? E o "talvez fixo"?
3. Contrato da Dashplan: SLA, marca própria, exportação de dados e multa de saída.
4. Gateway: taxa de cartão real.
5. Contador: CNAE e anexo do Simples.

Próximo: `/founder-launch`.

## Launch plan

Hoje: **sexta, 09/10/2026**. Datas abaixo são a proposta mais cedo realista. Ajuste se tiver uma data-alvo. Base: `cfo.md` (v4), `ops.md`, `offer.md`, `pricing.md`. **`brand.md` e `marketing.md` ainda não existem** (as etapas foram interrompidas); as tarefas de marca e marketing estão no cronograma como mínimo viável.

### 1. O teste antes de gastar: pré-venda da turma fundadora

**Por que primeiro:** o CFO mostra que, com R$ 18.900/mês de fixos, a rampa lenta queima os R$ 100 mil até o mês ~5. **Não ligar o adiantamento do CEO de R$ 10 mil, nem marketing pago, antes deste teste.**

**O teste (4 semanas, 12/10 → 08/11):**
- **Oferta:** Diagnóstico Financeiro **pago antecipadamente**, com a sessão do casal, o raio-X do banco e o plano escrito em 15 dias. Preço **R$ 297** para metade dos contatos e **R$ 197** para a outra metade, para testar os dois preços do `pricing.md`. Inclui a vaga na turma fundadora: Acompanhamento a R$ 297/mês (R$ 390 no Profissional) com preço travado por 12 meses, sem fidelidade.
- **Canal:** só a **rede dos sócios** e indicação (WhatsApp, LinkedIn, contatos do mercado financeiro), mais **uma landing page** com o preço e um botão de pagamento. Sem anúncios pagos.
- **Público prioritário:** profissionais liberais de alta renda e casais. Foram os dois perfis que compraram no painel v2 e são o nicho do conselho.

**Linha de sucesso (escrita antes de rodar):**

| métrica | sucesso | ajustar | parar e repensar |
|---|---:|---:|---:|
| Diagnósticos **pagos** em 4 semanas | **≥ 20** | 10–19 | < 10 |
| Conversão de diagnóstico em Acompanhamento (medida até 30 dias após a entrega) | **≥ 50%** | 30–49% | < 30% |
| Pedidos de garantia ("plano genérico") | ≤ 10% | 10–20% | > 20% |
| Tempo real por diagnóstico | ≤ 4 h | 4–6 h | > 6 h |

**Comparação com o painel:** o painel v2 comprou o diagnóstico a 10% (2 de 20). Se a taxa real de quem recebe a oferta e paga ficar **bem abaixo de 10%**, acredite nos compradores reais e volte para `/founder-offer` ou `/founder-pricing`. Para medir isso, conte quantas pessoas receberam a oferta.

**Por que 20:** o CFO precisa de ~10 clientes novos por mês para caber nos R$ 100 mil. Com 50% de conversão, 20 diagnósticos dão os ~10 primeiros assinantes.

### 2. Cronograma

Responsáveis: **CEO** = sócio que toca o negócio; **PLAN** = planejador(es); **CONT** = contador; **JUR** = advogado.

#### Semana 1 (12–16/10): decisões que travam tudo ⚠️ caminho crítico
- [ ] ⚠️ **Escopo CVM:** o planejador vai ou não recomendar investimentos? Se sim, quem tem registro de consultor? (CEO + JUR, até 14/10)
- [ ] ⚠️ **CNPJ:** existe um CNPJ dos sócios que possa faturar já, ou é preciso abrir? Pedir ao contador CNAE, anexo do Simples e prazo de abertura (CEO + CONT, até 16/10)
- [ ] ⚠️ **Contrato do diagnóstico + termos de cancelamento, garantia e LGPD** (JUR, até 23/10)
- [ ] Confirmar que "sem comissão" é verdade para todos os planejadores (CEO, 14/10)
- [ ] Dashplan: pedir SLA, marca própria, exportação de dados e regra de saída (CEO, 16/10)
- [ ] Gateway (Asaas ou similar): abrir conta e confirmar a taxa de cartão (CEO, 16/10)
- [ ] Lista de 100 nomes da rede, priorizando profissionais liberais e casais (CEO, 16/10)

#### Semana 2 (19–23/10): pré-venda no ar
- [ ] Nome provisório + landing page com preço, o que inclui, prazo de 15 dias, garantia, "sem fidelidade" e "sem comissão" se verdade (CEO, 21/10)
- [ ] Plano exemplo anonimizado. Pode ser de um sócio ou de um conhecido, **com autorização** (PLAN, 21/10)
- [ ] Mensagem pessoal para os 100 nomes. Metade com R$ 197, metade com R$ 297. Registrar quem recebeu o quê (CEO, a partir de 22/10)
- [ ] ZapSign e modelo do contrato funcionando (CEO, 23/10)

#### Semanas 3–4 (26/10–08/11): vender e entregar os primeiros
- [ ] Seguir com quem respondeu, com no máximo 2 lembretes (CEO)
- [ ] Rodar a rotina R1 → sessão do casal → R2 nos primeiros pagantes (PLAN)
- [ ] **Cronometrar** horas por diagnóstico e medir o que o cliente realmente usa (PLAN)
- [ ] Pedir 3 indicações a cada cliente que gostar da entrega (PLAN)

#### 09/11 (segunda): ⚠️ decisão de seguir
Comparar com a linha de sucesso. **Só se estiver em "sucesso" ou "ajustar":**
- ligar o adiantamento do CEO, **começando por R$ 5 mil até o break-even** (recomendação do CFO);
- aprovar a verba de marketing de R$ 3 mil/mês.

#### Semanas 6–7 (09–20/11): preparar o lançamento público
- [ ] Marca mínima: nome final (checar INPI classe 36, domínio .com.br e @), logo simples, cores (CEO; rodar `/founder-brand`)
- [ ] Posicionamento e 10 ganchos, incluindo "quanto você gastou de iFood este ano?" e "pare de brigar por dinheiro" (CEO; rodar `/founder-marketing`)
- [ ] Instagram com 9 posts antes do lançamento: plano exemplo, bastidores, "como funciona a sessão do casal" (CEO)
- [ ] 2–3 parcerias de indicação, como contadores de profissionais liberais (CEO)
- [ ] Treinar os planejadores nas rotinas R1–R5 de `ops.md` (PLAN)
- [ ] Seguro de RC profissional cotado e contratado (CEO)

#### Lançamento suave: segunda 16/11
Diagnósticos dos clientes da pré-venda em andamento; primeiras assinaturas de Acompanhamento cobradas; tudo rodando com clientes reais antes de abrir ao público.

#### Lançamento público: **segunda 23/11/2026**
Turma fundadora aberta ao público até **31/01/2027** ou até completar 30 vagas. As vagas da pré-venda contam.

**Caminho crítico:** escopo CVM → CNPJ e gateway → contrato → landing page → pré-venda → decisão de 09/11. Um atraso em qualquer um empurra tudo.

### 3. Dia do lançamento: segunda, 23/11

| hora | quem | o quê |
|---|---|---|
| 08:00 | CEO | Conferir landing page, botão de pagamento (fazer uma compra de teste de R$ 1 e estornar) e agenda aberta |
| 08:30 | PLAN | Agenda da semana com espaço para ≥ 5 sessões do casal |
| 09:00 | CEO | Post de lançamento no Instagram, com o plano exemplo e "o que você recebe em 15 dias" |
| 09:30 | CEO | Mensagem pessoal para a rede (2ª onda) e parceiros, com um link por parceiro para medir a origem |
| 10:00 | CEO | Story: "como funciona a sessão do casal" |
| 12:00 | CEO | Responder todos os leads da manhã (meta: até 4 h úteis) |
| 14:00 | PLAN | Atender os clientes da pré-venda normalmente. O lançamento não pode atrasar entregas |
| 17:00 | CEO | Contar visitas, pagamentos e mensagens do dia; anotar a origem de cada um |
| 18:00 | todos | 15 min: o que travou, o que mudar amanhã |

**Se algo quebrar** (de `ops.md`):
- **Pagamento falha:** enviar link de Pix manual pelo gateway e registrar.
- **Dashplan fora do ar:** seguir com o diagnóstico em planilha padrão e avisar o cliente antes que ele perceba.
- **Reclamação pública:** rotina R4, responder em até 2 dias úteis.

### 4. Os primeiros 30 dias (23/11 → 23/12)

**Números da semana:**

| número | meta | sinal para mudar |
|---|---|---|
| Clientes de Acompanhamento ativos | caminho para 98 (break-even a R$ 297) | menos de 10 novos no mês |
| Diagnósticos pagos por semana | ≥ 5 | < 3 por 2 semanas seguidas |
| Conversão de diagnóstico em assinatura | ≥ 50% | < 30% |
| Custo por diagnóstico vindo de anúncio (quando ligar) | ≤ R$ 150 (estimativa até haver dados) | > R$ 300 |
| Tempo do planejador por cliente-mês | ≤ 50 min | > 75 min |
| Cancelamentos | ≤ 1 a cada 20 clientes por mês | > 2 a cada 20 |

**Custo máximo para ganhar um cliente** (do CFO): cada assinante deixa ~R$ 195/mês e cada diagnóstico a R$ 297 deixa ~R$ 195. Para recuperar o custo em 3 meses, pode-se gastar até ~**R$ 780 por assinante** (1 diagnóstico + 3 mensalidades). Com 50% de conversão, isso equivale a até **~R$ 390 por diagnóstico vendido**. São estimativas a confirmar com a retenção real.

**Revisões:**
- **Dia 7 (30/11):** algum canal trouxe zero? A landing page converte? Os diagnósticos estão saindo em ≤ 15 dias?
- **Dia 14 (07/12):** a conversão de diagnóstico em assinatura está acima de 30%? Qual preço de diagnóstico (R$ 197 ou R$ 297) teve mais vendas **e** mais assinaturas depois? O tempo por cliente está em 50 min?
- **Dia 30 (23/12):** o ritmo cabe nos R$ 100 mil segundo o CFO (~10 novos/mês)? **Re-rodar `/founder-cfo` com os números reais** (rampa, taxa do gateway, imposto do contador). Manter, cortar ou subir o marketing pago? Preço final do diagnóstico.

Próximo: `/founder-plan`.

## Not done yet

- Marketing: run /founder-marketing
- Brand: run /founder-brand

_The panel is simulated buyers and the numbers are projections from your inputs. Confirm demand with real customers and costs with real quotes before you spend. Not financial, legal or tax advice._

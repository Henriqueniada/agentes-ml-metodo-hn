# Ads — Métricas, fórmulas e diagnóstico de CTR/conversão

Assuntos: métricas primárias (faturamento, receita, investimento); ACOS e ROAS; TACOS e ROI; margem de contribuição bruta x realizada; contribuição publicitária e aporte publicitário; atalho de conversão entre ACOS/ROAS/TACOS/ROI; métricas do painel (impressões, cliques, visitas, vendas); CTR, CVR (conversão), CPC e CPA; vitrine (CTR) x interior do anúncio (conversão); leilão de Ads, Ads Rank e Ads Score; produto novo e Ads; conta dependente de Ads e "detox"; ruptura e Ads Rank; Ads group (MLBU); leitura de variação de métricas sem calcular; regra "ACOS dividido por 2 maior que TACOS"; orçamento e ROAS objetivo em dia de pico; ROAS objetivo em fim de semana.

## Como usar as métricas (ideia geral)

A leitura de Ads é matemática aplicada. Use duas telas da conta do Mercado Livre: Métricas (vendas brutas, visitas) e Publicidade (Product Ads). O objetivo é saber o que cada métrica significa, não decorar números absolutos. Para qualquer análise, olhe sempre três janelas de tempo, 30, 15 e 7 dias, para ver a cadência: se a métrica está melhorando, piorando, acelerando ou perdendo tração. Uma olhada semanal (por exemplo, toda segunda-feira, com horário fixo na agenda) nas métricas de 30, 15 e 7 dias já dá uma boa noção; não é necessário mexer nas campanhas todo dia, mas em dias de pico vale acompanhar o dia inteiro.

## As três métricas primárias

Toda análise de Ads parte de três números, as "cores primárias" das quais se misturam as demais métricas:

- **Faturamento total:** vendas brutas da conta inteira, vindas de publicidade e de orgânico. Aparece como "vendas brutas" na tela de Métricas.
- **Receita (faturamento publicitário):** só o faturamento que veio por publicidade, ou seja, vendas em que a pessoa passou pelo anúncio patrocinado antes de comprar. Aparece como "receita" dentro do painel de Product Ads.
- **Investimento:** quanto foi gasto em publicidade. Prefere-se chamar de investimento (ou orçamento) em vez de "gasto", porque o dinheiro é colocado para gerar retorno posterior.

Atenção: receita e faturamento não são a mesma coisa. Receita = só Ads. Faturamento = Ads + orgânico.

## ACOS e ROAS

**ACOS** (Advertising Cost of Sales) é a eficiência publicitária: quanto da receita de Ads foi investido.

- Fórmula: ACOS = (investimento ÷ receita) × 100. O "× 100" serve só para transformar em percentual.
- Quanto menor o ACOS, mais eficiente a publicidade; quanto maior, menos eficiente. ACOS baixando é ganho de eficiência; ACOS subindo é perda de eficiência.
- Exemplo: vendeu 100 reais com 10% de ACOS, então foram investidos 10 reais.
- Se o investimento é o mesmo e a receita aumenta, o ACOS cai (a comparação vale para o mesmo produto e o mesmo investimento).

**ROAS** mede a mesma eficiência olhando para o outro lado (quanto voltou para cada real colocado).

- Fórmula: ROAS = receita ÷ investimento. Não se multiplica por 100; é um fator de multiplicação (por isso aparece como "5x", "10x").
- Exemplos: ACOS de 10% = ROAS de 10; ACOS de 20% = ROAS de 5 (colocou 20, voltaram 100). Receita = ROAS × investimento.
- Regra mental: quando o resultado é percentual (ACOS, TACOS), é parte pelo todo (número menor sobre o maior, depois × 100). Quando é fator de multiplicação (ROAS, ROI), é o maior sobre o menor. Cuidado: se investir 200 e vender 30, o ROAS será menor que 1 (por exemplo, 0,72) e o ACOS passará de 100%, o que significa prejuízo direto na campanha.

Em Product Ads a campanha é configurada por ROAS objetivo (antes era por ACOS objetivo). Colocar ROAS objetivo é dizer quanto se quer receber de volta para cada real investido; é o mesmo número do ACOS visto ao contrário (ACOS objetivo de 10% equivale a ROAS objetivo de 10).

## TACOS e ROI

**TACOS** (Total Advertising Cost of Sales) usa o investimento sobre o **faturamento total**, não só sobre a receita de Ads.

- Fórmula: TACOS = (investimento ÷ faturamento total) × 100.
- ACOS olha eficiência publicitária (só Ads). TACOS olha eficiência financeira, porque o percentual do TACOS bate diretamente na margem.
- **ROI** é o par do TACOS: ROI = faturamento total ÷ investimento (fator de multiplicação, como o ROAS).

### Relação do TACOS com a margem

Do faturamento bruto desconta-se frete, devolução, imposto, custo do produto e tarifas do marketplace; o que sobra é a **margem de contribuição bruta** (em %). Depois se desconta o investimento em Ads, que em percentual é o TACOS, e chega-se na **margem de contribuição realizada (ou líquida)**. Dela saem então os custos fixos.

- Margem de contribuição realizada = margem de contribuição bruta − TACOS.
- Exemplo 1: margem bruta de 17% e TACOS de 3% resultam em 14% de margem realizada.
- Exemplo 2: margem bruta de 12% e TACOS de 4% resultam em 8% realizada.
- Exemplo 3: margem bruta de 15% e TACOS de 5% deixam 10% de margem realizada.

## Atalho de conversão entre ACOS, ROAS, TACOS e ROI

Basta fazer 100 dividido pela outra métrica.

- 100 ÷ ROAS = ACOS; 100 ÷ ACOS = ROAS.
- 100 ÷ ROI = TACOS; 100 ÷ TACOS = ROI.
- Exemplos: ACOS de 25% → 100 ÷ 25 = ROAS 4. ROAS de 50 → 100 ÷ 50 = ACOS de 2%.

## Contribuição publicitária e aporte publicitário

**Contribuição publicitária** é a relação entre receita (Ads) e faturamento total: quanto das vendas da conta veio de publicidade.

- Fórmula: contribuição publicitária = (receita de Ads ÷ faturamento total) × 100. Cuidado com a ordem: é receita por faturamento (se inverter, dá número menor e errado).
- Exemplo: faturamento de 100 mil, dos quais 37 mil vieram de Ads, resulta em 37%. Se 72 mil vieram de Ads, 72% já é valor alto.
- Referência (não é regra rígida, depende do momento e do objetivo): trabalhar na faixa de **30 a 40% nos períodos normais**. Para acelerar, há margem para chegar perto de **50%** e ainda ser saudável.
- **Acima de 50%** é sinal de alerta: dependência publicitária e risco de **canibalização** (o anúncio passa a aparecer mais por Ads do que organicamente e a conta paga por vendas que já aconteceriam de graça).
- **Muito abaixo disso** (15% a 20%, ou 10%): provavelmente há dinheiro na mesa; existe espaço para investir um pouco mais e vender mais.
- Vender só com Ads, mesmo com ACOS e TACOS baixos, quase nunca faz sentido. "Aumentar o valor de Ads" significa trazer mais receita por Ads, e não simplesmente gastar mais: investir mais sem vender mais piora ACOS e TACOS.
- Se a contribuição está alta num período curto (por exemplo, 7 dias) mas normal em 30 dias, pode ser que o orgânico tenha vendido menos naquela semana; por isso a leitura em 30, 15 e 7 dias.

**Aporte publicitário** é um indicador que aparece logo abaixo do gráfico principal na tela de Product Ads. Ele considera só os anúncios que estão em campanha. Se todos os anúncios da conta estão em Product Ads, aporte e contribuição são iguais. Se há anúncios vendendo fora de campanha, o aporte publicitário fica **igual ou maior** que a contribuição publicitária (nunca menor). Exemplo: aporte de 63% pode corresponder a contribuição de 50%, mas não existe aporte de 40% com contribuição de 53%.

## As métricas do painel: impressões, cliques, visitas e vendas

Fora as métricas calculadas (ACOS, ROAS, TACOS, ROI, CTR, conversão, contribuição), o painel traz métricas "cruas", resumidas em três fatores: **quem viu (impressões), quem clicou/visitou (cliques e visitas) e quem comprou (vendas)**.

- **Impressão:** toda vez que alguém viu o anúncio patrocinado. (Alcance seria a quantidade de pessoas; impressões, a quantidade de vezes que foi visto. A relação entre os dois é a frequência, que não se usa em Product Ads.)
- **Cliques:** toda vez que alguém clicou no anúncio **patrocinado**. Fica no painel de Product Ads. Podem ser chamados de "visitas publicitárias".
- **Visitas:** toda vez que alguém entrou no anúncio, vindo de Ads **ou** de orgânico. Fica na tela de Métricas (junto de vendas brutas, unidades vendidas e ticket médio por unidade). A relação cliques x visitas é a mesma de receita x faturamento: um é só Ads, o outro é Ads + orgânico.
- **Vendas atribuídas (antes "vendas por Product Ads"):** compras que vieram pela publicidade.
- **Outras vendas (antes "vendas sem Product Ads"):** compras que vieram sem publicidade, inclusive de forma orgânica. Dentro do painel de Product Ads, "outras vendas" considera só anúncios que estão em campanha; venda de anúncio fora de campanha não aparece nesse painel. Exemplo: 50 vendas na conta, 10 delas de um anúncio sem campanha; o painel mostra 30 orgânicas + 10 de Ads e a soma (40) não bate com as 50 reais. Para olhar a conta inteira, use a tela de Métricas.
- **Quantidade vendida x unidades vendidas:** quantidade vendida conta vendas (pedidos); unidades vendidas conta itens. Uma venda pode ter três unidades.
- Se uma pessoa compra a versão orgânica de um anúncio que está patrocinado (sem ter vindo pelo anúncio patrocinado), a venda conta como orgânica, não como Ads.

## CTR, conversão (CVR), CPC e CPA

**CTR** (taxa de cliques): de todos que viram o anúncio, quantos clicaram.
- Fórmula: CTR = (cliques ÷ impressões) × 100. Exemplo: 100 impressões e 15 cliques = 15%.
- Em Ads usa-se cliques ÷ impressões; também dá para calcular um CTR geral da conta (visitas ÷ impressões totais), mas o foco é o da publicidade.

**CVR (taxa de conversão):** de todos que clicaram, quantos compraram. Existem três formas:
- Conversão de Ads = vendas atribuídas ÷ cliques.
- Conversão total da conta = quantidade de vendas ÷ visitas.
- Conversão orgânica = (vendas totais − vendas de Ads) ÷ (visitas − cliques).
- A conversão total é uma média ponderada das outras duas: se Ads converte mais, o orgânico converte menos, e vice-versa.

**CPC** é custo por clique (investimento ÷ cliques) e **CPA** é custo por aquisição (investimento ÷ vendas). Em marketplace usa-se mais ACOS/ROAS do que CPA; ACOS e CPA são parentes: um olha o valor em reais, o outro a quantidade de vendas.

### Valores de referência

- **Não existe CTR ou CVR "ideal" universal.** Depende da categoria. Em algumas, 1% de CTR já é ótimo; em outras, 12% é pouco. Produto de desejo x produto de necessidade, e produtos com muita variação (moda, cortina, persiana, tapete) costumam ter CTR mais baixo.
- Para ter base de conversão, olhe o **painel de tendências/análise de concorrência do Mercado Livre**: nos 50 maiores da categoria dá para ver a taxa de conversão dos concorrentes e saber se a conta está muito dentro ou muito fora.
- O foco é sempre melhorar a métrica, não bater um número fixo.

### Como interpretar conversão de Ads x conversão total

- Conversão total de 6% com conversão de Ads de 9% indica que Ads converte bem. Se a contribuição publicitária também é alta, pode haver canibalização: o anúncio vende mais por Ads e converte melhor em Ads simplesmente porque aparece mais em Ads. Se a contribuição é baixa, talvez o orgânico esteja escondido e, ao aparecer por Ads (mais bem posicionado), converte mais rápido; então faz sentido acelerar Ads.
- Exemplo: a conversão de Ads caía porque, sempre que o anúncio aparecia em Ads, aparecia ao lado de concorrentes queimando preço, em um lugar em que ele não deveria estar competindo. O posicionamento orgânico, com as palavras-chave certas, tinha concorrentes com preço pior e conversão maior. Por isso compare sempre a conversão de Ads com a conversão total e com a contribuição publicitária.

## Diagnóstico: vitrine (CTR) x interior do anúncio (conversão)

Analogia: o CTR é a vitrine (de todos que passaram na frente, quantos entraram); a conversão é o interior da loja (de todos que entraram, quantos foram ao caixa). Se o problema é CTR, mexer no que está dentro do anúncio não resolve; se o problema é conversão, mexer na vitrine também não.

**Quando o CTR está baixo ou caindo, otimizar a vitrine (o que aparece sem entrar no anúncio):**
- Imagem de capa (a primeira foto é o principal fator de CTR; atenção à regra de não trocar capa de produto curva A sem critério).
- Título.
- Preço.
- Full (atrai, tanto que existe filtro de Full na busca).
- Promoção e cupom visíveis, oferta por atacado/negócios (preço mais barato para negócios ajuda).
- Nota das avaliações (as estrelinhas). A **nota** ajuda no CTR, mas o **texto** das avaliações só é visto por quem já entrou, então afeta conversão.
- Descrição e ficha técnica **não** influenciam CTR (só quem está dentro vê). Título sim.

**Quando a conversão está baixa, otimizar o interior do anúncio:**
- Clips e demais imagens (da segunda em diante).
- Ficha técnica.
- Descrição.
- Texto das avaliações.
- Preço e desconto por quantidade também ajudam na conversão.
- Caso típico de avaliação: nota alta (4,8 ou 4,9) atrai clique, mas os comentários dizem "bonito, mas é pequeno, achei que fosse maior". O CTR segue bom, mas a conversão não sobe: é problema de expectativa/comunicação dentro do anúncio (tamanho, medidas), não de vitrine.

Conclusão: a função da publicidade é só entregar impressão. Se clica e se compra depende, em grande parte, da otimização orgânica do anúncio.

## Como funciona o leilão de Ads (por que produto novo não deve entrar direto em Ads)

**Dúvida comum:** em muitos nichos a estratégia é preço baixo (zero a zero) para vender e ranquear. A partir de que momento se começa a ganhar leilão em Ads mesmo sem vendas? Quanto o preço pesa para o CTR? O concorrente tem mais de mil avaliações e preço mais alto, mas está mais bem posicionado.

**Resposta:** não faz sentido lançar produto novo já acelerando em Ads. O leilão não olha somente quanto o vendedor aceita pagar (ROAS ou ACOS objetivo). O algoritmo considera a **reputação e a credibilidade da oferta**. Quando o consumidor compra, a reputação em jogo é a da plataforma; por isso o Mercado Livre prefere dar espaço a quem tem oferta validada, produto bom e pós-venda bom, mesmo que essa pessoa pague menos pelo clique, do que a alguém que só aceita pagar mais para aparecer. Um produto novo, com zero venda, não tem oferta validada: a plataforma não sabe se o produto é original, se entrega bem, se o pós-venda é bom. Para aparecer, ele teria de pagar muito mais que um concorrente com histórico, e o Ads ficaria caríssimo. Exemplo: dois vendedores do mesmo produto; um falsificado oferece 10 reais por venda, outro com produto original e nota fiscal paga 7,50; a plataforma tende a escolher o que protege a reputação.

O **Ads Rank** (ranking do anúncio nos leilões) é formado pelo desempenho do anúncio e pela pontuação (**Ads Score**) de toda a conta, e não só pelo valor do lance. Mesmo que um concorrente queira pagar mais, o Mercado Livre pode mostrar o anúncio com melhor oferta (por exemplo, lance menor, mas com kit extra e recompra).

**Recomendação para produto novo:** validar a oferta primeiro no orgânico e só depois ligar Ads.
- Com o anúncio "aquecido" (vendas, conversão, posição orgânica), ao ligar Ads ele roda mais barato.
- Anúncio novo que já entra com Ads agressivo faz a plataforma aprender a dependência; evitar.

## Conta dependente de Ads e "detox"

**Dúvida comum:** uma conta vendeu bem com poucos produtos de forma orgânica. Depois de ligar Ads, sente que só vende com Ads: todo produto novo só vende se ligar Ads, e não consegue mais escalar organicamente. Deve desligar tudo?

**Resposta:** a dependência publicitária também acontece com anúncio novo. A conta se "vicia": sempre que cria um anúncio e liga Ads, a plataforma aprende que ele só vende com Ads. A solução não é desligar completamente o Ads, e sim **enxugar o Ads** e fazer uma estratégia orgânica forte para posicionar os anúncios, até que Ads represente pouco da conta. Não é de um dia para outro: é um "detox" gradual. Anúncio recém-enviado ao Full demora até ter desempenho; é normal aparecer com "desempenho ruim" logo no início, sem dados.

## Produto que ficou sem estoque (ruptura longa) e Ads Rank

**Dúvida comum:** um produto que era dos mais vendidos ficou quatro meses sem estoque e tem muitas avaliações. Ao voltar, ele se comporta como produto novo?

**Resposta:** não há garantia, só testando. Se o produto é **sazonal**, pode ficar um ano parado e voltar a funcionar quando religar. Se **não é sazonal** e vendia mês após mês, ao ficar quatro meses sem vender o ranking dele (Ads Rank) se perdeu. Vale tentar reativar com um volume pequeno para validar, porque aproveita vendas e avaliações acumuladas; com pouco concorrente e preço já agressivo, ele pode retomar. Mas muitas vezes **criar um anúncio do zero leva menos tempo para voltar a vender** do que reativar um anúncio que passou quatro meses em ruptura.

## MLBU e Ads group

MLB é o ID do anúncio; MLBU (user product) é o novo formato de anúncio, hoje padrão em anúncios criados. Em Ads, o ponto relevante é que as variações ficam agrupadas no mesmo **Ads group** (agrupamento de anúncios), o que dificulta a análise, que era melhor em nível de anúncio.

**Dúvida comum:** dá para fazer Ads em apenas uma variação em vez de todas?

**Resposta:** antigamente sim; hoje dificilmente, porque as variações já ficam agrupadas no mesmo Ads group e não há como desagrupar.

## Como ler a variação de métricas sem calcular (numerador e denominador)

Em uma divisão:
- Se o numerador aumenta, o resultado aumenta; se diminui, o resultado diminui.
- Se o denominador aumenta, o resultado diminui; se diminui, o resultado aumenta (relação inversamente proporcional).

Aplicado às métricas:
- **ACOS = investimento ÷ receita (quanto menor, melhor).** Para baixá-lo: aumentar a receita com o mesmo investimento, ou diminuir o investimento mantendo a receita. Se ambos aumentam, **depende da proporção**: se o investimento sobe mais (em proporção) que a receita, o ACOS sobe; se a receita sobe mais, o ACOS cai. Exemplo: investimento de 10 para 20 (dobrou) e receita de 10 para 15 (+50%) faz o ACOS piorar.
- **TACOS = investimento ÷ faturamento (quanto menor, melhor)**, mesma lógica, com o faturamento no denominador.
- **ROAS e ROI (quanto maior, melhor):** melhoram aumentando a receita (ou faturamento) com o mesmo investimento, ou diminuindo o investimento.
- **CTR = cliques ÷ impressões (maior é melhor):** melhora se aumentam os cliques para as mesmas impressões, ou se diminuem as impressões mantendo os cliques. Se cliques e impressões sobem, o que importa é qual subiu mais em proporção: se as impressões subiram mais, o CTR caiu.
- **Conversão = vendas ÷ cliques:** se a quantidade de vendas subiu 10% e a de cliques subiu 25%, a conversão piorou.

**Exercício prático:** na tela de Product Ads, selecionar apenas receita e investimento (tirar ACOS e ROAS do gráfico), comparar 7 dias com os 7 dias anteriores (ou 30 x 15 x 7) e verificar: a receita subiu mais ou menos que o investimento? Se subiu menos (ou caiu mais), o ACOS piorou. A tela já mostra a variação percentual, então não é preciso calcular tudo toda hora, mas é preciso saber a fórmula para entender o que está sendo comparado. ACOS de 15% pode significar margem muito boa ou pagar para vender, dependendo do produto.

## Acompanhar CTR e conversão por anúncio dentro da campanha

Na tela de anúncios da campanha, o CTR e a conversão **não aparecem prontos**. Para saber se o anúncio está melhorando depois de uma otimização:
- Para o CTR: comparar a variação de **cliques** x **impressões** no mesmo período (30, 15, 7 dias). Se os cliques cresceram mais que as impressões, o CTR melhorou; se as impressões cresceram mais, piorou. Se tudo caiu, é preciso que as impressões caiam mais que os cliques para o CTR melhorar.
- Para a conversão: comparar **vendas atribuídas** x **cliques**.
- CTR piorando ao longo de 30, 15 e 7 dias significa que algum concorrente ficou mais atrativo que o anúncio: investigar preço do concorrente, Full, cupom, queda de promoção, etc.
- Quedas pontuais de conversão em fim de semana ou logo depois de mexer na campanha são normais; analisar o período com cuidado.

## Contribuição publicitária por anúncio: regra do "ACOS dividido por 2"

No nível do anúncio dentro da campanha existe a receita, mas não o faturamento total do anúncio, que exigiria abrir outras telas (análise de desempenho). Para evitar esse trabalho, a regra é derivada das fórmulas.

Derivação: ACOS = investimento ÷ receita, logo receita = investimento ÷ ACOS. TACOS = investimento ÷ faturamento, logo faturamento = investimento ÷ TACOS. Contribuição = receita ÷ faturamento = (investimento ÷ ACOS) ÷ (investimento ÷ TACOS) = **TACOS ÷ ACOS**. O investimento se cancela.

Com o teto de 50% de contribuição, a condição é TACOS ÷ ACOS < 0,5, ou seja: **ACOS ÷ 2 deve ser maior que o TACOS** (ou o ACOS tem de ser pelo menos o dobro do TACOS).

Como usar:
1. No anúncio, olhar o ACOS e dividir por 2.
2. Comparar com o TACOS do mesmo anúncio. Se o TACOS está **acima** da metade do ACOS, a contribuição publicitária daquele anúncio passa de 50%: o anúncio depende demais de Ads e precisa de um olhar orgânico urgente.
3. Exemplo: ACOS 7,8% → metade é ~3,9%. TACOS acima de 3,9% significa contribuição acima de 50%; abaixo de 3,9% está ok.
4. Se o ACOS é igual ao TACOS, a contribuição é de 100% (tudo vindo de Ads), o máximo possível. Matematicamente o TACOS não pode ser maior que o ACOS; só pode aparecer assim por venda assistida em casos específicos.

Exemplos:
- ACOS 8,86% e TACOS 6,98%: contribuição altíssima. O ACOS até pode estar bom para a categoria, mas o TACOS de quase 7% está alto: com margem de 15%, 7% foi para Ads e metade da margem foi embora com publicidade.
- ACOS 10,25% e TACOS 6,28%: seria preciso um ACOS de pelo menos 12,5% para ficar ok com esse TACOS; contribuição alta.
- ACOS 4,57% e TACOS 3,67%: também contribuição publicitária alta.
- Quando ACOS e TACOS estão ambos altos (por exemplo ACOS 20,5%), a contribuição pode até estar saudável (30%), mas a eficiência é baixa.

A métrica de 50% serve tanto para a conta como para o anúncio individual. Uma conta pode ter contribuição saudável no total, mas o principal anúncio (curva A) estar ultradependente de Ads, drenando orçamento que faltaria para um anúncio curva B que ranqueia bem. O ajuste para anúncio dependente de Ads é trabalhar o orgânico do anúncio.

## Dia de pico (ex.: 7/7): orçamento e acompanhamento

**Dúvida comum:** a otimização começou no sábado, mas hoje o gasto em Ads subiu assustadoramente. Reduzir? Depois, se aumentar amanhã e baixar depois, isso influencia a campanha?

**Resposta:** não mexer por causa disso na véspera de data comercial. Na véspera há muita busca e pouca conversão: as pessoas pesquisam e clicam, mas esperam o dia da data (cupons) para comprar; a conversão vem no dia seguinte. Gasto muito acima do orçamento destinado (por exemplo, orçamento de 100% e gasto de 400%) pode ocorrer porque o Mercado Livre viu um nível de busca muito alto pelo produto. No dia de pico, a conversão é mais alta e vale trabalhar com **orçamento mais alto e ROAS objetivo mais baixo, de propósito** (também em Black Friday): atrai mais visibilidade e visita e, como a conversão é maior, o ROAS realizado ainda sai bom e o ACOS baixa. Se a conversão estiver boa, aumentar o orçamento e depois baixar não prejudica a campanha.

Cuidados:
- Campanhas de curva C ou de produtos em teste exigem mais cautela. Para campanhas de curva A ou B (produtos que já vendem bem), pode aumentar o investimento e acompanhar durante o dia.
- Acompanhar o dia com filtro "hoje" dentro do Product Ads: olhar às 8h, meio-dia, 16h-18h e 20h, comparando orçamento diário destinado e quanto já foi consumido. Exemplo: orçamento de 20 reais e 18 já consumidos ao meio-dia; subir para 40 para durar o dia todo. O objetivo é não faltar orçamento nas campanhas até o fim do dia.
- Não usar o compartilhamento de orçamento entre campanhas nesse cenário, porque ativa em um dia e desativa no outro; prefere-se acompanhar e aumentar o orçamento manualmente a deixar o Mercado Livre distribuir sozinho.
- No dia de pico, olhar a conversão geral e por anúncio durante o dia todo e comparar com 30, 15 e 7 dias para ver se a conta está performando bem.

## ROAS objetivo em fim de semana

Exemplo: subir o ROAS objetivo das campanhas aos finais de semana (que têm menos tráfego) deixa a campanha mais seletiva e evita gasto à toa, o que pode melhorar as métricas sem perder venda. O caso de referência trabalha com ACOS abaixo de 4% e TACOS em torno de 1,5 a 1,8% (produto de ticket mais alto, acima de R$ 300, com leilão mais seletivo). Em produto novo, validar o orgânico primeiro deixa o Ads mais barato. Trazer tráfego externo (influenciadores e afiliados do Mercado Livre) é uma forma de reduzir a dependência de cliques pagos.

## Resumo das regras e números

- Contribuição publicitária saudável: 30 a 40% em período normal; até cerca de 50% para acelerar; acima de 50% é risco de dependência e canibalização; 15 a 20% ou menos pode significar dinheiro na mesa.
- Regra por anúncio: ACOS ÷ 2 deve ser maior que o TACOS.
- Margem de contribuição realizada = margem de contribuição bruta − TACOS.
- Atalho: 100 ÷ ROAS = ACOS; 100 ÷ ACOS = ROAS; 100 ÷ ROI = TACOS; 100 ÷ TACOS = ROI.
- Analisar sempre em janelas de 30, 15 e 7 dias.
- Problema de CTR: mexer na vitrine (capa, título, preço, Full, cupom, nota). Problema de conversão: mexer no interior do anúncio (clips, fotos secundárias, ficha, descrição, texto das avaliações).
- Produto novo: validar o orgânico antes de ligar Ads; o leilão pesa reputação e oferta validada, não só o lance.
- Conta dependente de Ads: enxugar Ads e fortalecer o orgânico aos poucos (detox).
- Dia de pico: orçamento maior, ROAS objetivo mais baixo, acompanhamento ao longo do dia, sem compartilhar orçamento.

# Ads — auditoria de campanhas de Product Ads, passo a passo

Assuntos: orçamento automático (compartilhado); aporte para publicidade x contribuição publicitária; ROAS objetivo e como subir aos poucos; detratores e promotores pelo ROAS da conta; gráfico de competitividade dos anúncios (impressões ganhas, perda por orçamento e por classificação/Ad Rank); ACOS x TACOS; estrutura de campanhas por curva A/B/C e distribuição 70-20-10; quantidade de anúncios por campanha; ticket e giro; produtos de performance diferente na mesma campanha; catálogo e Ads; produto novo; teto de verba de Ads pela margem; o que o Ads realmente faz; faixa de 0,5% do faturamento; rotina semanal.

## Como usar esta auditoria

Exemplo de conta auditada: dois anúncios sustentam quase metade do faturamento e o restante é diluído em várias campanhas. A auditoria percorre campanha por campanha. Os números citados são de campanhas e anúncios (ROAS, ACOS, orçamento). A mesma análise deve ser feita pelo menos uma vez por semana.

## Ordem de análise de uma conta

1. Olhar a conta inteira: vendas com Product Ads x vendas sem Product Ads, aporte para publicidade e contribuição publicitária.
2. Olhar o ROAS de cada campanha em relação ao ROAS da conta, para achar detratores e promotores.
3. Abrir campanha por campanha (na primeira vez que se mexe na conta, olhar todas), sempre em três janelas: 30, 15 e 7 dias, para ver o fluxo e a tendência. Quem já mexe na conta toda semana pode olhar principalmente os 7 dias.
4. Em cada campanha, abrir o gráfico "Ver a competitividade dos seus anúncios" (logo abaixo do gráfico principal da campanha) para ver quanto se ganha dos leilões e por que se perde.
5. Descer para o nível do anúncio: vendas, cliques, CPC, ROAS, ACOS e TACOS de cada MLB.
6. Decidir: o que é detrator vai sendo limpo, isolado ou removido; o que performa bem é acelerado (ROAS mais alto e orçamento de acordo com a curva).

Lógica de otimização: o que for detrator, vai arrancando e limpando; o que estiver melhor, vê como acelerar.

## Orçamento automático (compartilhado): desligar

- Regra do método: tirar o compartilhamento de orçamento automático. Ele só serve para jogar dinheiro no lixo na maioria das contas.
- O recurso é apresentado pelo próprio Mercado Ads como novidade (orçamento "medidiário"). Só faz sentido em momentos muito específicos e para quem sabe exatamente o que está fazendo (nível avançado), de forma pontual. Deixá-lo ativo direto gera gasto sem sentido.
- Como identificar: nas campanhas aparece um ícone ao lado do valor do orçamento (o "cifrão"). Clique no lápis de editar ao lado do orçamento diário e desative o orçamento automático.
- Por que é pior com ROAS baixo: o Meli aumenta o orçamento para itens que não precisavam de gasto. Com o orçamento compartilhado ligado, ele puxa o orçamento que estava compartilhado entre todas as campanhas e consome tudo; o investimento sobe mesmo com ROAS baixo.
- Exemplo: a campanha principal teve o ROAS objetivo mudado de 10 para 8,33 ao aceitar a recomendação do Mercado Ads. O ROAS realizado foi caindo (entregou cerca de 7 em vez de 8,33), o investimento subiu e a receita caiu; a campanha chegou a ganhar 50% dos leilões com contribuição publicitária de 57%. Conclusão: aceitar a recomendação automática baixou o ROAS justamente na campanha que deveria ter o ROAS mais alto.

## Aporte para publicidade x contribuição publicitária

- Contribuição publicitária olha a conta inteira: receita vinda de Product Ads dividida pelo faturamento total da conta (vendas com e sem Ads).
- Aporte para publicidade olha só o universo dos anúncios que estão em Ads: quanto das vendas desses anúncios veio pela publicidade.
- Os dois só são o mesmo número quando todos os anúncios que vendem estão em campanha. Se há anúncios fora de Ads vendendo organicamente, a contribuição publicitária fica menor que o aporte. A contribuição publicitária nunca é maior que o aporte; no máximo é igual.
- Dentro de uma campanha, aporte e contribuição da campanha são o mesmo número, porque tudo ali está em Ads.
- Exemplo: aporte de 60% nos 30 dias, mas contribuição da conta de cerca de 40 e poucos por cento, porque há produtos fora de Ads vendendo organicamente.
- Faixa de referência: contribuição/aporte na casa de 30% a 40% é bom, até 50% é tranquilo. Acima de 50% é perigoso: é dependência de Ads e sinal de canibalização do orgânico. Perto de 60% já preocupa, principalmente no produto principal (curva A), que deveria ser o mais forte organicamente e não precisar de aporte tão alto.
- Ler a tendência: aporte subindo (por exemplo 77% em 30 dias e 78% em 7 dias) mostra dependência crescendo.
- Contribuição publicitária alta pode ser proposital, por exemplo quando há muito produto de curva sem campanha. Mesmo assim é preciso entender.
- Quando a contribuição está em 90%, a cada 10 vendas 9 vêm de Ads. Esse não é o foco: o foco é fazer o orgânico rodar.

## ROAS objetivo: quanto usar

- Quem vem de outras plataformas de tráfego pago costuma achar que "ROAS 10" é o ideal. A lógica não está errada, mas em Product Ads muitas vezes dá para trabalhar com ROAS acima de 10. Quando a conta está em crescimento e posicionando anúncios, ser mais agressivo (ROAS menor) é estratégia aceitável; depois dá para respirar e subir.
- Faixas de referência, que variam por nicho e posicionamento do anúncio:
  - Curva A: ROAS bem alto, na casa de 20, 25, 30, dependendo do posicionamento. Produtos de marca grande chegam a rodar com ROAS 35 sem perder por classificação. Um produto principal bem posicionado pode rodar com ROAS 20 tranquilamente.
  - Curva B: ROAS intermediário.
  - Curva C: o mais baixo; 9, 10, 11 costuma ser suficiente para teste.
  - Ranquear produto novo: costuma-se começar com ROAS 9 ou 10 e subir aos poucos. Em alguns nichos é preciso começar mais baixo (por exemplo 5) para dar o primeiro empurrão e depois subir.
  - Moda e cosméticos: normalmente precisam de ROAS um pouco mais baixo, porque trabalham com ACOS mais alto. Testar na casa de 8 a 10 e, se não ranquear nem performar, baixar um pouco.
  - Cuidado: já criar campanha com ROAS 5 ou 6 dificulta muito subir depois.
- Quanto melhor o posicionamento do anúncio, maior o ROAS que se consegue trabalhar. Quanto pior o anúncio, mais baixo o ROAS precisa ser para compensar.
- ROAS objetivo muito baixo (5, 7 ou até 8,33) em campanha de produto já validado "não faz sentido". ROAS 8,33 só se justificaria num produto que se quer escalar demais, como um curva A que está sendo acelerado.

### Como subir o ROAS (movimento gradual)

- Subir de pouco em pouco. Exemplo: subir 1 ponto de ROAS hoje, esperar até quinta ou sexta e ver como rodou; se não houver queda, subir mais 1, e assim por diante.
- Intervalo entre mudanças: ideal em torno de 7 dias de janela de atribuição. Se as mudanças são de 1 em 1 ponto, pode mexer a cada 4 ou 5 dias. Se for mexer 2 pontos de uma vez, esperar cerca de 10 dias antes da próxima mexida.
- Se o produto é o curva A principal e não se pode perder venda, o movimento deve ser ainda mais gradual. Se é um produto que já roda bem, dá para ser um pouco mais agressivo.
- Exemplo: campanha com ROAS objetivo 8,33 e realizado 7. Recomendação cautelosa: voltar pelo menos para 10, esperar uma semana, se a performance não caiu subir para 12 e assim sucessivamente. Um perfil mais agressivo subiria de uma vez, mas o caminho gradual é o recomendado.
- Para campanha com contribuição alta demais (exemplo: produto de moda com 75% de aporte e perdendo 68% por classificação): ganhar menos leilões. Subir o ROAS aos poucos e, enquanto isso, fortalecer o orgânico fora do Ads.

## Detratores e promotores: o teste rápido do ROAS

- Compare o ROAS de cada campanha com o ROAS da conta no mesmo período (ele aparece no topo da tela de Ads).
- Campanha com ROAS acima do da conta é promotora. Campanha abaixo é detratora.
- Exemplo: ROAS da conta nos últimos 7 dias de 6,54. Quase todas as campanhas ficavam acima; a única detratora tinha ROAS 2,56, puxava a métrica da conta para baixo e seria atacada primeiro.
- Atenção: o ROAS mostrado pelo Meli pode ser enganoso (falso positivo). Um ROAS que parece bom pode ser causado por um único dia de pico de vendas, enquanto vários dias têm ROAS praticamente zero. Sempre olhar o gráfico dia a dia e pegar janelas maiores, sem confiar só no número agregado nem num dia isolado.
- Evitar julgar por 1 dia: um dia pode ter ROAS 190 e distorcer a imagem completamente.

## Gráfico de competitividade: leilões ganhos e perdas

Local: dentro da campanha, logo abaixo do gráfico principal, "Ver a competitividade dos seus anúncios". É onde está o ouro da análise.

- Mostra quanto os anúncios foram exibidos (leilões ganhos) e as perdas por dois motivos:
  - Perda por orçamento ("não foram exibidos por falta de orçamento", em inglês lost impression share by budget). Está ligada ao investimento da campanha.
  - Perda por classificação (em inglês lost impression share by rank, ligada ao Ad Rank). Ligada à qualidade do anúncio/oferta e ao ROAS (lance) usado.
- Quanto melhor o score do anúncio (Ad Rank), mais barato é disputar leilões. O Mercado Livre dá prioridade a quem leva a plataforma a sério e traz resultado positivo para ela.
- Metas:
  - Não se quer ganhar 100% dos leilões. O recomendado é ganhar na faixa de 30% a 40%, até 50%, que ainda está ok. Ganhar 100% faz a contribuição publicitária ficar muito alta.
  - A perda por orçamento deve ficar zerada na enorme maioria dos casos (cerca de 99%): a campanha deve rodar o dia inteiro, sem acabar o orçamento no meio do dia.
  - Toda a perda restante deve ser por classificação, e de forma saudável: perde-se por classificação porque se trabalha com ROAS alto, não porque o anúncio é ruim.
- Exceção: grandes marcas com ROAS 35 que perdem por orçamento de propósito, porque não querem contribuição publicitária tão alta e não perdem por classificação (anúncio muito bem posicionado).
- Se o anúncio está ruim, perde-se muito por classificação, demora-se mais para ranquear e é preciso compensar trabalhando com ROAS muito baixo. Conversão e CTR baixos obrigam a baixar o ROAS. O caminho ideal é o contrário: Ad Rank bom (anúncio otimizado) para poder trabalhar com ROAS alto e controlar o gasto pelo ROAS.
- Como saber se a perda por classificação é por anúncio ruim ou por ROAS alto: não há indicação explícita. Olhar cliques e impressões. Se está rodando e mesmo assim não imprime o suficiente, há problema de ranqueamento; se mesmo com ROAS/ACOS extremo quase não clica nem vende, é falta de demanda. Exemplo: um produto com ACOS liberado em 75% que nem assim clicava ou vendia era falta de demanda.
- O alerta do Meli de que "o ROAS é pouco competitivo" sempre aparece e sempre sugere ROAS muito baixo, porque o Meli quer que se ganhe 100% dos leilões. Não seguir cegamente: olhar a contribuição publicitária e quanto realmente se está ganhando.
- Perguntar sempre: faz sentido ganhar mais leilões? Se a cada 4 vendas, 3 vêm de Ads, mostrar mais ainda não faz sentido; é preciso vender organicamente. O Meli fica satisfeito quando se ganha mais leilão, enquanto o seller fica sem margem.
- Caso didático: um dia ganhando 32% de impressões e o Meli apontando como positivo; na prática, a campanha subiu 264% de investimento na semana, vendeu quase só por Ads (de 20 vendas, 1 orgânica) e, com margem de cerca de 10%, perdeu praticamente 12% em publicidade, ou seja, "pagou para vender".
- Cuidado ao aumentar orçamento só porque perde por classificação: aumentar o orçamento só resolve perda por orçamento. Para perda por classificação o ajuste é ROAS (subir ou descer) e melhorar o anúncio.

### Dúvidas comuns: quando faz sentido mexer em ROAS ou orçamento

**Dúvida comum:** Um produto de moda tem anúncios patrocinados exibidos 31%, não exibidos por orçamento 1% e não exibidos por classificação 68%, com aporte de 75%. São números ruins?
**Resposta:** Com aporte baixo (30% a 40%) seriam números ideais. Com aporte de 75% o objetivo é ganhar menos leilões, não mais, senão só se vende por Ads. O orçamento já está ok (perde só 1%). Deve subir o ROAS aos poucos, principalmente porque é o curva A. Se esse anúncio fosse levado a 50% de leilões ganhos, a contribuição bateria em cerca de 90%.

**Dúvida comum:** Campanha de anúncio isolado com ROAS baixo, ACOS alto, TACOS baixo, perda por orçamento de 53% e perda por classificação de 24%. O que fazer?
**Resposta:** ACOS alto com TACOS baixo significa que o orgânico performa bem. Com muita perda por orçamento, dá para aumentar o orçamento (pode até dobrar) e, ao mesmo tempo, subir o ROAS (por exemplo de 7 para 15, de uma vez ou em etapas: 10, 12, 15). Quanto mais se sobe o ROAS, mais se perde por classificação e menos por orçamento; ao dar mais orçamento, um balanceia o outro. Ressalva: um TACOS de 4% é alto se a margem de contribuição for de 15% (equivale a mais de um quarto da margem). Com margem acima de 20% a 25%, TACOS de 4% é considerado aceitável.

**Dúvida comum:** Quando uma campanha fica com ROAS baixo e TACOS baixo, o que isso mostra?
**Resposta:** ACOS e ROAS medem eficiência publicitária; TACOS mede eficiência financeira (impacto sobre o faturamento total). ACOS alto e TACOS baixo indica que o orgânico está performando bem e a contribuição publicitária provavelmente é saudável. Pode valer mexer no ROAS para "reaprender" a campanha, subindo o ROAS mas ganhando mais leilão em testes pontuais; só vale aumentar orçamento se há perda por orçamento.

## ACOS x TACOS

- ACOS e ROAS: eficiência publicitária (gasto em Ads sobre a receita de Ads, ou o inverso, ROAS).
- TACOS: eficiência financeira (gasto em Ads sobre o faturamento total, com e sem Ads).
- Exemplo: TACOS de 11% nos produtos em 30 dias significa perder 11% de margem só em publicidade. Quando praticamente tudo que vende é por Ads, ACOS e TACOS ficam iguais (um produto que vendeu 11 unidades, 100% por Ads, tinha ACOS = TACOS).
- Referência de teto: TACOS de 4% com margem de contribuição de 15% já é pesado.

## Estrutura de campanhas: curvas A, B e C e a regra 70-20-10

- Curva orgânica não é a mesma coisa que curva publicitária. Há produto que organicamente é curva C, mas na lógica de Ads o que importa é a curva A da conta; em conta pequena, curva A, B e C da publicidade saem da curva A orgânica.
- Tudo que é curva A da conta deve estar 100% em Ads (pode estar separado em campanhas A, B e C da publicidade). Curva B e C dependem do cenário: se há poucos anúncios ou verba, dá para trabalhar mais produtos; em conta com muitos anúncios, o foco fica nos principais.
- Regra 70-20-10 (distribuição do orçamento de Ads): 70% para campanhas de curva A, 20% para curva B, 10% para curva C. Exemplo: com R$ 1.000 por mês, R$ 700 na curva A, R$ 200 na B e R$ 100 na C.
- Quando os produtos já estão muito bem posicionados, pode-se trabalhar com menos de 70% na curva A, tirando um pouco da A e colocando em B para ranquear mais produtos. É uma base, não uma lei fixa.
- Características por curva:
  - Curva A: orçamento alto, ROAS mais alto, poucos anúncios por campanha (1 a 5 ou 6 no máximo; produtos muito fortes podem ficar isolados). Pode haver mais de uma campanha de curva A.
  - Curva B: orçamento por volta de 20% do total, ROAS intermediário (abaixo do da curva A), de 8 a 12 anúncios por campanha, até duas ou três campanhas.
  - Curva C: orçamento em torno de 10%, ROAS o mais baixo, 15, 20 ou até 30 anúncios, funcionando como campanha de teste (também chamada de campanha de pesca): o que performa sobe para curva B, o que não performa é arrancado. Deve ser momentânea, por exemplo 30 dias, depois mantém-se só o que performa.
- Movimentação: o que performa bem na C sobe para B, o que performa bem na B sobe para A; o que não performa na A desce, na B cai para C e na C sai da publicidade.
- Um produto por campanha não é errado, mas o trabalho é muito grande e geralmente não compensa. Os anúncios competindo entre si na mesma campanha ajudam a ver quem puxa o orçamento. Mesmo em conta multinicho, a quantidade de campanhas é menor do que um por produto.
- Campanha de produtos novos: só entram depois que vendem bem organicamente e performam o suficiente para fazer sentido em Ads (cerca de 90% dos casos). Só em casos muito específicos (por exemplo, lançamento) vão direto. Produto novo ranqueia primeiro com orgânico bem posicionado e preço competitivo.
- Produto com mais de uma conta própria: se o nicho é pequeno e o produto específico, cuidado para não canibalizar uma conta com a outra; focar num produto em cada conta. Se o nicho é grande e muita gente vende, não há problema em anunciar o mesmo produto nas duas.

### Regra do 0,5% do faturamento para decidir quem entra em Ads

- Produto que representa menos de 0,5% do faturamento: não colocar em Ads nesse momento (a não ser em campanha de teste/pesca, sabendo o que está fazendo). Ver essa participação na tela de métricas do Mercado Livre, na parte de anúncios.
- Acima de 0,5% já faz mais sentido estar em Ads. O que está bem acima disso é o foco.
- Em conta concentrada (por exemplo, dois anúncios acima de 20% do faturamento cada), esses dois são super curva A, isolados numa campanha, e concentram o esforço. Em conta mais diluída, o principal pode ter 3% a 4% do faturamento, e então trabalha-se com mais anúncios. Quem traz mais resultado fica com maior percentual do orçamento.
- Se a conta usa a campanha automática sugerida pelo Mercado Ads, pode-se aproveitá-la como curva C: pausar tudo o que não vendeu, deixar um orçamento baixo, tirar o que performa bem (que deve ir para campanha A ou B) e manter só os testes.

## Quantos anúncios por campanha, ticket e giro

- Anúncios de performance parecida rodam por igual na mesma campanha. Quando um consome e outro não, a causa é a diferença de performance: o Meli entrega para os itens de maior volume de impressão, clique e conversão, e os demais ficam "escondidos".
- Ticket (preço): separar por faixa de ticket só quando a diferença é muito grande, por exemplo um produto de R$ 20 e outro de R$ 2.000, e já na criação. Para diferenças moderadas (R$ 60 e R$ 200) é preferível testar na mesma campanha primeiro; se o produto de ticket mais alto puxa mais investimento, divide por ticket (por exemplo curva B de ticket alto e de ticket baixo).
- Kits de 2, 3, 5 e 10 unidades do mesmo produto: o kit maior tem ticket maior e naturalmente consome mais orçamento; na mesma campanha o kit de ticket baixo pode não gastar. Soluções: baixar o ROAS para fazer rodar mais, ou separar por ticket.
- Giro: produto de ticket baixo gira muito, e a campanha mantém ROAS/ACOS estáveis dia a dia. Produto de ticket alto (kits, colchões) vende menos unidades; naturalmente o ROAS oscila: um dia o ACOS estoura, no seguinte fica perfeito. Para ticket alto, analisar períodos maiores, não o dia a dia.
- Misturar ticket baixo e alto na mesma campanha "bagunça" a campanha.
- Orçamento alto não garante que o anúncio gaste: quem determina o gasto é o desempenho do anúncio e o ROAS. Para destravar: baixar um pouco o ROAS para rodar mais, ou separar produtos de ticket muito diferente.
- Anúncio de curva A que não consome: isolar numa campanha e fazer rodar. Anúncio de curva B ou C que não performa: pode retirar ou jogar para a curva C para ir testando.
- Se a campanha tem um item bom e outros que não vendem (uma venda em 30 dias, ou nenhuma), remover os que não vendem. Não mexer em orçamento quando a campanha já não gasta o orçamento (por exemplo orçamento de R$ 50 por dia e R$ 60 gastos em 7 dias).
- Aviso: ao tirar da campanha o anúncio que mais consumia, o orçamento passa todo para o que ficou, que pode consumir "uma enxurrada" e piorar a performance. Nesse caso reduzir o orçamento (no exemplo, de R$ 50 para cerca de R$ 15 por dia) e subir o ROAS (por exemplo para 12) para não dar pancada de gasto.
- Produto de performance diferente, mesmo sendo o "mesmo produto" (variações, kits): não deve ficar na mesma campanha. Exemplo: um com ROAS 2 e duas vendas; outro com ROAS 62 e oito vendas; um vendeu 36 e outro 1; um com CPC altíssimo (provável problema de atratividade, CTR baixo). Separar: os que performam bem juntos; os que performam mal em outra campanha com ROAS alto de teste ("campanha de pesca") ou removê-los (uma venda em 30 dias, remover).
- Reorganização feita no exemplo: isolar os dois melhores produtos numa campanha com ROAS entre 8 e 10 (ou subir para 12); colocar os demais produtos mais fracos numa campanha separada com ROAS na casa de 15 para "aprender a trabalhar".

**Dúvida comum:** Mais de uma campanha com produtos de R$ 100 e outros de R$ 3.000: posso colocar na mesma campanha?
**Resposta:** Pode, como primeiro teste. Depois de 7 a 15 dias, olhar se o de R$ 3.000 sugou todo o orçamento. Se não performou, isolar em campanhas separadas por faixa de ticket.

## Orçamento por campanha: arredondar e dar folga

- Exemplo: orçamento total de R$ 800 no mês de gasto real; arredondar para R$ 900 e dar R$ 30 por dia por campanha. Se o ROAS está alto, a campanha não vai consumir tudo isso.
- Cuidado com campanha com orçamento alto de R$ 100 por dia (R$ 3.000 por mês) e ROAS 5: perigosíssimo para o faturamento daquele produto.
- Ao retirar um anúncio de uma campanha, sobra orçamento para o que ficou. Reduzir o orçamento para não dar "pancada de investimento".
- Mexer no orçamento só quando necessário: aumentar quando há perda por orçamento e o produto compensa; diminuir quando é teste de curva C ou quando se quer limitar. Na maioria dos casos o ajuste é no ROAS, não no orçamento.
- Se a campanha não gasta o orçamento, mexer no orçamento não faz diferença; o ajuste é no ROAS.

## Quando baixar o ROAS para acelerar

**Dúvida comum:** Quero acelerar uma campanha corretamente. Hoje o ROAS é 8; devo baixar o objetivo?
**Resposta:** Não está errado se for estratégico e independente da contribuição publicitária, mas é preciso acompanhar a contribuição e o retorno para não gastar demais. Muitas vezes, em vez de baixar o ROAS, compensa direcionar o investimento extra para ferramentas que só gastam quando há venda, porque a publicidade gasta vendendo ou não.

**Dúvida comum:** Por que o CPC não abaixa, mesmo mudando imagem e título?
**Resposta:** O CPC está vinculado à demanda por leilões de anúncios iguais ao seu. Se o CPC sobe, a demanda (a concorrência por esse espaço) aumentou; se cai, diminuiu. Não depende só do seu anúncio.

## Variações e Ads

- Se acaba o estoque de uma variação, a conversão cai e consequentemente a entrega do anúncio pode ser afetada.
- Variação de grade (tamanhos P, M, G ou números de sapato) quebra mais: o comprador entra achando que tem o seu número e não tem, o que derruba a conversão. Variação só de cor atrapalha menos.

## Catálogo e Ads

- Produto em catálogo: só vale manter em Ads se o anúncio ganha o catálogo mais de 90% do tempo. Em catálogo em que se ganha e perde alternadamente, não compensa gastar muito em Ads; se perde o catálogo por distância razoável, o anúncio praticamente não roda no Product Ads.
- Catálogo próprio (marca própria, principalmente com registro): pode deixar em Ads.

## Produto sem demanda e liquidação via Ads

- Forçar Ads para esvaziar estoque de produto sem demanda é um cenário ruim: gasta-se muito em Ads para pouco retorno. Se há margem, dá para vender aos poucos, com ROAS mais alto, em campanha isolada. Se o cenário não faz sentido, é melhor assumir o prejuízo com consciência do que seguir pagando para vender.
- Anúncio que perde 99% por classificação mesmo com preço baixo e Ad Rank destruído ("derretido"): muitas vezes performa mais criar o anúncio do zero do que tentar ressuscitá-lo.

## O que o Ads realmente faz (conceito)

**Dúvida comum:** Qual é o objetivo do Ads? Ele não serve para vender?
**Resposta:** Toda ferramenta de tráfego pago leva a pagar para aparecer, não para vender. O Ads só imprime e mostra o anúncio para mais gente; se o título e a capa forem bons, traz o clique; se o anúncio (descrição, imagens, clips, convencimento) for bom, traz a venda. Se o anúncio for ruim, o Ads apenas expõe um anúncio ruim. Por isso se coloca mais orçamento em curva A (produto já validado), enquanto a curva C trabalha com ROAS baixo, apenas dando visibilidade inicial.

**Dúvida comum:** Vale a pena anunciar em outra plataforma de busca para levar tráfego ao anúncio do Mercado Livre?
**Resposta:** Não. O custo por clique fora do Mercado Livre fica mais caro do que dentro dele.

**Dúvida comum:** O orçamento de Ads recomendado pelo Meli ou pelo Mercado Ads vale seguir?
**Resposta:** Não, sobretudo o orçamento automático/compartilhado. Olhar contribuição, perda por classificação e perda por orçamento da própria conta.

**Dúvida comum:** Qual ROAS objetivo para uma campanha nova?
**Resposta:** Depende do intuito. Quanto mais curva A, maior o ROAS (20, 25, 30 conforme posicionamento); curva C, mais baixo (9, 10, 11 para teste); curva B no meio do caminho.

## Teto de verba de marketing pela margem

- O velho "3% do faturamento bruto no Ads" não considera mais outras ferramentas de marketing além do Ads. O teto total de marketing sai da margem: referência de cerca de um quinto (20%) da margem de contribuição. Exemplos: margem de contribuição de 15% leva a teto total de 3%; margem de 12% leva a cerca de 2,4%; margem de 20% leva a cerca de 4%.
- Divisão inicial usando a ideia do 70-20-10: com 3% de verba total, 70% para Ads (2,1%) e o restante para as demais ferramentas. É só o ponto de partida; vai regulando pela eficiência (ROAS ou ACOS de cada ferramenta).
- Se outra ferramenta entrega ROAS maior que o do Ads (exemplo: ROAS da publicidade 12, ROAS de outra ferramenta 25), tirar verba de Ads e concentrar o Ads nos melhores produtos. A verba que iria para curva C de teste pode ser redirecionada.
- Trabalhar sem Ads não é ruim: pode-se usar Ads em poucos anúncios de curva A para continuar acelerando sem estourar a contribuição.

## Erros comuns

- Aceitar a recomendação do Mercado Ads de reduzir o ROAS de 10 para 8,33 em campanha de produto curva A e deixar o orçamento automático ligado: investimento sobe, receita cai, ROAS realizado desaba.
- Orçamento de R$ 100 por dia (R$ 3.000 por mês) em campanha de ROAS 5 e vários produtos fracos: dinheiro gasto sem retorno. Um caso comum é uma conta que deveria gastar cerca de R$ 600 em Ads gastar perto de R$ 3.000 sem resultado.
- Deixar anúncios de performance muito diferente juntos na campanha, com um consumindo quase todo o orçamento e outros "escondidos".
- Misturar tickets muito diferentes (kit com 10 e unidade) sem olhar o giro.
- Olhar ROAS de um dia só em vez de períodos de 7, 15 e 30 dias; deixar picos de um dia mascararem dias de gasto sem venda.
- Esquecer de checar a contribuição publicitária antes de acelerar: se a cada 4 vendas, 3 vêm de Ads, falta orgânico.
- Mudar ROAS de muito em muito de uma vez, em produto curva A, sem esperar a janela de atribuição de cerca de 7 dias.
- Deixar de remover do Ads o produto que vende uma unidade em 30 dias.

## Rotina semanal recomendada

- Pelo menos uma vez por semana, fazer a análise completa: conta, campanha por campanha, anúncio por anúncio, nas janelas de 30, 15 e 7 dias.
- Conferir por campanha: investimento por curva em relação ao 70-20-10, ROAS objetivo x realizado, aporte/contribuição, perda por orçamento e por classificação, ACOS e TACOS.
- Tratar detratores (limpar, isolar, remover, jogar para campanha de teste) e acelerar promotores (subir ROAS gradualmente ou dar orçamento).
- Campanhas de teste (curva C ou pesca) devem ser temporárias; depois de cerca de 30 dias, manter só o que performa.
- Após a mudança, aguardar cerca de uma semana (ou 4 a 5 dias para mudanças pequenas) antes de nova mexida.

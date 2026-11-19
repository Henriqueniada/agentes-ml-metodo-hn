# Ads — Métricas, fórmulas, contribuição publicitária, CTR e CVR

Assuntos: faturamento, receita publicitária e investimento (as três métricas base); ACOS, ROAS, TACOS e ROI (fórmulas, diferença e conversão entre elas); contribuição publicitária (faixas ideais, teto de 50%, como calcular); quais anúncios entram em Ads (curva A da publicidade, corte de 0,5% de participação); Ads em catálogo; ACOS ideal por nicho; impressões, cliques, visitas, vendas e unidades; CTR e CVR (o que mexer em cada um, diagnóstico vitrine x página); avaliações e ad rank (leilão do Mercado Ads); como saber se cada métrica melhora ou piora só olhando as variações; atalho ACOS ÷ 2 versus TACOS; anúncio sem venda, devolução e anúncio a forçar; compartilhar orçamento e ajuste automático; organização de campanhas; CPC, CPM e CPA.

## Por que entender a lógica das métricas e não decorar fórmulas

Métrica é matemática: quase tudo é uma divisão entre dois números que o Mercado Livre já mostra no painel. Quem entende o raciocínio consegue olhar as variações percentuais do painel e deduzir o que aconteceu sem refazer a conta. São usadas duas telas: Métricas (Vendas > Métricas) e Publicidade (Product Ads).

## As três métricas base

Tudo parte de três números:

1. **Faturamento total (vendas brutas):** tudo o que a conta vendeu, por publicidade ou não (orgânico incluído). É o norte da conta. Em Métricas aparece como "Vendas brutas". Se cai muito, é preocupante, mesmo sabendo que também importa a margem e o vender saudável.
2. **Receita (faturamento publicitário):** só as vendas que vieram depois de uma passagem por publicidade (Product Ads).
3. **Investimento (gasto):** o que saiu do caixa em publicidade na plataforma. O painel chama de "gasto"; "investimento" é o termo preferido, porque é dinheiro aplicado para gerar receita.

Todas as outras métricas de desempenho (ACOS, ROAS, TACOS, ROI, contribuição publicitária) são cálculos feitos a partir desses três números.

## Fórmulas de desempenho: ACOS, ROAS, TACOS, ROI

**ACOS** (Advertising Cost of Sales, custo de publicidade por venda): investimento dividido pela receita publicitária, vezes 100. O resultado é um percentual. Mede a eficiência da publicidade em si. Quanto menor, melhor (na maioria dos casos, com a ressalva de que muito baixo pode significar dinheiro deixado na mesa).

**ROAS** (Return on Advertising Spend): receita publicitária dividida pelo investimento. Não é percentual, é um fator de multiplicação (aparece com "x"). É o mesmo número do ACOS visto do outro lado. Responde: para cada R$ 1 colocado em Ads, quantos reais voltaram. ROAS 20 significa que cada R$ 1 investido devolveu R$ 20. Quanto maior, melhor. ACOS e ROAS são inversamente proporcionais: se um sobe, o outro cai.

**TACOS** (Total Advertising Cost of Sales): investimento dividido pelo faturamento total da conta, vezes 100. Percentual. Diferente do ACOS, o TACOS não é uma métrica publicitária pura: ele compara o investimento com o faturamento geral (orgânico mais Ads), portanto é uma métrica de eficiência financeira. Quanto menor, melhor.

**ROI** (Return on Investment): faturamento total dividido pelo investimento. É o inverso do TACOS, também um fator de multiplicação e não um percentual.

Resumo da lógica de pares:
- ACOS e ROAS usam investimento e receita publicitária: olham só a publicidade.
- TACOS e ROI usam investimento e faturamento total: olham o financeiro geral.
- Percentual (ACOS, TACOS): do que foi vendido, quantos por cento foram para publicidade.
- Fator (ROAS, ROI): para cada R$ 1 colocado, quanto voltou.

### Como converter de uma métrica para a outra

Basta dividir 100 pela métrica que se tem:
- ACOS = 100 ÷ ROAS, e ROAS = 100 ÷ ACOS.
- TACOS = 100 ÷ ROI, e ROI = 100 ÷ TACOS.

Exemplos: ROAS 20 equivale a ACOS 5%. ACOS 10% equivale a ROAS 10. ROI 50 equivale a TACOS 2%.

O Mercado Livre mudou a exibição do ACOS para ROAS; é exatamente a mesma informação lida ao contrário.

### Ler a variação do painel sem fazer conta

Exemplo: ACOS subindo 31%, investimento caindo 25%, receita caindo 43%. O ACOS é investimento dividido por receita. Se o investimento cai 25% mas a receita cai 43%, a receita caiu mais que o investimento, então o ACOS piora. Se o investimento tivesse caído 25% e a receita se mantido, caído menos de 25% ou subido, o ACOS melhoraria. Não é preciso saber os valores anteriores: basta olhar a variação percentual de cada componente.

## Contribuição publicitária (aporte de publicidade)

**Definição:** quantos por cento do faturamento total veio de publicidade. Fórmula: receita publicitária dividida pelo faturamento total, vezes 100. É a relação entre os dois números que as métricas anteriores não relacionavam entre si (receita e faturamento). Em quantidade de vendas, é equivalente a vendas por Product Ads divididas pelas vendas totais.

### Faixas de referência

- **Normal:** 30% a 35% das vendas vindo de Ads, algo em torno de um terço. Em geral aceita 30% a 40%.
- **Momento de aceleração:** pode subir até cerca de 50% e ainda ser saudável.
- **Acima de 50%: perigoso.** Dois riscos: dependência publicitária (sem Ads a conta não vende, para vender tem que pagar) e canibalização (grande chance de estar pagando por vendas que seriam orgânicas de qualquer jeito).
- **Muito baixo, abaixo de 15% a 20%:** a conta está deixando dinheiro na mesa. Orgânico forte é bom, mas um Ads que contribui pouco indica que se poderia performar melhor.
- Em contas sazonais ou em campanha de aceleração intencional, passar de 50% pode ser uma decisão consciente. Exemplo: campanha com 66% de contribuição, aceitável por ser um produto sazonal em época que exigia forçar venda.
- Uma contribuição de 48% no dia a dia normal ainda está dentro do saudável, mas dá para enxugar e sobrar mais margem; em aceleração ou fora da sazonalidade tentando segurar posição, é aceitável.

### Pegadinha importante: o percentual do painel não é o da conta

O percentual de vendas por publicidade que aparece na tela de Publicidade considera só os anúncios que estão divulgados (em campanha). Exemplo: o painel mostrava 64%, mas esse número só compara as vendas dos anúncios em Ads (publicitárias e orgânicas desses anúncios). A contribuição real da conta compara a receita publicitária total com o faturamento total da conta (incluindo os anúncios que estão fora de Ads e vendem organicamente). Nesse exemplo, o cálculo correto deu 48,28%.

Passo a passo para calcular a contribuição da conta:
1. Em Publicidade, pegar a receita publicitária do período (por exemplo, últimos 30 dias).
2. Em Vendas > Métricas, pegar as vendas brutas do mesmo período.
3. Dividir receita por vendas brutas e multiplicar por 100.

Dentro de uma campanha, o percentual mostrado vale só para os produtos daquela campanha (exemplo: campanha com 2 produtos e 66% das vendas vindo de Ads, ou seja, duas a cada três vendas por publicidade).

O Mercado Livre também traz um indicador chamado "aporte de publicidade" que ajuda a ver isso sem calcular manualmente.

### Atalho: ACOS dividido por 2 contra TACOS

Dá para saber se um anúncio ou campanha passou do teto de 50% sem ter o faturamento total do produto (que a tela de Ads não mostra por anúncio). Dedução: contribuição = receita ÷ faturamento. Como receita = investimento ÷ ACOS e faturamento = investimento ÷ TACOS, o investimento se cancela e a contribuição publicitária é TACOS dividido por ACOS, vezes 100.

Regra prática:
- Pegue o ACOS do produto e divida por 2. Se o TACOS estiver acima desse valor, a contribuição está acima de 50% (alta, dependente de Ads). Se estiver abaixo, está dentro do teto.
- Exemplo 1: ACOS 7%, metade é 3,5%. TACOS acima de 3,5% significa contribuição acima de 50%.
- Exemplo 2: ACOS 8% e TACOS 2% resulta em 25% de contribuição (tranquilo). ACOS 8% e TACOS 6,5% resulta em mais de 80% (problema, é preciso agir).
- Exemplo 3: ACOS 3% e TACOS 2% resulta em cerca de 66% de contribuição (alta).
- Exemplo 4: ACOS 7,08% e TACOS 3,65%: metade do ACOS é 3,54%, o TACOS está levemente acima, então a contribuição está um pouco acima de 50% (o cálculo manual deu 51,53%).
- Exemplo 5: ACOS 8,92% e TACOS 4,3%: metade é 4,46%, o TACOS está abaixo, então contribuição de cerca de 48%.
- Exemplo 6: ACOS 16,37% e TACOS 10,77%: metade do ACOS é cerca de 8%, o TACOS está bem acima, então a contribuição é muito alta e o cenário está pesado.

Observação: TACOS e ACOS por produto e por campanha aparecem no painel; por conta inteira o Mercado Livre não traz TACOS. O TACOS por anúncio aparece dentro do anúncio, não na página principal de campanhas.

### Como reduzir a contribuição publicitária (e por que isso reduz o TACOS)

A contribuição = TACOS ÷ ACOS. Para melhorá-la, ou se aumenta o ACOS (não é o objetivo) ou se reduz o TACOS. Reduzir o TACOS significa aumentar o faturamento total (vender mais organicamente) e investir menos, ou seja, vender menos por Ads e mais fora de Ads.

O TACOS não se "ajusta" diretamente: cai quando se melhora o orgânico. Exemplo numérico: mantendo o ACOS em cerca de 8%, passar de 48% para 30% de contribuição reduz o TACOS de cerca de 3,8% para 2,37%, aproximadamente 1,4 ponto percentual de margem a mais. O orgânico melhora com a otimização do anúncio (CTR, CVR e as demais métricas deste material) e com ações fora de Ads. Ao reduzir investimento, fazer aos poucos, sem cortar 50% de uma vez, para não derrubar o faturamento: vá tirando devagar e colocando mais verba onde realmente performa.

### TACOS e a margem

O TACOS é um percentual que sai diretamente da margem de contribuição. Se a margem do produto é 10% e o TACOS é 10%, a margem de lucro é zero, ou negativa se passar disso. Como referência do método, o TACOS ideal costuma ser em torno de 20% da margem (exemplo: margem 10% resulta em TACOS ao redor de 2%), podendo no começo ficar na faixa de 10% a 20%. Quando se está posicionando um produto (ranqueando), é aceitável gastar mais temporariamente, e a contribuição pode ficar acima de 50%, desde que seja uma decisão consciente e não permanente.

Como o ACOS isolado não diz tudo, a análise combina ACOS, TACOS e contribuição; ACOS baixo com contribuição alta ainda pode ser problema.

## Quais anúncios entram em Ads

- Ads não é para 100% dos anúncios. É para os que performam bem. A orientação "põe tudo em Ads" (inclusive a do próprio Mercado Livre) não é a regra do método.
- Trabalha-se basicamente com a curva A da conta. A curva A, B e C da publicidade é diferente da curva A, B e C da conta inteira: muitas vezes só os A da conta entram na publicidade; um C ou até um B da conta, em geral, não faria sentido em Ads. As campanhas são nomeadas pela curva (A, B, C) e por finalidade (growth, ranking, profit, core) para facilitar a gestão.
- Em contas com quantidade razoável de anúncios, trabalha-se com cerca de 40 a 50 anúncios em Ads, no máximo (varia). Em autopeças, por exemplo, trabalha-se com praticamente todos os anúncios por causa da cauda longa. Em conta muito pequena (10 a 15 anúncios), pode-se anunciar todos.
- Critério de corte: anúncios com participação de 0,5% ou mais no faturamento da conta costumam ser os que fazem sentido em Ads, o que costuma dar na casa de 40 a 50 MLBs em 90% dos casos. Para calcular, baixar a planilha de vendas dos últimos 30 dias, montar uma tabela dinâmica por MLB, calcular o faturamento de cada um e dividir pelo total. Também dá para ver pela tela de Métricas, mas ela às vezes falha na paginação (mostra só a primeira página), por isso a planilha é preferível. O Mercado Livre também classifica curva ABC da conta inteira.
- Cuidado com "falso curva A": um produto pode ser A em faturamento por ticket alto e não ser em quantidade de vendas.
- Análise de campanha sempre em períodos de 30, 15 e 7 dias, para ver se a contribuição e as métricas estão melhorando ou piorando.

### Ads em catálogo

Só vale anunciar em Ads um anúncio de catálogo (que não é exclusivamente seu) se for possível garantir que se está ganhando o catálogo na grande maioria do tempo (a referência é cerca de 90% do tempo). Se não está ganhando o catálogo, não faça Ads: o risco é pagar o clique, a pessoa não comprar naquele momento, voltar depois e comprar de quem ganhou o catálogo, e o anúncio de outro ter sido acelerado. Se o Ads só roda quando se ganha, ganhando 10% das vezes o Ads muitas vezes nem roda.

## ACOS ideal por nicho

Não existe ACOS ideal único: depende da categoria, da concorrência, da variação e se o produto é de necessidade ou desejo.

- Quanto mais variação (cor, tamanho, modelo), mais a pessoa clica em vários, compara e demora a comprar, o que infla o ACOS. Moda (roupa, vestido, tênis), cortina, persiana e enxoval costumam ter ACOS mais alto, na faixa de 10, 15 até 20%.
- Produto sem variação e de necessidade específica (exemplo: filtro de ar de um modelo de carro) tem comprador mais assertivo, que olha o preço e compra, com ACOS mais baixo.
- Suplementos, produtos de academia e saúde: investimento alto, fabricantes com margem alta, nicho muito competitivo, ACOS mais alto.
- Cola de silicone e impermeabilizante: ACOS de 17% para cima é normal.
- Mala e mochila: 15% é um pouco alto; o recomendado seria 8% a 10% para ficar saudável (compra menos rápida, muita variação, as pessoas clicam mais e compram menos). Anúncio já consolidado pode trabalhar com bem menos; anúncio em posicionamento, 8% a 10% costuma ser viável.
- Autopeças: algumas trabalham com ACOS muito alto, outras já vêm orgânicas fortes.
- Produto de necessidade: precisa aparecer na frente o tempo todo. Produto de desejo: a pessoa vem atrás.
- Ao comparar com o ACOS de outro vendedor, só olhar o ACOS não permite concluir nada: é preciso analisar as demais métricas.

### ACOS que oscila muito de um dia para o outro

Acontece em dois cenários normais: ticket alto, ou produto específico de linha profissional ou de autopeças (cauda longa, em que a cada dia vende um modelo diferente). Nesses casos, olhe sempre períodos maiores. Em produto de ticket baixo, de venda diária, a oscilação forte indica problema de configuração de campanha: perda de impressões, conversão ruim ou campanha desenhada de forma errada. Produto com poucas vendas nem deveria estar em Ads.

## Outras métricas básicas: impressões, cliques, visitas, vendas e unidades

Métricas que não precisam de cálculo (vêm prontas do painel):

- **Impressões:** toda vez que alguém viu o anúncio patrocinado (na pesquisa, por exemplo). Na tela geral de Publicidade, refere-se só ao anúncio patrocinado (dentro do anúncio individual dá para ver impressões totais). Em Product Ads só se olha impressão, não alcance (alcance e frequência são para outras ferramentas de mídia).
- **Cliques:** toda vez que alguém clicou no anúncio patrocinado. É a visita publicitária.
- **Visitas:** toda vez que alguém entrou no anúncio, vindo de Ads ou não (visão total). Cliques e visitas são a mesma coisa, uma só publicitária e outra total.
- **Vendas por Product Ads:** compras vindas pelo anúncio patrocinado. **Vendas sem Product Ads:** compras do mesmo anúncio que não vieram de publicidade. Na tela só aparecem esses dois para os anúncios que estão em campanha; as vendas de anúncios fora de Ads não aparecem ali.
- **Quantidade de vendas** (número de compras) e **unidades vendidas** (soma de unidades; uma venda pode ter mais de uma unidade). Também existem canceladas e devolvidas, que permitem calcular percentuais.

Exemplo de leitura: 678 vendas por Product Ads mais 374 sem Product Ads nos anúncios em campanha resultam em 1.052 vendas desses anúncios. Se a conta vendeu 1.875 no total, os outros anúncios (fora de Ads) trouxeram 823 vendas. Com cerca de 50 anúncios em Ads trazendo mais de mil vendas e uns 150 fora trazendo cerca de 800, fica claro por que se concentra Ads nos principais produtos. A relação vendas por Ads sobre vendas totais equivale à contribuição publicitária.

### Os três fatores do funil

Todas essas métricas resumem o caminho do cliente: **viu** (impressão), **clicou** (clique ou visita), **comprou** (venda). A relação entre elas gera as taxas de conversão.

## CTR e CVR

**CTR** (Click Through Rate): cliques divididos por impressões, vezes 100. De todo mundo que viu o anúncio, quantos entraram. Percentual, quanto maior melhor. Mede o quanto a vitrine foi atrativa. No Product Ads, aparece dentro dos anúncios da campanha, não na tela principal. Na tela de Métricas da conta não existe impressão, então não dá para calcular o CTR da conta inteira.

**CVR** (taxa de conversão): vendas divididas por cliques, vezes 100. De todo mundo que clicou e entrou no anúncio, quantos compraram. É a conversão de venda em si. No Mercado Livre costuma aparecer como "conversão" apenas dentro de alguns painéis; em publicidade, calcula-se.

Os dois são métricas de conversão: o CTR é conversão de entrada e o CVR é conversão de venda.

### O que é um bom CTR

Depende da categoria, da concorrência, da posição e do tempo de mercado. Não há número único: um CTR de 0,48% pode ser ótimo numa categoria; em outra, 10% pode ser baixo (produto novo, muita pesquisa, pouca concorrência, anúncio no topo). Orientação: analisar a média dos anúncios da conta, usar como base e tentar subir sempre. Quanto mais concorrência, mais é preciso se diferenciar para atrair o clique. Quanto mais bem posicionado (principalmente organicamente, com selo de mais vendido), maior o CTR.

### O que mexer em cada um (diagnóstico vitrine x página)

- **CTR baixo:** o problema está na vitrine, o que aparece na pesquisa antes do clique. Mexer em foto de capa (a principal), título, preço, selos (cupom, oferta, frete grátis, logística, nota de avaliação). Foto de capa e título são o que mais puxa o olho.
- **CVR baixo:** o problema está dentro da página do produto. Mexer em clips, demais fotos, ficha técnica, descrição, avaliações (o que os compradores escrevem), variações e experiência de compra.
- Mexer na descrição ou nos clips não muda o CTR (o clique ocorre antes de a pessoa ver isso). Em Product Ads não se patrocina o clips: o que aparece é a capa, o título e o preço. Dá para ver a taxa de visualização do clips, mas não a conversão real do clips para dentro do anúncio.
- Analogia da loja: se pouca gente entra na loja, de nada adianta treinar o vendedor; é preciso melhorar a vitrine. Depois que entra, a conversão tem que estar boa lá dentro. Publicidade não vende, publicidade imprime. Se o Ads gera impressão e o anúncio não gera clique, a culpa não é do Ads, é do anúncio mal otimizado.
- **Avaliação conta nos dois:** a nota geral aparece na vitrine (afeta o CTR); o conteúdo das avaliações (o que o comprador escreve sobre fragilidade, tamanho, produto diferente da foto) afeta o CVR.
- **Nota abaixo de 4,5 é perigo imediato:** o Mercado Livre começa a reduzir a entrega, as impressões caem, a nota de experiência cai e o anúncio pode até ser travado na publicidade. Se ficou muito baixo, a recomendação é apagar o anúncio e subir outro para reposicionar; abaixo de 4,5 a conversão cai muito (pela confiança do comprador e pelo corte do próprio Mercado Livre).

## Ad rank e o leilão do Mercado Ads (por que anúncio bom paga menos)

O leilão não é baseado só no quanto se está disposto a pagar. O Mercado Livre considera o valor e a relação do quanto o anúncio é benéfico para o comprador e para a plataforma. Quanto melhor a conversão (CTR e CVR), a avaliação, a entrega (sem atraso) e a experiência de compra (sem reclamação, sem devolução), melhor o ad rank. Ganha-se mais leilões gastando menos. Isso vale para as plataformas de anúncios em geral.

Raciocínio: o Mercado Livre empresta o nome dele a quem vende e quer fidelizar o comprador para a recorrência. Por isso prefere ganhar um pouco menos num clique e divulgar o produto que encanta, do que ganhar muito de um anúncio mal otimizado, com CTR baixo, que não converte, atrasa e gera reclamação. Se dois vendedores oferecem o mesmo produto, o do vendedor com anúncio melhor ranqueado, boa avaliação e boa entrega paga menos para aparecer; o de anúncio pior precisa pagar mais para valer a divulgação. Por isso um concorrente pode estar gastando menos: ele tem um anúncio melhor ranqueado.

## Como saber se cada métrica está melhorando ou piorando

Regra geral: as fórmulas são divisões; olhe a variação de cada componente, não do resultado. Em uma divisão, o resultado cai quando o numerador (de cima) cai ou o denominador (de baixo) sobe, e sobe no caso contrário.

| Métrica | Melhor | Como melhorar |
|---|---|---|
| ACOS (investimento / receita) | menor | aumentar a receita ou reduzir o investimento |
| ROAS (receita / investimento) | maior | aumentar a receita ou reduzir o investimento |
| TACOS (investimento / faturamento) | menor | aumentar o faturamento total ou reduzir o investimento |
| ROI (faturamento / investimento) | maior | aumentar o faturamento ou reduzir o investimento |
| CTR (cliques / impressões) | maior | aumentar cliques mais do que as impressões, ou reduzir impressões mais do que os cliques |
| CVR (vendas / cliques) | maior | aumentar vendas mais do que os cliques, ou reduzir cliques mais do que as vendas |
| Contribuição publicitária (receita / faturamento) | menor, com teto de 50% | aumentar vendas sem Ads (orgânicas) ou reduzir as vendas por Ads |

Observações:
- Não é preciso saber os valores: só as variações percentuais. Exemplos para o ACOS: receita +10% e investimento -5% melhora; receita -10% e investimento -5% piora (receita caiu mais que o investimento); receita -10% e investimento -15% melhora; receita +10% e investimento +15% piora (investiu mais do que a receita cresceu).
- É possível reduzir impressões: aumentar o orçamento da campanha ou o lance e melhorar os pontos vistos acima também afeta isso; reduzir a verba reduz a impressão. O importante é que cliques e vendas se movam na proporção correta.
- Vendas totais e unidades: mais vendas orgânicas melhoram a contribuição.
- Se o ACOS subir enquanto o investimento cai, a receita caiu mais; se a conversão (CVR) melhorar com o mesmo investimento, o ACOS melhora porque a mesma quantidade de cliques gera mais receita.
- Se o ACOS subiu e o investimento caiu, não é necessariamente que o custo da venda aumentou: a relação é entre investimento e receita, não só o valor do investimento.

## Orçamento: compartilhar orçamento e ajuste automático

- Desative o "compartilhar orçamento" entre campanhas: se não for usado corretamente, ele gasta o orçamento em excesso.
- Desative o ajuste automático de orçamento (o ícone de cifrão automático ao editar a campanha). Ele consome orçamento acima do planejado sem que se perceba. Esse recurso só serve para aumentar o orçamento sem consentimento, não baixa o que existia; desativar impede que o Mercado Livre gaste mais do que o combinado.

## Campanhas: organização

- Campanhas de Product Ads não são separadas por categoria; são separadas por performance. Produtos diferentes na mesma campanha podem performar melhor do que separar por tipo, salvo se houver uma estratégia específica (como uma sazonalidade).
- Em geral (90% dos casos) usa-se mais de um produto por campanha. Quanto mais bem posicionado (mais curva A), menos anúncios por campanha, com orçamento maior e ROAS mais alto. Quanto menos posicionado, mais anúncios na campanha, com menos investimento e ROAS menor.
- Um anúncio só pode estar em uma campanha de publicidade por vez; não dá para duplicar em duas.
- **Anúncio que se quer forçar a crescer:** isolar numa campanha específica. Se ficar misturado, outros produtos "mordem" o orçamento e ele não cresce, ou ele puxa investimento sem retorno e prejudica o restante da campanha.
- **Orçamento pequeno com muitos anúncios:** exemplo: campanha automática de cerca de 150 anúncios com R$ 17 por dia. O orçamento é muito baixo para essa quantidade, provavelmente anúncios ruins estão consumindo a verba que seria dos curva A, e não dá para testar produtos novos. Recomendação: separar uma campanha com os principais produtos e tirar os que não vendem.
- **Anúncio que consome e não vende:** produto que gera muito clique e não vende (muita pesquisa mas anúncio mal otimizado) puxa orçamento, o investimento sobe, o TACOS sobe e o ROAS cai. Para reverter, é preciso aumentar o faturamento e diminuir o investimento.
- **Anúncio que nunca vendeu dentro da campanha:** ou retira de vez (se é irrelevante) ou coloca numa campanha de teste, com orçamento pequeno e ROAS (meta) baixo para trazer visibilidade; depois que ele tem as primeiras vendas, sobe-se o ROAS-alvo e o orçamento conforme a necessidade. Um anúncio com traço (sem dado) no ACOS e no TACOS no período é um anúncio sem venda no período.
- **Anúncio sem avaliação (começando agora):** preço bem atrativo, ir passo a passo, não há atalho.

## Devolução dentro de Ads

Produto que vendia bem e começou a ter muitas devoluções: muito provavelmente tire do Ads. O Ads tende a ficar mais caro depois disso (pior ad rank). Primeiro investigue a causa da devolução, que costuma ser um destes três pilares:
1. Problema de lote (defeito no produto): não há muito o que fazer no anúncio; é preciso reclamar com o fornecedor. Tire o anúncio do Ads, porque continuar vendendo com lote ruim derruba a experiência e a reputação.
2. Falta de explicação no recebimento: o comprador não sabe usar (faltou manual ou instrução).
3. Anúncio mal explicado: o comprador acha que é uma coisa e recebe outra (tamanho, produto diferente da foto).

## Custo por clique, CPM, CPA e ticket médio

Cruzando os três fatores com o investimento obtêm-se outras métricas de publicidade:
- Investimento com impressões: CPM (custo por mil impressões).
- Investimento com cliques: CPC (custo por clique).
- Investimento com vendas: CPA (custo por aquisição).
- Faturamento com vendas: ticket médio. Unidades por venda: média de unidades por compra.

Em Product Ads essas métricas servem pouco no dia a dia. O CPC é útil só como termômetro de demanda: quando o CPC sobe, a demanda pelo produto caiu; quando o CPC cai, a demanda subiu. Ganho de leilões, pacing (ritmo de gasto da verba) e impressão perdida são tópicos de configuração avançada de campanhas.

## Dúvidas comuns

**Dúvida comum:** O ACOS está subindo, mas o investimento está caindo. Isso quer dizer que o custo está maior?
**Resposta:** Não necessariamente. O ACOS compara investimento com receita. Se o investimento caiu 25% e a receita caiu 43%, a receita caiu mais, então o ACOS piora. Para saber para onde o ACOS foi, olhe a variação de investimento e de receita, não só o investimento.

**Dúvida comum:** O TACOS é uma métrica publicitária?
**Resposta:** Não exatamente. O ACOS é eficiência publicitária (investimento sobre receita de Ads). O TACOS é eficiência financeira (investimento sobre faturamento total), embora tudo esteja conectado, porque a publicidade ajuda o ranqueamento e a venda orgânica.

**Dúvida comum:** Qual é uma contribuição publicitária ideal?
**Resposta:** Em condições normais, de 30% a 35% (aceitável até 40%). Em aceleração, até cerca de 50%. Acima de 50% é perigoso (dependência e canibalização). Abaixo de 15% a 20% pode ser dinheiro deixado na mesa.

**Dúvida comum:** O painel de Publicidade mostra 64%. É a contribuição da conta?
**Resposta:** Não. Esse percentual considera só os anúncios que estão em Ads. A contribuição da conta compara a receita publicitária total com o faturamento total (Vendas > Métricas) do mesmo período. No exemplo, os 64% do painel eram na verdade 48,28% na conta.

**Dúvida comum:** Como definir quais anúncios devem ou não estar em Ads?
**Resposta:** Ads não é para todos. Trabalha-se com a curva A (curva da publicidade, que é diferente da da conta). Um corte usado é participação de 0,5% ou mais no faturamento da conta, o que costuma dar 40 a 50 MLBs. Ordene por faturamento dos últimos 30 dias, preferencialmente numa planilha dinâmica por MLB. Em autopeças e cauda longa usa-se uma quantidade muito maior de anúncios; em conta muito pequena, podem ser todos.

**Dúvida comum:** Vale fazer Ads em anúncio de catálogo que não é só meu?
**Resposta:** Só se o catálogo for ganho em cerca de 90% do tempo. Caso contrário, paga-se o clique e a venda pode ir para quem ganhou o catálogo depois.

**Dúvida comum:** Como baixar um ACOS de 24% em mala e mochila, se o ACOS ideal é 15%?
**Resposta:** Não dá para concluir só olhando o ACOS; é preciso analisar as outras métricas. Para mala e mochila, 15% é um pouco alto; o recomendável seria 8% a 10% (mais baixo ainda em anúncio já consolidado). Categorias com muita variação (moda, cortina, persiana, enxoval) têm ACOS naturalmente mais alto (10 a 20%).

**Dúvida comum:** O ACOS oscila muito de um dia para o outro. É normal?
**Resposta:** É normal em produto de ticket alto ou muito específico (linha profissional, autopeças, cauda longa), e nesse caso olhe períodos mais longos. Em produto de ticket baixo e venda diária, a oscilação forte indica configuração errada de campanha (perda de impressão, conversão ruim). Produto com poucas vendas nem deveria estar em Ads.

**Dúvida comum:** Se mexer na descrição, o CTR melhora? E se mexer nos clips?
**Resposta:** Não. O CTR depende do que aparece na vitrine (capa, título, preço, selos, nota). Descrição, clips, outras fotos e ficha técnica melhoram o CVR, porque agem dentro do anúncio.

**Dúvida comum:** Avaliação é CTR ou CVR?
**Resposta:** Depende. A nota geral aparece na vitrine e afeta o CTR. O que as pessoas escrevem nas avaliações afeta o CVR. Abaixo de 4,5 o Mercado Livre começa a derrubar a entrega.

**Dúvida comum:** Por que há concorrentes que gastam menos em Ads do que eu com o mesmo produto?
**Resposta:** Por causa do ad rank. Anúncio com boa conversão, boa avaliação, boa entrega e baixa devolução é favorecido no leilão e paga menos para aparecer. Anúncio pior precisa pagar mais. Se mesmo mexendo em tudo o Ads continua caro, o anúncio provavelmente não está bem otimizado e é preciso achar onde está o problema.

**Dúvida comum:** Um produto que vendia bem agora tem muita devolução. Tirar do Ads?
**Resposta:** Muito provavelmente sim. Antes, investigue a causa: lote com defeito, falta de instrução na entrega, ou anúncio que não explica bem o que é o produto. Se for lote, reclame com o fornecedor; manter vendendo derruba a experiência.

**Dúvida comum:** Um produto na campanha nunca vendeu. Tirar?
**Resposta:** Pode retirar de vez, ou colocar numa campanha de teste com orçamento baixo e ROAS (meta) baixo para ganhar visibilidade; depois que vender, sobe-se a meta e o orçamento. O ideal é não deixar produto sem venda consumindo verba de produto bom.

**Dúvida comum:** Uma campanha automática com cerca de 150 anúncios e orçamento de R$ 17 por dia está certa?
**Resposta:** O orçamento é baixo demais para tantos anúncios, e provavelmente anúncios ruins estão consumindo a verba dos curva A. Separe uma campanha com os principais produtos e retire os que não vendem.

**Dúvida comum:** Como forçar um anúncio a crescer?
**Resposta:** Isole-o numa campanha específica, para que não dispute verba com outros nem puxe investimento de quem já performa.

**Dúvida comum:** Posso colocar o mesmo anúncio em duas campanhas de publicidade?
**Resposta:** Não, o Mercado Livre não permite.

**Dúvida comum:** É preciso separar campanhas por categoria?
**Resposta:** Não. Product Ads é por performance, não por categoria. Só separe se houver uma estratégia específica (por exemplo, sazonalidade).

**Dúvida comum:** Vários produtos por campanha ou um por campanha?
**Resposta:** Em 90% dos casos, vários. Quanto mais bem posicionado o anúncio, menos anúncios na campanha, com orçamento e ROAS maiores. Quanto menos posicionado, mais anúncios por campanha com menos investimento e ROAS menor.

**Dúvida comum:** O que é compartilhar orçamento e ajuste automático? Ativar?
**Resposta:** Desative os dois. Podem consumir verba acima do planejado sem que se perceba.

**Dúvida comum:** Uma contribuição publicitária de 48% está boa?
**Resposta:** É o limite do saudável. Aceitável em aceleração ou sazonalidade; em situação normal, dá para ser mais saudável e enxugar. Reduzindo de 48% para 30% de contribuição, mantendo o ACOS, o TACOS cai cerca de 1,4 ponto percentual e sobra mais margem. Reduza o investimento aos poucos, para o faturamento não cair junto.

**Dúvida comum:** Como diminuir o TACOS?
**Resposta:** Aumentando o faturamento total e reduzindo o investimento. Na prática, melhora-se o orgânico: otimização do anúncio e das métricas de CTR e CVR, além de ações fora de Ads. O TACOS cai quando a dependência de Ads cai.

**Dúvida comum:** Em um produto dentro da campanha aparecem ACOS e TACOS, mas não contribuição nem CTR. Como avaliar?
**Resposta:** Use o atalho: divida o ACOS por 2. Se o TACOS do produto estiver acima desse valor, a contribuição está acima de 50% e o produto depende de Ads. Para CTR e CVR, analise as variações das métricas base (impressões, cliques, vendas) entre períodos de 30, 15 e 7 dias.

**Dúvida comum:** O que fazer com um anúncio novo sem avaliações?
**Resposta:** Preço bem atrativo e ir passo a passo; no começo não há atalho.

## Resumo dos números e regras

- Contribuição publicitária normal: 30% a 35% (até 40%); em aceleração: até ~50%; acima de 50%: dependência e canibalização; abaixo de 15% a 20%: dinheiro na mesa.
- ACOS = investimento ÷ receita × 100. ROAS = receita ÷ investimento. TACOS = investimento ÷ faturamento × 100. ROI = faturamento ÷ investimento. ACOS = 100 ÷ ROAS e TACOS = 100 ÷ ROI.
- Contribuição = receita ÷ faturamento × 100 = TACOS ÷ ACOS × 100. Atalho: TACOS maior que ACOS ÷ 2 significa contribuição acima de 50%.
- CTR = cliques ÷ impressões × 100 (problema de vitrine: capa, título, preço, selos). CVR = vendas ÷ cliques × 100 (problema dentro do anúncio: clips, fotos, ficha, descrição, avaliações).
- Nota de avaliação abaixo de 4,5: perigo imediato de queda de entrega.
- Anúncios em Ads: curva A da publicidade; corte prático de 0,5% de participação no faturamento; cerca de 40 a 50 anúncios na maioria das contas; análise em 30, 15 e 7 dias.
- Desativar compartilhamento de orçamento e ajuste automático de orçamento.
- Um anúncio só pode estar em uma campanha de publicidade.
- Em catálogo, só anunciar se ganhar o catálogo em cerca de 90% do tempo.

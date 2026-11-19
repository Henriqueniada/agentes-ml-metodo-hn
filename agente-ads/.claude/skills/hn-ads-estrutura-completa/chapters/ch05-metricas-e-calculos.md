# Matemática das métricas de Ads (ACOS, TACOS, contribuição publicitária, CTR e CVR)


## Ideia central
Toda análise de Ads sai de 3 métricas primárias (faturamento total, receita, investimento) e de 3 fatores de funil (visualização, visita, venda). Combinadas, elas dão ACOS/ROAS, TACOS/ROI, contribuição publicitária, CTR e CVR. Com o atalho **TACOS < ACOS ÷ 2** você vê, anúncio por anúncio, se ele está dependente de Ads.

## Métodos e frameworks
- **3 métricas primárias ("cores primárias")**: faturamento total (vendas brutas, Ads + orgânico, na tela de Métricas), receita (só o que veio de publicidade, no painel de Product Ads) e investimento (o que saiu para Ads; chame de "investimento", não de "gasto").
- **Fórmulas base**:
  - ACOS = investimento ÷ receita × 100 → eficiência publicitária (quanto menor, melhor).
  - ROAS = receita ÷ investimento → fator de multiplicação.
  - TACOS = investimento ÷ faturamento total × 100 → eficiência financeira, porque bate direto na margem.
  - ROI = faturamento ÷ investimento.
  - Contribuição publicitária = receita ÷ faturamento total × 100.
  - Regra de bolso: percentual = "parte pelo todo" (× 100); fator = "maior pelo menor".
- **Atalho dos 100**: 100 ÷ ROAS = ACOS e 100 ÷ ACOS = ROAS. O mesmo vale entre TACOS e ROI. Exemplos: 25% de ACOS = ROAS 4; ROAS 50 = 2% de ACOS.
- **Margem realizada**: MC bruta (faturamento − frete − devolução − imposto − custo do produto − tarifas do marketplace) − TACOS = MC realizada. Os custos fixos (aluguel, folha, luz, pró-labore) saem depois disso.
- **7 métricas → 3 fatores**: impressões (visualização); cliques e visitas (visita); vendas por Product Ads, outras vendas, quantidade vendida e unidades vendidas (venda).
- **Três conversões (CVR)**:
  - CVR de Ads = vendas por Product Ads ÷ cliques.
  - CVR total = quantidade de vendas ÷ visitas.
  - CVR orgânica = (vendas − vendas por Product Ads) ÷ (visitas − cliques).
- **Vitrine vs. loja (CTR vs. CVR)**:
  - Quando usar: para decidir o que otimizar.
  - CTR baixo é problema de vitrine: imagem de capa, título, preço, Full, cupom, preço de atacado/para negócios, estrelinhas da avaliação.
  - CVR baixo é problema de dentro do anúncio: clips, demais imagens, ficha técnica, descrição, texto das avaliações.
- **Leitura sem calcular (numerador/denominador)**: compare as variações de numerador e denominador entre períodos.
  - ACOS cai se a receita sobe mais que o investimento.
  - CTR sobe se os cliques sobem mais que as impressões.
  - CVR do anúncio = vendas atribuídas vs. cliques. Exemplo: vendas +10% com cliques +25% = conversão caindo.
- **Regra TACOS < ACOS ÷ 2**: deduzida da contribuição publicitária, que equivale a TACOS ÷ ACOS × 100.
  - Se o TACOS do anúncio passar da metade do ACOS, a contribuição está acima de 50% e o anúncio está dependente de Ads.
  - ACOS = TACOS significa 100% de contribuição.
  - Como: na lista de anúncios da campanha, divida o ACOS por 2 e compare com o TACOS.

## Conceitos-chave
- **Receita**: faturamento atribuído à publicidade (painel Product Ads).
- **Faturamento total / vendas brutas**: Ads + orgânico (tela Métricas).
- **Contribuição publicitária**: % do faturamento total que veio de Ads.
- **Aporte publicitário**: indicador do painel de Product Ads que considera só os anúncios em campanha. É sempre ≥ à contribuição publicitária e igual a ela se todos os anúncios estiverem em Ads.
- **Cliques vs. visitas**: cliques = visitas publicitárias. Visitas = Ads + orgânico, e ficam só na tela Métricas.
- **Vendas atribuídas / outras vendas**: são os novos nomes de "vendas por Product Ads" e "vendas sem Product Ads". "Outras vendas" conta só os anúncios que estão em campanha.
- **Quantidade vendida vs. unidades vendidas**: pedidos vs. unidades. Um pedido pode ter 3 unidades.
- **CPC / CPA**: custo por clique / custo por aquisição. O CPA é "primo" do ACOS, só que por quantidade em vez de reais.
- **Ad rank / Ad score**: credibilidade do anúncio e da conta que o leilão usa além do lance.
- **MLBU (user product)**: novo formato de anúncio. Cada variação vira um MLB próprio, com preço, logística e promoção separados, mas fica agrupada em ad group na publicidade.
- **Venda assistida**: explica TACOS > ACOS em casos específicos no nível anúncio/campanha.

## Modelos mentais
- Pense no CTR como a vitrine do shopping e no CVR como o atendimento dentro da loja. Mexer em clip ou descrição não resolve CTR.
- Pense no leilão como o Mercado Livre protegendo a própria reputação: um produto validado e com bom pós-venda ganha mesmo pagando menos. Um anúncio sem vendas só aparece pagando muito mais.
- Use o TACOS como linha de margem. Exemplo: margem de 15% com 7% de TACOS significa que "metade da sua margem foi embora com publicidade".
- A publicidade só leva até a impressão. Clique e venda dependem da otimização do próprio anúncio.

## Números e limites citados
- **Contribuição publicitária ideal**: 30–40% em períodos normais. Para acelerar, até ~50% ainda é saudável.
- **Acima de 50%**: dependência e risco de canibalização.
- **Contribuição de 15–20% ou menos**: provável "dinheiro na mesa".
- **"99,9% dos casos"**: não faz sentido vender quase tudo por Ads.
- **Janelas de análise**: sempre 30, 15 e 7 dias. Olhe Ads pelo menos 1 vez por semana, na segunda-feira.
- **CTR não tem valor ideal**:
  - Em algumas categorias, 1% "é sonho"; em outras, 12% é pouco.
  - Produtos com muita variação (moda, cortina, persiana, tapete) têm CTR mais baixo.
  - Sobre 4% de CTR, ele disse que é bom, mas depende muito do produto.
- **CVR**: para ter referência, compare com os top 50 da categoria no painel de tendências/concorrência do ML.
- **Exemplos de margem**: MC bruta 17% − TACOS 3% = 14% realizada; 12% − 4% = 8%.
- **Ranqueio por preço**:
  - Exemplo: preço-alvo R$ 78,99 e venda para ranquear a R$ 59,99 ("no 0 a 0").
  - Não mexa no preço-base. Reduza o desconto da central de promoções aos poucos (20% → 18 → 16 → 15 → 13 → 10%), a cada 1–2 semanas ou na virada do mês.
- **Ruptura**: anúncio não sazonal 4 meses sem estoque perde o ad rank e pode valer mais criar um anúncio do zero. Anúncio sazonal pode ficar 1 ano desligado e voltar.
- **Data comercial (7/7)**:
  - Suba o orçamento e baixe o ROAS objetivo de propósito (o mesmo vale para a Black Friday).
  - Confira o consumo às 8h, 12h, 16–18h e 20h. Exemplo: R$ 18 de R$ 20 consumidos ao meio-dia → suba para R$ 40.
  - Faça isso só em curva A/B. Tenha cautela em curva C ou em teste.

## Erros comuns (anti-padrões)
- **Ligar Ads em anúncio novo e sem vendas**: o leilão fica caro, porque o ML não conhece a oferta. Valide antes no orgânico (cupom agressivo, central de promoções, oferta relâmpago, afiliados, clips). Também não mande para o Full antes de validar.
- **Conta "viciada" em Ads**: novos anúncios só vendem com Ads. A saída é um "detox": enxugar Ads aos poucos, sem desligar tudo, e fortalecer o orgânico.
- **Aumentar investimento achando que é "aumentar Ads"**: a meta é mais receita de Ads, não mais gasto. Investir mais sem vender sobe ACOS e TACOS.
- **Subir o preço-base de uma vez ou mudar o desconto bruscamente**: as vendas despencam.
- **Olhar só o ACOS**: um ACOS de 8,8% parece bom, mas com TACOS de 6,98% a contribuição está estourada.
- **Ativar orçamento compartilhado sem acompanhar a conta o dia inteiro**: "muito cuidado".
- **Estoque baixo no Full**: tira visibilidade. É empírico, "não gravado em pedra".

## Exemplo trabalhado
Checagem de anúncios reais com a regra ACOS ÷ 2:
- **ACOS 7,83%**: arredonda para 8 → 4 (precisamente 3,9). TACOS acima disso significa contribuição > 50%.
- **ACOS 8,86% / TACOS 6,98%**: 8,86 ÷ 2 ≈ 4,4, abaixo de 6,98. Contribuição estourada, apesar do ACOS aceitável. Precisa de análise orgânica urgente e de segurar Ads.
- **ACOS 10,25% / TACOS 6,28%**: o limite seria 5. Para um TACOS de 6, o ACOS teria de ser pelo menos 12 → dependente.
- **ACOS 20,5%**: ACOS ÷ 2 fica acima do TACOS, então a contribuição está OK (~30%), mas ACOS e TACOS estão altos: a eficiência está baixa.
- **ACOS 4,57% / TACOS 3,67%**: contribuição alta.
- **ACOS = TACOS (3,82 / 3,82)**: 100% das vendas do anúncio no período vieram de Ads.

## Principais lições
1. Separe sempre receita (Ads) de faturamento total (Ads + orgânico). Errar isso contamina todos os cálculos.
2. Acompanhe a contribuição publicitária da conta e de cada anúncio. Um curva A que só vende por Ads pode estar tirando orçamento de curvas B/C.
3. Em cada anúncio de campanha, use TACOS < ACOS ÷ 2 como triagem rápida de dependência.
4. Diagnostique antes de otimizar: CTR caindo → mexa na vitrine; CVR caindo → mexa no conteúdo interno.
5. Compare janelas de 30/15/7 dias pela variação de numerador e denominador, sem recalcular tudo.
6. Primeiro valide no orgânico, depois acelere em Ads. Assim o anúncio entra "aquecido" e com CPC menor.
7. Em data de alta conversão, abra orçamento, baixe o ROAS objetivo e vigie o consumo ao longo do dia.

## Conecta com
- Configuração de ROAS objetivo (o ML trocou ACOS objetivo por ROAS objetivo)
- Central de promoções, cupons e afiliados (regras R em `regras.md`)
- Estratégia de datas comerciais e sazonalidade
- Curva ABC e distribuição de orçamento
- MLBU/user product e ad groups em Product Ads
- Full, estoque e ad rank

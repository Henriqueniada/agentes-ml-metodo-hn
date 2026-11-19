# Leitura de métricas: ACOS, ROAS, TACOS, ROI, contribuição publicitária, CTR e CVR


## Ideia central
Não decore fórmulas: entenda de quais números básicos cada métrica é feita. Assim você lê se ela melhorou ou piorou só olhando a variação de investimento, receita, faturamento, cliques e vendas. A métrica-mestra de saúde é a **contribuição publicitária**, e ela dá para estimar anúncio por anúncio com **ACOS ÷ 2 vs TACOS**.

## Métodos e frameworks
- **3 métricas fundamentais ("cores primárias")**: faturamento total (Vendas Brutas na tela de Métricas), receita (vendas que vieram de publicidade) e investimento (gasto em Ads). Todas as outras saem da mistura dessas três.
- **Pares gêmeos**: ACOS = investimento ÷ receita × 100. ROAS = receita ÷ investimento (fator "x"). TACOS = investimento ÷ faturamento × 100. ROI = faturamento ÷ investimento.
  - ACOS/ROAS = **eficiência publicitária**. TACOS/ROI = **eficiência financeira** ("tacos não é métrica publicitária").
  - Para converter de um no outro, use 100 ÷ o número: ROAS = 100 ÷ ACOS, TACOS = 100 ÷ ROI.
- **Contribuição publicitária (CP)** = receita ÷ faturamento × 100: quanto % do faturamento veio de Ads.
- **Funil de 3 fatores**: viu (impressão) → clicou (clique/visita) → comprou (venda).
  - CTR = cliques ÷ impressões × 100. Mede a vitrine.
  - CVR = vendas ÷ cliques × 100. Mede o anúncio por dentro.
- **"Requisinho" da variação**: para saber se uma métrica melhorou, olhe a variação percentual do numerador e do denominador, sem refazer a conta.
  - Exemplo: o investimento cai 25% e a receita cai 43%. A receita caiu mais, então o ACOS piorou.
- **Atalho ACOS ÷ 2**: CP = TACOS ÷ ACOS × 100. Se o TACOS do anúncio for maior que a metade do ACOS, a CP passou de 50%.
  - Quando usar: na campanha, anúncio por anúncio, porque o ML não mostra a CP por produto.
- **Corte de quem entra em Ads (só referência, não é regra)**: no Excel de Vendas dos últimos 30 dias, monte uma tabela dinâmica por MLB e calcule o share de cada um no faturamento. Coloque em Ads quem tem **≥ 0,5%**, o que costuma dar 40–50 MLBs.
- **Janela de análise 30/15/7**: compare os períodos de 30, 15 e 7 dias para ver a tendência.

## Conceitos-chave
- **Vendas Brutas**: o faturamento total da conta, com orgânico e Ads juntos.
- **Receita (publicitária)**: vendas de quem passou pela publicidade.
- **Aporte de publicidade (painel)**: é a CP só dos anúncios que estão em Ads, não da conta inteira.
- **Dependência publicitária**: a conta só vende se pagar para vender.
- **Canibalização**: pagar Ads por uma venda que já seria sua.
- **Cliques vs visitas**: clique é a visita que veio do Ads. Visita é o total.
- **Ad rank**: o leilão considera o lance e a qualidade (conversão, CTR, avaliação, entrega). Anúncio melhor paga menos.
- **CPC**: aparece no painel e serve só como termômetro de demanda. CPM e CPA quase não se aplicam a Product Ads.
- **Falso curva A**: é curva A em faturamento, mas não em quantidade de vendas.

## Modelos mentais
- Pense no CTR como a **vitrine da loja**: capa, título, preço, frete, cupom, tag e nota macro. Pense no CVR como o **vendedor lá dentro**: clips, demais fotos, ficha técnica, descrição e o texto das avaliações. Não adianta treinar o vendedor se ninguém entra.
- "Publicidade não vende, publicidade imprime." CTR baixo é culpa do anúncio, não do Ads.
- Pense como o Mercado Livre: ele prefere divulgar o anúncio que fideliza o cliente e cobra mais caro de quem converte mal.
- Para baixar o TACOS sem mexer no ACOS, faça vender mais fora do Ads: cupom, afiliados, canal de transmissão, clips e otimização do anúncio.

## Números e limites citados
- **CP ideal na CNTP: 30–40%**, de preferência 30–35% (cerca de 1/3 das vendas vindo de Ads).
  - Em aceleração ou sazonalidade, até 50% ainda é saudável.
  - **Acima de 50%** fica perigoso (dependência e canibalização).
  - **Abaixo de 15–20%** você está deixando dinheiro na mesa.
- Caso real: o painel mostrava 64% em Ads. A conta real deu 410.752 ÷ 850.743 = **48,28%**.
- **Regra HN**: em 90% dos casos, trabalhe com 40–50 anúncios em Ads, no máximo. Exceções:
  - Autopeças (cauda longa): quase todos os anúncios.
  - Conta muito pequena (10–15 anúncios): todos.
- Referências de ACOS por nicho:
  - Malas e mochilas: 15% está alto, trabalhe com 8–10%.
  - Colas, silicone e impermeabilizante: 17% para cima é normal.
  - Produtos com muita variação (moda, cortina, enxoval): 10, 15, 20%.
- CTR: 0,48% pode ser ótimo numa categoria e 5% possível em outra. Já houve categoria com 10% que ainda dava para subir.
- **Avaliação abaixo de 4,5 é "perigo iminente"**: o ML derruba a entrega e às vezes trava o anúncio em Ads.
- Teto de marketing: 20% *da margem* (margem 10 → 2%); Ads começa com 70% dele.
- Para entrar com Ads em catálogo, você precisa ganhar o catálogo **~90% do tempo**.

## Erros comuns (anti-padrões)
- **Ler o "aporte" do painel como CP da conta**: ele exclui os anúncios fora de Ads e infla o número.
- **Deixar ligados "compartilhar orçamento" e o ajuste automático de orçamento ($)**: consomem verba sem você ver. Desative os dois.
- **Pôr todos os anúncios numa campanha automática com verba baixa** (ex.: 150 anúncios com R$17/dia): o anúncio com pesquisa e sem venda suga a verba da curva A.
- **Separar campanhas por nicho ou categoria**: Product Ads é por performance. Misture produtos.
- **Ads em catálogo que você raramente ganha**: você paga o clique e a venda vai para o concorrente.
- **Manter em Ads um produto com muita devolução ou lote ruim**: o Ads fica mais caro e a experiência cai.
- **Mexer na descrição para subir o CTR**: a descrição afeta o CVR, não o CTR.

## Exemplo trabalhado
Um vendedor tem um anúncio com ACOS de 7,08 e TACOS de 3,65.
- A metade do ACOS é 3,54. Como 3,65 > 3,54, a CP está levemente acima de 50%; a conta exata deu 51,53%.

Outro caso: ACOS 16,37 e TACOS 10,77.
- A metade do ACOS é cerca de 8. O TACOS está quase em 11, então o anúncio está muito dependente de Ads.

Simulação para reduzir a CP:
- Com TACOS 3,8 e CP 48%, o ACOS fica perto de 7,92.
- Mantendo o mesmo ACOS e levando a CP para 30%, o TACOS cai para 2,37.
- Isso dá cerca de 1,4 ponto a mais de margem, só porque o orgânico cresceu.

## Principais lições
1. Calcule a CP da conta à mão: receita de Ads ÷ Vendas Brutas, no mesmo período. Mire em 30–35%.
2. Avalie cada anúncio pelo atalho **TACOS > ACOS ÷ 2** para saber se ele passou de 50% de CP.
3. Para saber o sentido de uma métrica, compare a variação % das partes. Nem precisa abrir o número final.
4. CTR baixo: mexa na vitrine (capa, título, preço, promoção). CVR baixo: mexa no anúncio por dentro.
5. Reduza o TACOS fortalecendo o orgânico, não cortando Ads de uma vez. Corte aos poucos e realoque para quem performa.
6. Isole numa campanha própria o anúncio que você quer forçar. Coloque o produto que nunca vendeu numa campanha de teste com verba pequena e ROAS baixo, ou tire de Ads.
7. Um anúncio só pode estar em uma campanha de publicidade ao mesmo tempo. Na Central de Promoções, ele pode estar em várias.

## Conecta com
- Ad rank, leilão e qualidade do anúncio (CTR/CVR)
- Estrutura e nomenclatura de campanhas (curva A/B/C, Growth, Ranking, Profit, Core)
- Seleção de anúncios por curva ABC e share de faturamento
- Sazonalidade e fases de aceleração
- Catálogo e kits
- Central de Promoções, cupons e afiliados como alavancas do orgânico

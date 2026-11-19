# Otimização semanal de campanhas (aporte, competitividade e curvas A/B/C)


## Ideia central
Otimize Product Ads olhando primeiro a dependência de publicidade (aporte / contribuição publicitária) e o gráfico de competitividade, e só depois o ROAS. Na maioria das contas o erro é ROAS baixo demais com orçamento automático ligado: o Meli gasta muito e o orgânico some.

## Métodos e frameworks
- **Fluxo de análise em 3 níveis (conta → campanha → anúncio)**
  - Quando usar: toda semana, "pelo menos uma vez por semana".
  - Como: (1) Na conta, veja aporte e contribuição publicitária e o ROAS geral. (2) Em cada campanha, veja aporte, ROAS, histórico de mudanças (as "bandeirinhas" no gráfico) e o gráfico de competitividade. (3) Nos anúncios, veja ROAS, CPC, vendas, investimento por MLB e ACOS vs TACOS.
  - Períodos: compare sempre **30, 15 e 7 dias** para ver a tendência. Em campanha que você já acompanha, olhe os últimos 7 dias.
- **Promotor x detrator**: pegue o ROAS da conta no período. Campanha com ROAS acima dele é promotora, abaixo é detratora. Ataque primeiro as detratoras e acelere as melhores. (No exemplo, ROAS da conta 6,54; a detratora estava em 2,56.)
- **Gráfico "Ver a competitividade dos seus anúncios"**: "Aqui tá o ouro da nossa análise." Ele mostra % exibido, perda por orçamento e perda por classificação.
  - Perda por orçamento (lost by budget) deve ficar **zerada**, para a campanha rodar o dia todo.
  - Toda a perda restante deve ser por classificação (lost by ranking), e de preferência porque o ROAS está alto, não porque o anúncio é ruim.
  - Exceção: grandes marcas com ad rank forte perdem por orçamento de propósito (exemplo de ROAS 35 sem perder por classificação).
- **70-20-10 de orçamento**: 70% do orçamento para curva A, 20% para curva B e 10% para curva C. Ajuste quando os curva A já estão bem posicionados: tire um pouco da A e coloque na B para ranquear mais produtos.
- **Estrutura de campanhas por curva (publicitária)**
  - Curva A: orçamento alto, ROAS alto, poucos anúncios (de 1 a 5–6, às vezes um isolado).
  - Curva B: meio-termo, de 8 a 12 MLBs por campanha, no máximo 2 a 3 campanhas B.
  - Curva C / "campanha de pesca": muitos anúncios (15, 20, 30), ROAS mais baixo, ~10% do orçamento. É temporária: em ~30 dias, mantenha só o que performou. O que vai bem sobe para B e de B para A. O que vai mal desce ou sai.
- **Subida gradual de ROAS** para reduzir a dependência de Ads: no máximo 20% por vez e espere 4–5 dias. Na curva A, ~10% por vez. Exceção: resgate de campanha detratora (ex.: 6→10).
- **TMC (Total Marketing Cost)**: Ads + cupom + afiliado ≤ 20% da margem de contribuição. A central de promoção fica fora, porque o preço já é montado considerando ela. Ads começa com 70% do teto; cupom 20% e afiliado 10% como ponto de partida. Mova a verba para a ferramenta com melhor ROAS.

## Conceitos-chave
- **Aporte para publicidade**: % das vendas que veio por Product Ads, considerando os anúncios em Ads.
- **Contribuição publicitária**: receita de Ads em relação ao faturamento total da conta. É menor ou igual ao aporte. Só fica igual quando tudo o que vende está em Ads. No nível da campanha, os dois são o mesmo número.
- **Perda por orçamento vs perda por classificação**: a primeira depende do investimento. A segunda depende do ad rank (qualidade do anúncio) e do ROAS objetivo.
- **Ad rank / ad score**: qualidade do anúncio. Quanto melhor, mais leilão você ganha pagando menos e mais alto pode ser o ROAS.
- **Orçamento automático / compartilhado do Meli** (o ícone de cifrão na campanha): suga a verba compartilhada entre as campanhas. Desligue.
- **Falso positivo de ROAS**: ROAS médio inflado por um pico de um dia (ex.: um dia com ROAS 199), enquanto os outros dias ficaram perto de zero.
- **Curva ABC orgânica ≠ curva ABC publicitária**: muitas vezes só os curva A orgânicos da conta são divididos em A/B/C dentro de Ads.
- **CPC**: está ligado à demanda de leilões parecidos com o seu. CPC sobe quando a demanda cai.
- **ACOS vs TACOS**: o ACOS mede a eficiência publicitária e o TACOS a eficiência financeira. ACOS alto com TACOS baixo indica que o orgânico está performando.
- **TMC**: custo total de marketing (Ads, cupom e afiliado).

## Modelos mentais
- Pense em Ads como alguém que leva o cliente até a porta da loja: "você está pagando pra aparecer, não pra vender". Quem converte é o anúncio (capa, título, imagens, descrição). Ads mostra um anúncio ruim do mesmo jeito.
- Use o aporte para decidir quanto leilão ganhar. Com aporte baixo, ganhar 30–50% dos leilões está ótimo. Com aporte alto, ganhe menos (suba o ROAS) e force o orgânico com central de promoção, cupom e afiliado.
- O alerta do Meli de "ROAS pouco competitivo" não é critério: ele "sempre vai querer que você ganhe 100% dos leilões".
- Coloque na mesma campanha só anúncios de performance parecida. Se a performance for diferente, um consome tudo e o outro fica "escondidinho", mesmo sendo o mesmo produto.

## Números e limites citados
- Aporte / contribuição acima de **50%**: perigoso (alerta).
- Leilões ganhos ideais: **30% a 40%, até 50%** (com aporte baixo). Ganhar 100% nunca é a meta.
- Perda por orçamento: **zero** em 99% dos casos.
- Produto novo (regra HN): orgânico primeiro. Ao entrar em Ads no modo normal, ROAS **25** com **R$10/dia**, descendo de 2 em 2 ou 3 em 3. Para velocidade, só o modo Lançamento (ROAS **10–12**, ch08). ROAS 5–6 só no modo Acelerar, com limite. Evite criar a campanha já com 5–6, porque depois fica difícil subir.
- ROAS por curva: curva A **20, 25, 30** (conforme o posicionamento). Curva C **9, 10, 11** costuma bastar.
- Produto principal do exemplo: voltar o ROAS de 8,33 para pelo menos **10** (resgate), ir para **12** depois de uma semana e chegar a **20** no longo prazo, sempre com degraus de até 20%.
- Esperar **de 7 a 15 dias** antes de decidir se separa produtos de ticket diferente que estão na mesma campanha.
- Anúncio que representa menos de **0,5% do faturamento**: fora de Ads (no máximo, numa campanha de pesca).
- TMC (Ads + cupom + afiliado) ≤ **20% da margem de contribuição**. Margem de 15% dá **3%**, margem de 12% dá **2,4%** e margem de 20% dá **4%**. Exemplo de divisão de 3%: Ads **2,1**, cupom **0,6**, afiliado **0,3**.
- Super cupom: % alto com teto baixo em R$; o limite é a margem (regras de cupom R5 em `regras.md`).
- Catálogo: deixe em Ads só se ganhar **mais de 90% do tempo** (ou se for catálogo próprio, com marca registrada no INPI).
- Produto novo: em **90% dos casos**, só entra em Ads depois de vender bem no orgânico.
- Anúncio que vendeu de 1 a 2 unidades em 30 dias: tire da campanha principal e mova para a campanha de pesca/correção (nunca pausar).

## Erros comuns (anti-padrões)
- **Ligar o orçamento automático/compartilhado**: joga dinheiro fora. No exemplo, puxou a verba compartilhada (R$ 730) para campanhas de ROAS baixo.
- **Aceitar a recomendação do Meli de baixar o ROAS** (de 10 para 8,33): o investimento subiu, a receita caiu e o resultado real foi um ROAS de 7.
- **ROAS 5–7 em curva A já validada**: gera dependência de Ads e, com margem de ~10%, você "pagou para vender".
- **Colocar kits e tickets muito diferentes juntos** (ex.: R$ 20 com R$ 2.000): o de ticket maior suga o orçamento, e o ROAS oscila mais. Avalie em períodos longos. Diferenças pequenas (R$ 60 x R$ 200, ou kit de 5 a ~R$ 100 x kit de 10 a R$ 199) podem ficar juntas no começo.
- **Avaliar ticket alto pelo dia a dia** (ex.: colchão): o ROAS oscila muito. Olhe períodos maiores.
- **Isolar um item e deixar o orçamento alto e o ROAS baixo**: ele recebe uma "enxurrada de investimento". Suba o ROAS e restrinja o orçamento (de R$ 50 para ~R$ 15 por dia no exemplo).
- **Baixar o ROAS para acelerar** quando a central de promoção resolve: a promoção só gasta se vender, e Ads gasta vendendo ou não.
- **Google Ads para a loja do Mercado Livre**: o CPC fica mais caro.
- **Um produto por campanha**: não é errado, mas dá trabalho demais. Vários anúncios competindo entre si costumam performar melhor.

## Exemplo trabalhado
Conta de exemplo, com faturamento de R$ 60–90 mil por mês. Dois plugs adaptadores geram ~47–48% da conta. Contribuição publicitária ~40 e poucos %, aporte 60%. O orçamento automático estava ligado em quase todas as campanhas. Os ROAS estavam entre 5 e 8,33.
1. Desligar o orçamento automático em todas as campanhas. Arredondar o orçamento para ~R$ 900 por mês (R$ 30/dia por campanha).
2. Campanha principal (os 2 plugs, curva A): aporte de 60% nos 30 dias. A bandeirinha mostra que, por recomendação do Meli, o ROAS caiu de 10 para 8,33. Desde então, o ROAS realizado foi de 10,07 (30 dias) para 8,37 (15 dias) e 7 (7 dias), com 50% dos leilões ganhos. Ação: voltar para 10, subir para 12 depois de uma semana e manter os dois plugs juntos. Isolar o segundo se não consumir em uma semana.
3. Campanha de fresa/pano: ROAS ~6 com "falso positivo" de um pico no dia 21/05. O período personalizado de 20/04 a 20/05 mostra que 31 de 41 vendas vieram de Ads. Na última semana, 19 de 20 vendas foram por Ads, com +264% de investimento. Os anúncios tinham TACOS de 11% e performances diferentes. Ação: subir para 12, manter os 2 melhores e tirar os 2 fracos. A ideia é levar os fracos para outra campanha ("pesca").
4. Campanha com ROAS de 5 e R$ 100/dia (~R$ 3 mil por mês): subir para 10 agora e reavaliar durante a semana.
5. Campanha da tampa: o item bom recebia só R$ 0,68 de investimento, enquanto os outros consumiam a verba. Ação: tirar os fracos, subir o ROAS do item isolado para 12 e baixar o orçamento de R$ 50 para R$ 15/dia.

## Principais lições
1. Desligue o orçamento automático do Meli e não aceite no automático a sugestão de baixar o ROAS.
2. Leia o aporte antes do % de leilões ganhos. Aporte alto pede ROAS mais alto e esforço no orgânico.
3. Mantenha a perda por orçamento em zero e controle a entrega pelo ROAS (perda por classificação).
4. Organize por curva publicitária: na A, poucos anúncios com ROAS e orçamento altos. Na C, muitos anúncios com ROAS e orçamento baixos, por tempo limitado.
5. Suba o ROAS aos poucos: até 20% a cada 4–5 dias; na curva A, ~10%.
6. Separe anúncios de performance ou ticket muito diferentes. Isole o curva A que não consome e remova o curva C/B que não vende.
7. Defina o TMC em até 20% da margem (Ads começa com 70%) e distribua a verba pelo ROAS de cada ferramenta (Ads, cupom, afiliado).

## Conecta com
- Aporte e contribuição publicitária, e o limite de 50% (ch01)
- Central de marketing: promoções, cupom, afiliados e carrinho abandonado (regras R em `regras.md`)
- ACOS/TACOS e margem de contribuição
- Catálogo e anúncios com variações (uma grade quebrada derruba a conversão)
- Como recuperar um anúncio "derretido": muitas vezes compensa criar um anúncio novo, ou queimar de 10 a 15 unidades com oferta relâmpago agressiva

# Regras do Método HN — Mercado Livre (resumo numerado)

Duas camadas:

1. **Método** — skill `hn-precificacao` em `.claude/skills/`. É a fonte; o agente só lê.
2. **Este arquivo** — resume o método em regras com código (A1, P2, R8…) e fixa
   números de referência. Onde o vendedor configurou outro valor em `minha-loja.md`
   (margem mínima, margem-objetivo, teto de marketing), vale o dele.

Precedência: skill `hn-precificacao` > `minha-loja.md` (só nos números configuráveis) > este arquivo.

## Ads (Product Ads)

| # | Regra | Por quê |
|---|---|---|
| A1 | **Teto de marketing = 20% da margem de contribuição bruta real do mês fechado** (antes de Ads; nunca a planejada). Ads + cupom + afiliado somados nunca passam disso. Ads começa com 70% do teto (~14% da margem). Promoção fica fora (já está no preço). Curva C pode passar do teto por um tempo; A e B nunca. Nunca % fixo do faturamento. | Ads, cupom e afiliado saem da mesma margem; o que importa é o custo total por venda. |
| A2 | **A alavanca principal é o ROAS objetivo, não o orçamento.** Perda por orçamento alta → subir o ROAS antes de pôr verba. Nunca baixar o ROAS por sugestão do ML nem por "sobrar verba". | ROAS alto faz o ML mostrar só onde há mais chance de venda. |
| A3 | **Mudança de ROAS: no máximo 20% por vez**, esperando 4–5 dias. Curva A: ~10%. Perdeu exposição depois de subir → voltar no mesmo passo (moonwalk). Exceções: resgate de campanha ruim (ex.: 6 → 10) e "desfibrilador" (campanha sem impressão: ROAS baixo e orçamento alto por ~5 dias). **Baixar o ROAS só em 4 casos:** gangorra, data comercial (curva A/B), desfibrilador e orgânico crescendo sem parar (aí ROAS ~15 e mais orçamento). Nunca por sugestão do ML. | Mudança grande faz a campanha reaprender e derruba as vendas por 2–3 dias; a curva A é o faturamento principal. |
| A4 | **ROAS de referência (modo normal):** produto novo entra em Ads com **ROAS 25 e R$10/dia, descendo de 2 em 2 ou de 3 em 3**; curva C/pesca 9–11; curva A 12–17+ (alvo maduro 20–30). ROAS 5 em curva A é inaceitável. Velocidade maior só pelos modos da A11. | ROAS baixo amplia o público, não as vendas, e come margem. |
| A5 | **Estrutura por curva de Ads A/B/C, orçamento 70/20/10.** A: 1–6 anúncios (<12), vendem e têm estoque fundo. B: tudo que vendeu em 30 dias (8–12, máx. 20). C: pesca, temporária (~30 dias). Revisão semanal: sobe/desce de curva. Não separar por categoria. Maioria das contas: 3–4 campanhas (R$100 mil/mês: 3; R$8–10 milhões/mês: 6–7). | Campanha demais divide verba e aprendizado. |
| A6 | **Detrator** = ROAS abaixo do da conta (campanha) ou da campanha (produto), lido em 30 e 7 dias, toda segunda. **Nunca pausar.** Antes de agir, análise completa: CTR, conversão, share de impressões, leilões ganhos, perda por orçamento, contribuição publicitária, TACOS, vendas pagas × orgânicas. Ação: (a) sem venda em 30 dias → sai de Ads; (b) um anúncio ruim → **move para campanha de ROAS 15+ e orçamento baixo** e corrige a causa (CTR baixo = capa/título/preço/frete; conversão baixa = fotos/clips/descrição); (c) >50% da venda vem de Ads → sobe ROAS aos poucos e fortalece o orgânico; (d) campanha inteira ruim → sobe o ROAS da campanha (resgate); (e) estoque de 1–5 peças ou catálogo ganho <90% do tempo → sai de Ads. Ter <0,5% do faturamento é só referência, não motivo de saída. | Pausar corta o público e perde o aprendizado; com ROAS alto o anúncio segue vivo enquanto é corrigido. |
| A7 | **Contribuição publicitária** (receita de Ads ÷ faturamento) **é alerta**: 30–40% ideal; >50% = conta dependente do Ads; <15–20% = venda deixada na mesa. TACOS > ACOS ÷ 2 também indica dependência. | Mostra se a conta vive do Ads ou se está deixando venda na mesa. |
| A8 | **Quem não entra em Ads:** sem 5–10 vendas no orgânico (regra da casa); produto que não vendeu em 7 dias de aquecimento (cupom, promoção, relâmpago, afiliado, clips) — mexer no anúncio primeiro; catálogo que não ganha ~90% do tempo; estoque raso. Produto novo: orgânico primeiro; Ads desde o dia 1 só nos modos Lançamento ou Teste (A11). | Anúncio sem venda paga clique caro porque o ML ainda não conhece a oferta. |
| A9 | **Desligar orçamento automático/compartilhado.** Orçamento é mensal, não diário. Regra do dia 20: gastou <50–60% → mandar o resto para a última semana. Bônus de Ads: usar 100% e somar verba própria (aparece como reembolso na fatura do Mercado Pago). | Bônus parado é dinheiro perdido; o teto é do mês. |
| A10 | **Revisão:** Ads pelo menos 1 vez por semana, na segunda. Curva A a cada 7 dias, B 15, C 30. "Analisar com 30, entender com 15, executar com 7." Um ritmo só para toda a conta (nada de 14/28 dias). | Mexer duas vezes na semana não deixa ver o resultado. |
| A11 | **Modos especiais** — a estratégia atual é o modo normal. Modo especial só quando o dono pedir, sempre com início, fim e meta: **Lançamento** (ROAS 10–12, orçamento maior, Ads desde o dia 1, 30 dias; só produto que já vende em outro canal/conta ou sazonal); **Acelerar** (ROAS 5–6, limite em R$, unidades ou % do estoque definido antes, consulta o financeiro); **Teste** (ROAS 25, R$10–15/dia, 7–15 dias). Saída: segurar 7 dias e subir o ROAS até 20% a cada 4–5 dias (volta um degrau se a venda total cair) até a gangorra com contribuição de 30–40%. Relatório semanal do modo na quinta. | A regra que funciona não muda; a exceção tem começo, meio e fim e não fica esquecida ligada. |
| A12 | **CTR:** não existe CTR ideal fixo. Comparar com a média da própria conta. CTR baixo = problema de vitrine (capa, título, preço, frete, cupom, estrelas). CTR mede a vitrine; conversão mede a página. | Em uma categoria 1% é ótimo, em outra 12% é pouco. |
| A13 | **Referências de Ads:** leilões ganhos 30–40% (nunca buscar 100%); share de impressões 5–15% entendendo, 15–40% boa fatia, >50% algo errado, 60–70% alerta; 40–50 anúncios em Ads; ACOS alto no máximo 15–20 dias; campanhas automáticas do ML (datas, "liquida") só com o dinheiro do ML; com dinheiro próprio, desligar; bônus do ML usar (A9); desmame do Ads pela saída da A11. | Números para ler a campanha sem achismo. |
| A14 | **Planejamento:** reorganizar a estrutura de campanhas por curva 1 vez por mês. Mapa semanal de conversão (semanas 1–7, 8–14, 15–21, 22–fim): semana boa = mais orçamento e ROAS menor (só dentro dos casos da A3: gangorra ou data comercial; o resto segue o degrau de 20%); semana ruim = menos Ads, mais afiliado e ofertas — sempre dentro do teto mensal (A1). | O dinheiro vai para a semana que converte. |

## Busca e ranqueamento

| # | Regra | Por quê |
|---|---|---|
| B1 | **CPC caro:** investigar nesta ordem: 1) estoque e variação zerada; 2) CTR e conversão; 3) demanda da categoria. | Os dois primeiros você controla; o terceiro só passa com o tempo. |
| B2 | **Choque orgânico:** tirar verba do Ads e pôr em promoção primeiro; melhorar o anúncio depois. | A promoção traz venda rápida, e a venda puxa a posição. |
| B3 | **Diagnóstico de queda:** só orgânico caiu = oferta melhor do concorrente, avaliação ruim ou ruptura; só Ads caiu = orçamento ou lance; os dois = sazonalidade ou reputação. Depois ver se a concorrência também caiu (aí é o mercado). | Separa mercado, anúncio e campanha antes de mexer. |
| B4 | **Medir posição** em ferramenta por palavra-chave ou em outro aparelho, contando só orgânicos. Nunca no próprio computador (nem em aba anônima). | Histórico e cache viciam o resultado. |
| B5 | **Nota abaixo de 4,5 = alerta.** | É o número que derruba a entrega e pode travar o Ads. |
| B6 | **Estoque constante e nenhuma variação zerada.** | O ML rebaixa quem liga e desliga estoque; variação zerada derruba o anúncio todo. |
| B7 | **Alavancas de posição:** relâmpago e oferta do dia indicadas pelo ML (aproveitar quando vierem); cupom forte 1 vez por mês com estoque grande (nunca com estoque baixo); anúncio "derretido" → criar do zero em vez de ressuscitar. | Venda puxa posição; o anúncio velho carrega o histórico ruim. |
| B8 | **Referência:** conta comprada ou CNPJ novo começa do zero. | Evita expectativa errada de posição. |

## Preço e margem

| # | Regra | Por quê |
|---|---|---|
| P1 | **Preço de lista = preço-alvo × 1,30** (o preço "de", para a promoção mostrar o desconto). Conferência: ≥ 1,30. | Dá espaço para promoções sem perder margem. |
| P2 | **Margem de referência = margem realizada**: margem de contribuição (preço − comissão − frete − imposto − ferramenta − custo) **menos Ads**, do **mês fechado**, nunca a da planilha. Trava geral: **margem do mês fechado nunca abaixo de 5%.** (O teto da A1 usa a margem bruta, antes de Ads.) | Protege o mês inteiro, mesmo acelerando produtos. |
| P3 | **Margem-objetivo depende do tipo de produto e do nicho**, e cada vendedor define a sua antes de precificar. Referência da casa: **20%**. Há nichos com mais e nichos que operam com ~8%. Nunca um piso fixo único para tudo. | Regra da casa sobre quanto cada venda precisa deixar; o nicho muda o que é possível. |
| P4 | **Custo do produto = custo da próxima compra/produção**, não o da atual. | É o preço que você vai pagar para repor. |
| P5 | **Zero a zero** é permitido com teto definido antes (data, R$ ou unidades; máx. 60 dias), poucos produtos e caixa positivo. Ao bater o teto: tirar a alavanca e comparar com o período anterior; se a venda caiu, continuar com menos força; subir em degraus de ~5%. Escada zero a zero → 5–7% → margem-objetivo (P3) só para estoque grande. **Margem negativa para medalha** é permitida com limite definido antes (unidades, valor total em R$ ou % do estoque); para no primeiro que bater. Nunca margem negativa com Ads no mesmo item. Consultar quem cuida do financeiro (ou o contador) antes. | Medalha abre exposição, mas o prejuízo precisa ter tamanho conhecido antes. |
| P6 | **Subir preço em degraus de ~5%** (na segunda, quando estiver em escada); nunca 10–15% de uma vez. Olhar o mercado antes. | Sair de uma vez derruba a venda. |
| P7 | **Custo máximo de compra** = preço médio dos mais vendidos − comissão − imposto − frete, com valores reais (16% de comissão e 10% de imposto só como estimativa rápida). | Saber quanto pode pagar antes de negociar. |
| P8 | **Catálogo com preço mínimo do fabricante:** o preço não é arma; usar cupom e afiliado dentro da margem (R1). Antes de contestar o preço mínimo, levantar todos que vendem abaixo dele. | Baixar o preço gera denúncia do fabricante. |
| P9 | **Preço entre canais:** com o mesmo CNPJ, no mínimo o mesmo preço no ML, Shopee, Amazon e site. | O ML pune a visibilidade de quem vende mais barato em outro canal (não está na documentação oficial). |
| P10 | **Custo de envio ao Full por unidade** (ex.: R$100 para 20 peças = R$5/peça) entra na margem antes de mandar. Se a margem não aguenta: subir preço, cortar Ads ou esperar. | Em ticket baixo pesa muito. |

## Promoções

| # | Regra | Por quê |
|---|---|---|
| R1 | **Todo anúncio fica em promoção.** O preço base é alto (P1) e a margem é trabalhada no desconto. Existe **margem mínima** para aceitar convite (R8) e existe a conta do **pior caso**: promoção + cupom + afiliado + Ads na mesma venda contra a margem realizada. Promoção sobre o preço base; cupom e afiliado sobre o preço já com promoção. | Assim nenhuma combinação de descontos leva a venda ao prejuízo sem você saber. |
| R2 | **Desconto mínimo: 7–10%.** 5% não conta. | 5% quase não mexe na posição e o ML pode nem tratar como promoção. |
| R3 | **Oferta relâmpago:** só com estoque longo e margem conferida; mesmo conjunto por 1 semana; começar com ~5 unidades por produto. Medir o efeito depois: a venda "caiu e zerou" ou "caiu, mas manteve". Pode ser própria (Minha Página). | O que importa é o efeito depois da oferta. |
| R4 | **Ritmo:** campanhas a cada 7 dias; promoções a cada 15. **Cupom aberto só nos itens sem Ads** (cupom com código/direcionado pode em item com Ads, sempre dentro do pior caso da R1). Rebate = o ML paga parte do desconto. | Campanha reage mais rápido; em item com Ads você pagaria duas vezes pela mesma venda. |
| R5 | **Cupom:** sem teto fixo; o limite é a margem (entra no pior caso da R1). Padrão: % alto com teto baixo em R$ (ex.: 40% limitado a R$8), compra mínima abaixo do ponto em que o % bate no teto. Limites do ML: teto acima de R$5, desconto de 5% a 80%, até 31 dias, só reputação verde. 1 cupom por compra; acumula com a promoção. | O cliente vê o % alto e você gasta pouco por venda. |
| R6 | **Ordem das promoções:** 1) relâmpago e oferta do dia indicadas pelo ML; 2) campanha do ML com rebate (maior primeiro); 3) campanha do ML sem rebate (datas, banner); 4) própria, só em último caso. Sempre uma própria programada de reserva. | As do ML dão vitrine extra; no rebate o ML paga parte do desconto. |
| R7 | **Afiliado:** base de 15% sempre ligada; medir pelo que foi pago de verdade; escada 15% todos / 18% captando / 20% top 20 / 25% top 5. Em data de pico: subir (ex.: 20% → 30%) na semana anterior e encerrar 2 dias antes. Não usar em ticket baixo de compra rápida. Nunca criar conta de afiliado com o CPF do dono. | Comissão configurada não é o que você paga; os afiliados escolhem o que divulgar na semana anterior. |
| R8 | **Convite sem rebate abaixo da margem mínima = recusar.** **Margem mínima = 20% de margem realizada (P2) no pior caso, igual para todos os produtos** . A margem-objetivo (P3) pode ser maior; a mínima é o piso. Exceção: limite de zero a zero/medalha travado antes (P5). | Vitrine não paga prejuízo sem limite. |
| R9 | **Carrinho abandonado:** pelo menos 1 disparo por semana, com imagem própria (25–30% livres embaixo). Cupom de % alto e teto baixo. Só um cupom de carrinho ativo, vale para todos os anúncios e o % não se edita: para um mais forte, encerrar o atual antes. Disparo de sexta ~19h cobre o fim de semana. Entra no pior caso da R1. | É a única ferramenta de remarketing dentro do ML e alcança quem não é seguidor. |
| R10 | **Desconto por quantidade e preço de atacado:** em produto que o cliente compra em mais de uma unidade ou combina com outro — leve X pague Y, desconto na 2ª unidade (30–80%) ou em todas (10–80%), sempre com data final. Acumula com a promoção (entra no pior caso da R1). Preço de atacado (só aparece para comprador CNPJ): ativar mesmo em produto que não é B2B. | Aumenta o valor por venda sem mexer no preço base. |
| R11 | **Roteiro de estoque parado** (parado >90 dias ou começando a pagar armazenagem no Full; metas da E6): 1) entrar nas promoções disponíveis da Central, incluindo as campanhas de giro do Full; 2) afiliado com % maior nos itens de pouco giro (R7); 3) cupom "limpa estoque" para todos, só nos parados, compra mínima alta e código para divulgar; 4) liquidação pela E8; 5) sem giro no ML → canais fora do ML. Mexer na promoção, nunca no preço base. Abaixo da margem só com o limite travado antes. | Produto parado perde valor todo mês; as alavancas só cobram quando vende. |

## Anúncio

| # | Regra | Por quê |
|---|---|---|
| T1 | **Título = só palavras-chave**, tiradas dos anúncios **orgânicos** do topo e dos mais vendidos (ignorando patrocinados), incluindo público/ocasião. **Usar os 60 caracteres** (57–58 só se nada couber). **Sem conectivos ("para", "com") nem símbolos.** Palavra mais buscada no começo; a ordem das palavras muda a posição. Benefício e gatilho vão na descrição e nas imagens. | Regra da casa. |
| T2 | Anúncio que já vendeu: o ML barra trocar o título inteiro → trocar 1–3 palavras a cada ~2 dias e testar a ordem. | Mexe na posição sem perder o histórico. |
| T3 | **Título de 200 caracteres só em anúncio de catálogo.** Fora dele vale a T1. | Fora do catálogo o limite é menor. |
| T4 | **Descrição:** abrir pela dor e pela solução do cliente, depois o que é o produto. Sem limite de caracteres. Número exato no lugar de frase vaga. Fórmula do sim: motivação + proposta de valor + incentivo − confusão − ansiedade. | Anúncio técnico demais vende só por preço. |
| T5 | **Ficha técnica 100% e certa.** Campo vazio tira o anúncio do filtro; atributo errado é pior que vazio. | Ficha completa ajuda a ser encontrado e a vender. |
| C1 | **Capa diferente das capas dos concorrentes** ("vaca roxa"): ver as capas dos 10 primeiros orgânicos do termo principal e propor 3 opções que destoem. Produto em ~80%. Capa sem texto. | Capa igual às outras não chama o clique. |
| C2 | **Nunca trocar a capa de anúncio curva A.** | A troca derruba a venda por até 7 dias. |
| C3 | **Galeria:** 10 fotos é o ideal, 6–8 já é bom; sempre uma foto de garantia e uma de prova social (só verdadeira). 1200×1200. Nunca alterar o produto na imagem; nada de foto com texto em inglês. | Garantia vence o medo; prova social falsa derruba a confiança. |
| C4 | **Ordem da galeria (Story Selling):** 1 capa · 2 dor · 3 benefício principal · 4 especificações com número · 5 uso · 6 detalhe · 7 para quem é · 8 prova social · 9 garantia · 10 chamada final. | A ordem das fotos segue a ordem das objeções do cliente: emoção antes da lógica. |
| D1 | **Duplicar anúncio é permitido:** um anúncio por título diferente (combinações diferentes do banco de palavras). **Nunca dois anúncios com o mesmo título.** Comparar visitas em 15–30 dias. Anúncio antigo que perdeu posição → criar o anúncio novo do ML (MLBU). | Regra da casa. Vários anúncios com o mesmo título dão problema na conta. |
| V1 | **Variações:** juntar num anúncio. Depois de 1–2 meses, levar as paradas para outro anúncio e pôr como principal a que mais vende. Clássico e Premium juntos não é exigência. | Venda junta fortalece; variação parada atrapalha. |
| O1 | **Reforma por momento do anúncio:** novo (<14–15 dias no ar) → sem mudança forte · parado 30 dias sem venda, ou curva C/B → reforma completa de uma vez (capa, título, 10 fotos no Story Selling, descrição) · curva A → reforma de tudo menos a capa (C2) · depois da reforma, ou anúncio que vende → ajuste fino, uma mudança por vez, medindo 5–7 dias · 90–100 dias sem venda → apagar e recriar (exceto produto de necessidade: vende pouco, mas o cliente procura). Fila: 1º os sem venda há 30 dias; depois curva C e B; **curva A por último**. | Anúncio parado pesa na conta; mudar tudo junto num anúncio que vende não deixa saber o que funcionou. |
| O2 | **Alerta ≠ otimização:** alertas olham a curva A primeiro; otimização segue a O1. | O alerta protege o faturamento; a otimização começa pelo que não vende. |
| O3 | **Antes de otimizar, conferir o ML:** nota de qualidade e tarefas pendentes, moderação e infrações, perda de exposição, situação no catálogo e sugestão de preço, EAN que falta, avaliações negativas. Depois: Story Selling, título e fotos. | Não adianta trocar foto se o anúncio está travado por infração ou sem EAN. |
| W1 | **Minha Página**: revisão completa a cada 15 dias + checagem rápida na sexta (ocultar sem estoque, conferir promoções). Topo: cabeçalho (nome, banner, logo) → cupom → banner principal (novidade, oferta ou data) → produto de destaque logo depois. Limites: banner principal até 5; carrossel e galeria até 20; evitar lista de conteúdo e imagem com pins. | Página parada parece negócio morto; sem Minha Página não há Brand Ads. |
| W2 | **Identidade de marca fixa por conta** (cores, fontes, foto, tom, o que evitar, logo); o clima do produto varia dentro dela. Monte a identidade uma vez e use sempre. QR code só na embalagem física (recompra), nunca no anúncio. | O cliente precisa reconhecer a loja mesmo sem o logo. |
| W3 | **Canal de transmissão**: 1 por semana. Antes, conferir se a conta já tem o disparo automático do ML em produto em promoção. | Frequência alta faz perder seguidor; evita mandar em dobro. |

## Mercado, produto e catálogo

| # | Regra | Por quê |
|---|---|---|
| M1 | Procurar o "lado B" (vendedores crescendo contra o mercado), não copiar o líder. 3 vendedores crescendo com a mesma marca = sinal forte. Full/Ads acima de 80–90% numa faixa é barreira, não demanda. | Copiar o líder é entrar onde a briga já está perdida. |
| M2 | Pirâmide de preços dos 100 mais vendidos; kit para mudar de faixa (frete grátis ~R$79). **Estoque inicial** pelo tamanho do mercado: o mais vendido vende 100 → entrar com ~15; vende 1.000 → entrar com ~100 (não % fixo). Comprar fora do pico. | Em mercado grande, % fixo é demais para um teste. |
| M3 | **Estudo de mercado com histórico:** baixar e guardar 6 meses de relatórios; participação mensal por subcategoria; varredura da busca toda segunda (páginas 1–5, 250 anúncios) por 3–4 semanas. Anúncio novo com 100 vendas em 50–70 dias = tendência acelerando. | O ML apaga o histórico; crescer menos que o mercado é perder espaço. |
| M4 | **Importação:** AliExpress para teste (5–10 unidades); Alibaba para lote. Conferir a taxa de importação de compra pequena antes de cada compra. | Depende da regra de imposto do momento. |
| K1 | **Catálogo:** reputação, logística (Full) e preço decidem; com preço mínimo do fabricante, o preço sai da disputa (P8). Ads em catálogo só se ganha ~90% do tempo. Não vincular orgânico que já vende a catálogo que não é seu. Não pôr duas contas próprias no mesmo catálogo. | O orgânico desliga e o catálogo não herda o histórico. |
| K2 | **Nunca:** alugar catálogo, EAN falso, baixar o preço para expulsar quem entrou. | Risco de conta e de nunca mais recuperar o preço. |
| K3 | **Revenda de marca de terceiro**: carta só da própria marca (a do distribuidor não vale); nunca esconder a marca. | Com o código de barras certo a denúncia pega igual, e o ML não discute denúncia. |
| K4 | **Fugir do catálogo = kit com item exclusivo que resolve algo**, marca registrada ou proteção de preço negociada. Kit exclusivo e marca própria podem subir como **catálogo novo**. Kit de quantidade só em commodity ou para mudar de faixa de frete. Conteúdo adicional no catálogo só com marca deferida no INPI (conferir antes). | Kit de quantidade qualquer um copia; sem marca deferida o catálogo é do ML. |

## Estoque

| # | Regra | Por quê |
|---|---|---|
| E1 | **Quando pedir:** estoque ÷ venda média por dia − prazo do fornecedor. Zero ou menos = atrasado. Não contar estoque em trânsito nem o não liberado no Full. Estoque de segurança só para venda irregular. | Conta simples, feita por produto. |
| E2 | **Venda média de 30 e 7 dias;** se o item vai para Ads, usar a venda esperada. | O Ads muda o ritmo de venda. |
| E3 | **Quanto mandar ao Full:** começar abaixo do melhor dia e subir; pedidos ao Full de ~15 dias; nunca picadinho. Recomendação do ML só para conferir. Receber na 3ª semana do mês para chegar no início do seguinte. | Picadinho trava o Full e aumenta custo; a 3ª semana costuma ser de queda. |
| E4 | **Produto novo vende por fora primeiro;** Full só depois de provar venda. Exceção: produto de data comercial. Full só para o que gira. | Não pagar armazenagem de produto que ainda não provou venda. |
| E5 | **Black Friday: preparar em junho e julho.** Sazonalidade com meses de antecedência (importação ~160 dias). Comparar com o ano anterior antes de agir. | A nota do Full olha 60 dias e o Full trava o recebimento perto da data. |
| E6 | **Estoque demais:** meta até 60 dias; alerta acima de 90; 6 meses é grave. Full: limpar a partir de 45 dias parado. | Estoque parado perde 5–10% por mês e, no Full, ainda paga armazenagem. |
| E7 | **Ruptura:** vai acabar → subir o preço; Full rompeu no pico → estoque próprio na hora. Faltar é pior que sobrar. | Subir preço faz o estoque durar até a reposição; no pico não dá para esperar. |
| E8 | **Liquidação:** cupom de valor fixo travado pelo orçamento (ex.: R$49 com orçamento de R$490 = 10 unidades). Cupom e afiliado antes de Ads. Nunca com estoque raso. | Você controla exatamente quantas unidades saem com desconto. |
| E9 | **Flex:** raio de 10–20 km; 30–40 km para tomar mercado; compensa em capital e região metropolitana. | No interior vende pouco e sai caro. |
| E10 | **Caixa da compra:** comprar para ~30 dias e pedir para ~15 (com pedidos ao Full de ~15 dias, E3). Dias de estoque de cada pedido = prazo do boleto − dias até o dinheiro cair (dias reais da conta; sem medição, 20 dias). À vista só se o estoque acaba em menos de 1 mês e o desconto é maior que o custo do dinheiro. Compra grande: consultar o CFO. | Boleto 30 e dinheiro em 14 = comprar 16 dias; número fixo pode deixar o caixa negativo. |
| E11 | **Meta: 80% dos produtos no Full ou Flex.** | Entrega rápida pesa na posição e na conversão. |
| E12 | **Data comercial em 7 passos**: plano por fase com Ads, Full e promoção; promoção mais forte na reta final; dobrar o orçamento de Ads a cada 2 dias no pico; afiliado pela R7. Usar o ritmo de vendas das 52 semanas do ano para a sazonalidade. | Uma sequência só, sem improviso na data. |
| E13 | **ABC-XYZ e fórmulas estatísticas** ficam só como apoio de cálculo. | A regra que vale é a do método. |

## Proteção da conta

| # | Regra | Por quê |
|---|---|---|
| S1 | **Bug de conta ou reclamação injusta:** chamado todo dia (mínimo a cada 3–4 dias), por e-mail quando houver opção, sempre cobrando o anterior. Dossiê escrito por conta com o número de cada chamado. | O número do chamado é a prova que o ML aceita depois. |
| S2 | **Conta bloqueada:** depois dos chamados, notificação extrajudicial ao ML com os números de chamado, para abrir conversa. Processo só por decisão do dono da conta. Denúncia vinda do fornecedor → cobrar o fornecedor. | Abre conversa sem a briga e o custo de um processo. |
| S3 | **Várias contas no mesmo documento = risco**, não regra do ML (há caso de várias contas bloqueadas pelo mesmo CPF; a documentação não confirma). Conferir se as contas têm o mesmo representante (CPF). Outra conta só como backup ou teste de nicho. | A regra não é pública, mas o caso real mostra o efeito. |
| S4 | **Duas contas próprias:** pode ter o mesmo produto nas duas. A conta do foco do produto é a **principal** (mais barata e com Ads); a outra é de **apoio**: sem a mesma promoção, nunca com preço menor que a principal e nunca no mesmo catálogo. | Com papéis definidos as contas não brigam no leilão nem no preço pelo mesmo cliente. |
| S5 | **Denúncia de marca:** responder com documentos antes da data limite. Guardar a nota fiscal. | Sem resposta no prazo, o ML remove o anúncio. |
| S6 | **Devolução:** ~2% é normal; acima de 5% é ruim. | Devolução come margem direto. |
| S7 | **Gerente de contas** é só referência: não depende de faturamento, e o pago ajuda pouco. | Não muda nenhuma ação. |

## Rotina

| # | Regra | Por quê |
|---|---|---|
| Q1 | **Um calendário só** (abaixo). Os agentes seguem o calendário aprovado; nenhuma outra agenda semanal vale. | Duas agendas fazem cada agente agir num dia. |
| Q2 | **Referência de equipe:** um analista cuida de até 250 anúncios ativos. Acima disso = anúncio sem dono e preço velho. | Muito anúncio por pessoa vira preço desatualizado. |
| Q3 | **80/20:** 20% das categorias e anúncios trazem 80% do resultado — concentrar a análise ali. | É onde a análise rende. |
| Q4 | **Consultar quem cuida do financeiro (ou o contador)** antes de: compra grande de estoque, antecipar recebíveis, acelerar com margem negativa. Antecipar não é rotina. | São decisões de caixa da empresa inteira, não só do ML. |

**Calendário**

- **Diário (dia útil):** termômetro, reclamações abertas e ruptura dos líderes; perguntas respondidas em no máximo 20 min, avaliações respondidas, convite de avaliação até 48 h; chamados do dossiê (S1). Sábado e domingo: só urgências.
- **Segunda:** Ads — detratores em 30 e 7 dias, sobe e desce de curva; varredura da busca, páginas 1–5; preço +~5% quando em escada; anúncios sem promoção.
- **Terça:** otimização de anúncios na ordem O1.
- **Quarta:** catálogo (tirar de Ads o catálogo perdido) e rentabilidade.
- **Quinta:** estoque, ruptura e Full; relatório do modo especial de Ads.
- **Sexta:** checagem da Minha Página, reclamações e reputação; canal de transmissão e disparo de carrinho abandonado, R9.
- **Quinzenal:** curva B de Ads; revisão das promoções; Minha Página completa; retirar produtos das campanhas (a cada 15–30 dias).
- **Mensal:** curva C e reorganização das campanhas de Ads; fechamento da margem do mês; dia 20 do orçamento (A9); participação por subcategoria e relatório de mercado; faxina 30/90–100 dias; 3ª semana: receber produto para o Full; auditoria do catálogo e da taxa de avaliação por SKU.

---


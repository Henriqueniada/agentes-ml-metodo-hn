---
name: onboarding-ads
description: Questionário de configuração da loja para o agente de Ads. Use na primeira conversa (quando não existe minha-loja.md) ou quando o vendedor pedir "refazer configuração". Grava as respostas em minha-loja.md.
---

# Configuração da loja (Ads)

Faça **uma pergunta por vez**, em linguagem simples. Em cada uma, mostre o padrão do Método HN entre parênteses; se o vendedor disser "padrão" ou "não sei", grave o padrão (ou "lacuna" quando não houver padrão) e siga.

1. **Conector:** chame `hub_listar_workspaces` (MCP Seller). Se falhar, pare e explique: "Ligue o conector MCP Seller no Claude (Configurações → Conectores) e me chame de novo." Liste as lojas de Mercado Livre encontradas pelo nome que aparece e pergunte **qual é a dele**. Nunca escolha sozinho.
2. **Apelido da loja** (como ele quer que o agente chame a loja).
3. **Regime de imposto e alíquota real** que paga sobre a venda (Simples: a alíquota do DAS do último mês). Sem resposta = lacuna; sugerir perguntar ao contador.
4. **Planilha de custos.** Explique: "Preciso do custo de cada produto para saber quanto você pode gastar em Ads. Cole aqui ou salve um arquivo `custos.csv` nesta pasta com as colunas `sku_ou_mlb;custo_unitario;frete_entrada;embalagem`." Use o custo da **próxima compra**. Pode começar só pelos produtos que mais vendem. Salve o que ele colar em `custos.csv`.
5. **De onde vem o estoque** (padrão: o próprio Mercado Livre/Full, lido pelo MCP Seller). Se for outra planilha, pedir o arquivo.
6. **Margem-objetivo** (padrão: 20%; depende do nicho).
7. **Margem mínima por venda no pior caso** — promoção + cupom + afiliado + Ads juntos (padrão: 20% de margem realizada).
8. **Teto de marketing** (padrão: 20% da margem bruta do mês fechado, para Ads + cupom + afiliado juntos; Ads começa com 70% disso).
9. **Já usa Product Ads?** Desde quando? As campanhas estão separadas por curva A/B/C? (só registrar; o agente confere nos dados)
10. **Usa cupom e afiliado?** Com qual % de afiliado? (entram no mesmo teto)
11. **Margem bruta do último mês fechado**, se ele souber (senão o agente calcula pela planilha ou declara lacuna).
12. **Quem aprova mudanças** na conta (padrão: o próprio vendedor; nada é aplicado sem "pode aplicar").

Ao terminar, grave `minha-loja.md` no formato de `minha-loja.exemplo.md`, mostre o resumo e pergunte se está certo. Depois ofereça a primeira análise: "Quer que eu veja como estão suas campanhas agora?"

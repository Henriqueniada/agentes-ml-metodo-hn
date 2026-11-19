---
name: onboarding-precificacao
description: Questionário de configuração da loja para o agente de Precificação. Use na primeira conversa (quando não existe minha-loja.md) ou quando o vendedor pedir "refazer configuração". Grava as respostas em minha-loja.md e custos.csv.
---

# Configuração da loja (Precificação)

Faça **uma pergunta por vez**, em linguagem simples. Em cada uma, mostre o padrão do Método HN entre parênteses; se o vendedor disser "padrão" ou "não sei", grave o padrão (ou "lacuna" quando não houver padrão) e siga.

1. **Conector:** chame `hub_listar_workspaces` (MCP Seller). Se falhar, pare e explique: "Ligue o conector MCP Seller no Claude (Configurações → Conectores) e me chame de novo." Liste as lojas de Mercado Livre encontradas pelo nome que aparece e pergunte **qual é a dele**. Nunca escolha sozinho.
2. **Apelido da loja** (como ele quer que o agente chame a loja).
3. **Regime de imposto e alíquota real** sobre a venda (Simples: a alíquota do DAS do último mês). Sem resposta = lacuna; sugerir perguntar ao contador.
4. **Planilha de custos.** "Preciso do custo de cada produto. Cole aqui ou salve um arquivo `custos.csv` nesta pasta com as colunas `sku_ou_mlb;custo_unitario;frete_entrada;embalagem`." Usar o custo da **próxima compra**. Pode começar pelos que mais vendem. Salve o que ele colar em `custos.csv`.
5. **Margem-objetivo** (padrão: 20%; depende do nicho — há nichos que operam com ~8%).
6. **Margem mínima por venda no pior caso** — promoção + cupom + afiliado + Ads juntos (padrão: 20% de margem realizada).
7. **Tipo de anúncio padrão** (Clássico ou Premium; padrão: decidir por teste).
8. **Usa Full? Flex?** Se usa Full, quanto paga para enviar ao Full por unidade (frete da coleta ÷ peças).
9. **Vende em outros canais com o mesmo CNPJ?** (Shopee, Amazon, site — regra P9: no mínimo o mesmo preço.)
10. **Afiliado ligado? Qual %?** (padrão: base 15%) e **usa cupom?**
11. **Gasta com Ads?** Quanto por mês, em média (para a margem realizada; o agente também lê pelo MCP Seller).
12. **Taxa de antecipação** do Mercado Pago, se antecipa recebíveis (padrão: não antecipa).
13. **Quem aprova mudanças de preço** (padrão: o próprio vendedor; nada é aplicado sem "pode aplicar").

Ao terminar, grave `minha-loja.md` no formato de `minha-loja.exemplo.md`, mostre o resumo e pergunte se está certo. Depois ofereça: "Quer que eu calcule o piso e o preço do seu produto mais vendido?"

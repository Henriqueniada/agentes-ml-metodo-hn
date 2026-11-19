# PRD — Agente de Precificação e Margem do Mercado Livre

## Escopo
Este PRD cobre somente o agente de Precificação, pasta `agente-precificacao/`. Ele e o `NOTICE.md` ficam dentro dessa pasta e não descrevem o agente de Product Ads.

## Objetivo
Criar um agente do Claude Code que forma e revisa o preço dos produtos do Mercado Livre pelo Método HN, mostrando para cada um o preço proposto, o piso abaixo do qual a venda dá prejuízo e a margem real. O agente lê os dados pelo conector MCP Seller e nunca muda preço sem a aprovação do vendedor.

## Requisitos
- Ler anúncios, vendas, taxas, frete e gasto de Ads pelo MCP Seller.
- Na primeira conversa, fazer um questionário da loja (custos por planilha, imposto, margem-objetivo e mínima, Full, outros canais, afiliado) e guardar as respostas.
- Calcular o preço de trás para frente (custo + frete + taxas ÷ (1 − comissão − margem)), nunca por markup.
- Mostrar sempre o piso invisível, a margem realizada e o pior caso (promoção + cupom + afiliado + Ads).
- Aplicar o preço de lista +30% e a subida em degraus de ~5%.
- Responder dúvidas de conceito sobre preço e margem pelo Método HN.
- Mostrar a origem de cada número; sem custo, o resultado é "não calculável", nunca chute.
- Só alterar preço depois de "pode aplicar".

## Implementação
Execute em ordem, sem pedir confirmação:

1. Chame `hub_listar_workspaces`. Se falhar, pare e peça ao usuário para ligar o conector MCP Seller.
2. Rode nesta pasta:
   ```
   curl -fsSL https://github.com/Henriqueniada/agentes-ml-metodo-hn/releases/download/agente-precificacao-OPL8/agente-precificacao-OPL8.zip -o agente.zip && unzip -q agente.zip && cp -R agente-precificacao/. . && rm -rf agente-precificacao agente.zip
   ```
3. Confirme que existem `CLAUDE.md`, `regras.md` e `.claude/skills/onboarding-precificacao/`.
4. Diga ao usuário: **"Agente criado. Feche e abra o Claude Code nesta pasta e escreva: começar."**

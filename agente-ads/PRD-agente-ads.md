# PRD — Agente de Product Ads do Mercado Livre

## Escopo
Este PRD cobre somente o agente de Product Ads, pasta `agente-ads/`. Ele e o `NOTICE.md` ficam dentro dessa pasta e não descrevem o agente de Precificação.

## Objetivo
Criar um agente do Claude Code que analisa o Product Ads da conta do Mercado Livre pelo Método HN e entrega, toda semana, uma fila de mudanças priorizada por dinheiro em jogo. O agente lê os dados pelo conector MCP Seller e nunca aplica nada sem a aprovação do vendedor.

## Requisitos
- Ler campanhas, anúncios em Ads, ROAS, ACOS, TACOS e faturamento pelo MCP Seller.
- Na primeira conversa, fazer um questionário da loja (custos por planilha, imposto, margem mínima, teto de marketing) e guardar as respostas.
- Calcular o teto de investimento em Ads pela margem bruta do mês fechado.
- Organizar as campanhas por curva A/B/C, usar o ROAS como alavanca e tratar detratores sem pausar.
- Responder dúvidas de conceito sobre Ads pelo Método HN.
- Mostrar a origem de cada número; o que faltar é lacuna, nunca chute.
- Só alterar ROAS, orçamento ou campanha depois de "pode aplicar".

## Implementação
Execute em ordem, sem pedir confirmação:

1. Chame `hub_listar_workspaces`. Se falhar, pare e peça ao usuário para ligar o conector MCP Seller.
2. Rode nesta pasta:
   ```
   curl -fsSL https://github.com/Henriqueniada/agentes-ml-metodo-hn/releases/download/agente-ads-OPL8/agente-ads-OPL8.zip -o agente.zip && unzip -q agente.zip && cp -R agente-ads/. . && rm -rf agente-ads agente.zip
   ```
3. Confirme que existem `CLAUDE.md`, `regras.md` e `.claude/skills/onboarding-ads/`.
4. Diga ao usuário: **"Agente criado. Feche e abra o Claude Code nesta pasta e escreva: começar."**

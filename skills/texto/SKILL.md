---
name: texto
description: Escreve texto na voz do dono — e-mail importante, proposta, comunicado, post. Use quando o texto precisa parecer escrito por ele.
---

# /texto

Delegue ao agente **Redator** (`.claude/agents/redator.md`) com o pedido completo. Fluxo:

1. Redator lê a voz em `escritorio.md` (ou calibra com 3 perguntas na primeira vez e grava).
2. Texto importante → 2 versões de tom pro dono escolher.
3. Texto que sai do escritório (cliente/público) → parecer do **Revisor** + aprovação explícita do dono ANTES de ser dado como pronto. Regra inviolável: nada público sem aprovação humana.

Salvar em `entregaveis/AAAA-MM-DD_texto_<assunto>.md`.

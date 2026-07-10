---
name: painel
description: Gera/atualiza o Painel do Escritório — página HTML com plano do dia, entregáveis e pendências. Use pra ver o estado do escritório numa tela.
---

# /painel

Gere/atualize `painel/painel.html` — página estática, autocontida (CSS inline, sem libs externas), legível em desktop e celular.

**Conteúdo (nesta ordem):**
1. Saudação + data por extenso (derive o dia da semana por código/cálculo, nunca de memória)
2. **Hoje:** as prioridades vigentes (do Chefe de Gabinete) + próximas reuniões conhecidas
3. **Entregáveis:** últimos 7 dias da pasta `entregaveis/` (nome + data, mais recente primeiro)
4. **Pendências:** o que está aguardando o dono ou aguardando terceiros
5. Rodapé: "atualizado às HH:MM"

**Estilo:** fundo branco, texto quase-preto, UMA cor de destaque (azul escuro), tipografia do sistema, zero enfeite. Depois de gerar, diga o caminho do arquivo pro dono abrir (ou abra, se possível).

Este painel é atualizado também pelo `/fechamento-do-dia` — mantenha o mesmo formato pra não quebrar o hábito visual.

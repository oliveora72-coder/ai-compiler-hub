<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

# Lovable task

A sensibilidade atual está perfeita como base, mas em alguns momentos fica pesada demais. Ainda existe um pouco de aceleração no movimento e isso precisa ser removido para deixar a resposta consistente.

Também há lags no mapeador durante a partida, principalmente no meio do game. Investigue e corrija a causa desses lags, otimizando o processamento do mapeamento/overlay para manter a resposta estável e sem travamentos.

Requisitos:
- Manter a sensibilidade atual como referência; não alterar desnecessariamente o que já está bom.
- Corrigir os momentos em que a sensibilidade fica pesada.
- Remover completamente a aceleração do movimento.
- Corrigir os lags do mapeador durante o jogo.
- Priorizar baixa latência, resposta consistente e estabilidade do overlay.
- Não remover funcionalidades existentes.

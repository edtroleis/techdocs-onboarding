# Fluxo de trabalho

```text
Demanda ─▶ Refinamento ─▶ Desenvolvimento ─▶ Revisão ─▶ Validação ─▶ Produção
```

## Etapas

| Etapa | O que acontece | Evidência |
|-------|----------------|-----------|
| Demanda | Item criado no board com contexto e critério de aceite | Item no board |
| Refinamento | Time estima e quebra em tarefas pequenas | Tarefas vinculadas |
| Desenvolvimento | Branch curta, testes junto do código | Commits / PR |
| Revisão | Pelo menos 1 aprovação; CI verde | PR aprovado |
| Validação | Testes em staging; aceite do produto | Registro do aceite |
| Produção | Deploy pelo pipeline, com rollback documentado | Registro do deploy |

Para serviços, o caminho técnico detalhado está no
[Golden Path para Serviços](http://localhost:3000/docs/default/component/golden-path-servicos).

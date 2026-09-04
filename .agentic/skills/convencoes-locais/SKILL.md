---
name: convencoes-locais-app-poc-1
description: Use esta skill ao editar componentes React/TSX ou testes neste repositorio (app-poc-1). Cobre convencao de nomenclatura de componente/teste e o que nunca deve ser editado manualmente.
---

# Convenções deste repositório (app-poc-1)

Esta skill é local — só existe neste repo, soma-se às skills da platform,
e nunca é vista pelos outros repos da demanda.

## Stack específico
Componentes seguem o padrão de nome `Componente.tsx` + `Componente.test.tsx`
lado a lado. Testes usam Testing Library, nunca enzyme.

## Onde NÃO mexer sem aprovação
`src/design-tokens/` é gerado a partir do Gelada — qualquer edição manual
é sobrescrita no próximo sync e não deve ser tentada pelo agente.

---
name: convencoes-locais-app-poc-1
description: Use esta skill ao editar componentes ou testes neste repositorio (app-poc-1). Complementa a skill generica de React da platform com detalhes especificos deste projeto.
---

# Convenções deste repositório (app-poc-1)

Esta skill é local — só existe neste repo, soma-se às skills da platform
(incluindo `react-boas-praticas`), e nunca é vista pelos outros repos.

## Este repositório
Hello world React + Vite, JavaScript puro (sem TypeScript), testado com
Vitest + Testing Library. Ponto de entrada em `src/main.jsx`, componente
raiz em `src/App.jsx`.

## Convenção de arquivo
Componente e teste lado a lado: `Componente.jsx` + `Componente.test.jsx`.

## Onde não mexer sem aprovação
Não há design system integrado ainda neste hello world — se uma demanda
futura pedir estilo, pergunte antes de introduzir uma biblioteca de CSS.

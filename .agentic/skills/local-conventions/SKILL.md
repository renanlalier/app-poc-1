---
name: local-conventions-app-poc-1
description: Use this skill when editing components or tests in this repository (app-poc-1). Complements the platform's generic React skill with project-specific details.
---

# Repository conventions (app-poc-1)

This skill is local — it exists only in this repo, supplements the platform
skills (including `react-best-practices`), and is never visible to other repos.

## This repository
Hello-world React + Vite, plain JavaScript (no TypeScript), tested with
Vitest + Testing Library. Entry point at `src/main.jsx`, root component at
`src/App.jsx`.

## File convention
Component and test side by side: `Component.jsx` + `Component.test.jsx`.

## Do not change without approval
There is no integrated design system in this hello world yet — if a future
demand asks for styling, ask before introducing a CSS library.

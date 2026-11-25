# Avaliação GitHub Actions

Repositório criado para a avaliação de **GitHub Actions** da disciplina de Prática Profissional Desenvolvimento.

## Workflow de Verificação

Este repositório possui o workflow `.github/workflows/verificacao.yml` que:

- Dispara automaticamente em `push` no branch `main`
- Também pode ser executado manualmente (`workflow_dispatch`)
- Faz checkout do código com `actions/checkout@v4`
- Verifica se o arquivo `README.md` existe na raiz
- Escreve o RA e o SHA do commit no resumo do job (`GITHUB_STEP_SUMMARY`)

### Badge de status

[![Verificação](https://github.com/myronmaciell/github-actions/actions/workflows/verificacao.yml/badge.svg)](https://github.com/myronmaciell/github-actions/actions/workflows/verificacao.yml)
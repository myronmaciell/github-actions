# Avaliação GitHub Actions

Repositório criado para a avaliação de **GitHub Actions** da disciplina de Desenvolvimento / ADS.

## Workflow de Verificação

Este repositório possui o workflow `.github/workflows/verificacao.yml` que:

- Dispara automaticamente em `push` no branch `main`
- Também pode ser executado manualmente (`workflow_dispatch`)
- Faz checkout do código com `actions/checkout@v4`
- Verifica se o arquivo `README.md` existe na raiz
- Escreve o RA e o SHA do commit no resumo do job (`GITHUB_STEP_SUMMARY`)

### Badge de status

[![Verificação](https://github.com/myronmaciell/https://github.com/myronmaciell/github-actions/actions/workflows/verificacao.yml/badge.svg)](https://github.com/myronmaciell/https://github.com/myronmaciell/github-actions/actions/workflows/verificacao.yml)

## Como usar

1. Faça o push deste `"README.md` junto com o arquivo do workflow.
2. Após a primeira execução bem-sucedida, substitua o badge acima pelo badge gerado na aba **Actions** do repositório (botão `...` → Create status badge).
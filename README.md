# 🛠️ Insiders GitHub Workflow

![CI](https://github.com/WallanDavid/insiders-github-workflow/actions/workflows/ci.yml/badge.svg)

Este projeto demonstra como usar **GitHub Actions** para validar um script Node.js com CI automático.

## ✅ O que você vai ver aqui

- CI rodando a cada commit e pull request
- Badge de status do GitHub Actions
- Código simples em `Node.js`
- Workflow criado direto no **VS Code Insiders**

## 🧪 Como funciona

A cada `push` ou `pull_request`, o GitHub:
1. Instala o Node.js
2. Faz checkout do código
3. Valida `src/app.js` com `node --check`

---

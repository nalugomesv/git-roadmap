# 🌿 Módulo 02 – Branching, Commits e Workflows

🎯 **Objetivo:** Aprender como criar branches, seguir padrões de commits e usar workflows de desenvolvimento colaborativo.

---

## 📚 Materiais Recomendados
- 📄 [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/)
- 📄 [Git Flow – Guia Completo](https://nvie.com/posts/a-successful-git-branching-model/)
- 📄 [GitHub Flow – Workflow Simplificado](https://guides.github.com/introduction/flow/)

---

## 🌿 Branching

### 🔹 Convenção sugerida:
- `feature/nome-da-funcionalidade`
- `fix/nome-do-bug`
- `docs/nome-da-doc`
- `refactor/nome-da-alteracao`

### ✅ Exercício:
1. Criar uma branch `feature/minha-primeira-feature`
2. Fazer pelo menos 2 commits nela
3. Abrir um Pull Request no repositório forkado

---

## 📝 Commits

### 🔹 Padrão de Commits Semânticos (Conventional Commits)

Formato:  
```

<tipo>: descrição curta

```

Exemplos:  
- `feat: adicionar função de busca de usuários`
- `fix: corrigir bug na função de login`
- `docs: atualizar README com exemplos`

Tipos mais usados:  
- `feat` – nova funcionalidade  
- `fix` – correção de bug  
- `docs` – documentação  
- `style` – ajustes de formatação  
- `refactor` – refatoração de código  
- `test` – criação/alteração de testes  

---

## 🔄 Workflows

### 📌 GitHub Flow (simples)
1. Criar branch a partir da `main`
2. Commitar mudanças
3. Abrir Pull Request
4. Revisar e fazer merge na `main`

### 📌 Git Flow (projetos mais complexos)
- Branches principais: `main`, `develop`
- Branches auxiliares: `feature/`, `release/`, `hotfix/`

---

## 🚀 Desafio do Módulo
- Criar uma branch no seu fork
- Fazer pelo menos **3 commits semânticos**
- Abrir um Pull Request neste repositório adicionando seu nome no arquivo `contributors.md`

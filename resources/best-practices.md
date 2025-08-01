# ✅ Boas Práticas de Versionamento

Este arquivo serve como **guia rápido** de boas práticas para Git, GitHub e GitLab.

---

## 🌿 Convenção de Branches

| Tipo       | Prefixo   | Exemplo                        |
|------------|-----------|--------------------------------|
| Feature    | `feature/`| feature/adicionar-login        |
| Bug Fix    | `fix/`    | fix/corrigir-erros-de-login    |
| Docs       | `docs/`   | docs/atualizar-readme          |
| Refactor   | `refactor/`| refactor/melhorar-performace |
| Test       | `test/`   | test/adicionar-testes-unitarios|

---

## 📝 Padrão de Commits (Conventional Commits)

Formato:  
```

<tipo>: descrição curta

```

Exemplos:  
- `feat: adicionar funcionalidade de exportação`
- `fix: corrigir erro ao carregar lista de usuários`

Tipos mais usados:  
- `feat` – nova funcionalidade  
- `fix` – correção de bug  
- `docs` – documentação  
- `style` – ajustes de formatação  
- `refactor` – refatoração de código  
- `test` – testes  

---

## 🔄 Workflows Recomendados

### 🔹 GitHub Flow (simples e popular)
1. Criar branch a partir da `main`
2. Fazer commits seguindo boas práticas
3. Abrir Pull Request
4. Revisar e fazer merge

### 🔹 Git Flow (para projetos complexos)
- Branches principais: `main` (produção), `develop` (desenvolvimento)
- Branches auxiliares:
  - `feature/` → novas funcionalidades
  - `release/` → preparação para release
  - `hotfix/` → correções críticas em produção

---

## 📌 Dicas Gerais
✅ Commits pequenos e objetivos  
✅ Mensagens de commit no **imperativo** (ex.: "adicionar função", não "adicionando função")  
✅ Sempre atualizar sua branch antes de abrir PR/MR (`git pull origin main`)  
✅ Usar Pull Requests/Merge Requests para revisão de código  

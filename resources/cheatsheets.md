# 📄 Git Cheatsheet

Um guia rápido com os **principais comandos do Git**, organizado por contexto de uso.

---

## 📌 Configuração Inicial

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
git config --global init.defaultBranch main
````

---

## 📂 Criando e Clonando Repositórios

```bash
git init                      # Inicializa um novo repositório Git
git clone <url>               # Clona um repositório existente
```

---

## 📄 Status e Histórico

```bash
git status                    # Mostra o status dos arquivos
git log                       # Exibe o histórico de commits
git log --oneline --graph     # Histórico resumido com gráfico de branches
```

---

## ➕ Adicionando e Confirmando Alterações

```bash
git add <arquivo>             # Adiciona arquivo específico
git add .                     # Adiciona todas as alterações
git commit -m "mensagem"      # Cria um commit com mensagem
git commit -am "mensagem"     # Adiciona e commita de uma vez (somente arquivos já rastreados)
```

---

## 🌿 Trabalhando com Branches

```bash
git branch                    # Lista branches locais
git branch <nome>             # Cria uma nova branch
git checkout <branch>         # Troca para a branch
git checkout -b <branch>      # Cria e muda para a branch
git merge <branch>            # Faz merge de uma branch na atual
```

---

## ⬆️ Sincronizando com Repositórios Remotos

```bash
git remote add origin <url>   # Adiciona um repositório remoto
git remote -v                 # Lista remotos configurados
git push -u origin main       # Envia branch main para o remoto
git pull                      # Baixa e mescla alterações remotas
git fetch                     # Baixa alterações sem mesclar
```

---

## 🔄 Desfazendo Alterações

```bash
git restore <arquivo>         # Desfaz alterações não adicionadas ao stage
git reset <arquivo>           # Remove arquivo do stage
git reset --soft HEAD~1       # Remove último commit, mantendo alterações
git reset --hard HEAD~1       # Remove último commit e alterações
```

---

## 🏷️ Tags

```bash
git tag                       # Lista tags
git tag <nome>                # Cria uma nova tag
git push origin <nome-tag>    # Envia a tag para o remoto
```

---

## 🔗 Stash (Guardar Alterações Temporárias)

```bash
git stash                     # Salva alterações temporariamente
git stash list                # Lista stashes
git stash pop                 # Recupera e remove o último stash
git stash apply               # Recupera o stash sem removê-lo
```

---

## 📚 Fluxo Básico de Contribuição (Fork + PR)

```bash
git clone <fork-url>          # Clona seu fork
git checkout -b minha-feature # Cria uma branch para a feature
git add . && git commit -m "feat: adds new feature"
git push origin minha-feature # Envia para seu fork
```

Depois, **abra um Pull Request** no repositório original 🚀

---

## 🔗 Recursos Úteis

* [Documentação Oficial do Git](https://git-scm.com/doc)
* [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/)
* [Git Branching Playground](https://learngitbranching.js.org/?locale=pt_BR)

---

>💡 **Dica:** Use `git help <comando>` para abrir a ajuda de qualquer comando Git no terminal.

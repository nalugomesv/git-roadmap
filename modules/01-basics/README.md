# 📘 Módulo 01 – Git Básico

>Neste módulo, você vai aprender o básico sobre o Git: o que é, como instalar, configurar e usar seus principais comandos. Ao final, você saberá iniciar um repositório, versionar arquivos e interagir com repositórios remotos. É o primeiro passo para usar o Git no dia a dia.

## 🎯 Objetivos
✅ Entender o que é controle de versão  
✅ Instalar e configurar o Git  
✅ Aprender comandos essenciais (`init`, `clone`, `add`, `commit`, `push`, `pull`, `status`, `log`)  

---

## 📖 Materiais Recomendados

*Escolha os recursos que melhor se adaptam ao seu estilo de aprendizagem:*

**Se você aprende melhor lendo**
- 📄 [Pro Git (Capítulos 1 e 2)](https://git-scm.com/book/pt-br/v2)
- 📄 [Guia Rápido do Git](https://rogerdudler.github.io/git-guide/index.pt_BR.html)

**Se você aprende melhor com vídeos**
- 🎥 [Entendendo GIT | (não é um tutorial!)](https://www.youtube.com/watch?v=6Czd1Yetaac)
- 🎥 [GIT: Minicurso para Você Sair do Zero! (Aprenda em 45 Minutos)](https://www.youtube.com/watch?v=ts-H3W1uLMM)
- 🎥 [Git e GitHub](https://www.youtube.com/playlist?list=PLhkO7OMKgT_rqwGYldqcFxyN4yjFgmDh8)
- 🎥 [Curso de Git e Github [Completo] - Aprenda o Essencial em 2 horas](https://www.youtube.com/watch?v=192HgwRgOYE)


---

## 📝 Checklist do módulo:

* [ ] **Criar uma conta no GitHub**
  Acesse [github.com](https://github.com/) e registre-se para obter uma conta gratuita, que será usada para hospedar seus repositórios remotos.

* [ ] **Instalar o Git**
  Baixe e instale o Git no seu sistema a partir de [git-scm.com](https://git-scm.com/). Verifique a instalação com `git --version`.

* [ ] **Configurar seu usuário no Git**
  Use o mesmo nome de usuário e e-mail da sua conta no GitHub para que seus commits sejam associados corretamente:

  ```bash
  git config --global user.name "Seu Nome"
  git config --global user.email "seu@email.com"
  ```

* [ ] **Configurar chaves SSH para acesso ao GitHub**
  Configure uma chave SSH para autenticação segura sem senha. Consulte o guia oficial:
  [Configurar SSH no GitHub](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh)

* [ ] **Criar um repositório local e fazer seu primeiro commit**
  Use `git init` para iniciar o repositório e depois:

  ```bash
  git add .
  git commit -m "mensagem do commit"
  ```

* [ ] **Criar um repositório remoto e adicionar ao seu repositório local**
  Crie um novo repositório no GitHub ou GitLab (sem README) e conecte com:

  ```bash
  git remote add origin URL_DO_REPO
  ```

* [ ] **Fazer o primeiro push para o repositório remoto**
  Envie seus commits locais com:

  ```bash
  git push -u origin main
  ```

* [ ] **Clonar um repositório remoto e alterar o README**
  Use `git clone URL_DO_REPO`, edite o `README.md`, faça um novo commit e envie a alteração com `git push`.

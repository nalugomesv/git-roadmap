<!-- [WIP] Work in Progress -->

# 🤝 Colaboração com GitHub

>Neste submódulo você encontrará materiais para aprender a colaborar usando o GitHub, plataforma amplamente usada para hospedagem de código e desenvolvimento colaborativo.

---

## Tópicos abordados

- Fluxo GitHub Flow: branch principal, branches de feature e Pull Requests (PRs)
- Como criar um Pull Request eficiente
- Revisão de código: boas práticas e ferramentas
- Resolução de conflitos via GitHub
- Uso de issues para gerenciamento de tarefas
- Integração com GitHub Actions para CI/CD básica

---

## 📖 Materiais Recomendados

* 📄 [GitHub Flow](https://guides.github.com/introduction/flow/)
* 📄 [GitHub - Documentação sobre solicitações de pull](https://docs.github.com/pt/pull-requests)
* 📄 [Como revisar Pull Requests](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/reviewing-changes-in-pull-requests)
* 📄 [Sobre issues](https://docs.github.com/pt/issues/tracking-your-work-with-issues/about-issues)
* 📄 [Quickstart for GitHub Issues](https://docs.github.com/pt/issues/tracking-your-work-with-issues/configuring-issues/quickstart)
* 🎥 [28. O que são issues? - Git e Github na Vida Real](https://www.youtube.com/watch?v=JKNaqYJXxbI)
* 🎥 [Resolvendo problemas com issues no GitHub?](https://www.youtube.com/watch?v=1_Ler6OE5d4)
---

## Fluxo básico: GitHub Flow

O GitHub Flow é um fluxo simples e popular para colaboração que consiste em:

1. Trabalhar na branch principal (`main`).
2. Criar branches específicas para cada feature ou correção.
3. Abrir Pull Requests para discutir, revisar e integrar código.
4. Realizar deploy contínuo após o merge.

---

## Exemplo prático: Criar um Pull Request

```bash
git checkout -b feature/novafuncionalidade
# faça suas alterações
git add .
git commit -m "feat: adiciona nova funcionalidade X"
git push origin feature/novafuncionalidade
```

Após isso, abra um Pull Request no GitHub na interface web.

---

## Boas práticas para Pull Requests

* Use títulos claros e objetivos.
* Descreva o que foi feito e o motivo.
* Relacione issues quando aplicável (ex: `Closes #123`).
* Peça revisão de colegas.
* Faça commits pequenos e atômicos.

---

## Exercício prático

1. Crie uma branch nova e faça uma alteração simples num arquivo README.md.
2. Faça commit com mensagem clara.
3. Suba a branch para o remoto.
4. Abra um Pull Request.
5. Faça um comentário em algum trecho do PR para praticar a revisão.
6. Peça para um colega revisar (se possível) e finalize o merge.

---

## Dicas para colaborar no GitHub

- Sempre atualize sua branch com a branch principal antes de abrir um PR
- Escreva descrições claras e objetivas nos PRs
- Use templates de PR para padronizar informações
- Faça revisões construtivas e respeitosas
- Utilize labels e milestones para organizar o trabalho

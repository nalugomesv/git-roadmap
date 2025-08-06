# 🤝 Como Contribuir

Obrigada por querer ajudar a melhorar este roadmap! 💜

## 🛠 Passo a Passo

1. Faça um fork do repositório → [Git Roadmap](https://github.com/AngelOttoni/git-roadmap)
2. Crie uma branch para suas alterações:

   ```bash
   git checkout -b minha-sugestao
   ```
3. Faça as alterações
4. Commit seguindo boas práticas ([Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/))
5. Envie para o seu fork:

   ```bash
   git push origin minha-sugestao
   ```
6. Abra um Pull Request 🚀

## 🏷️ Labels usadas nas Issues
- `iniciante` – tarefas para quem está começando
- `intermediário` – tarefas para quem já sabe o básico
- `avançado` – desafios mais complexos
- `docs` – melhorias na documentação
- `good first issue` – boas primeiras contribuições
- `projeto-final` – relacionado à entrega do projeto final

---

## 📦 Contribuições de Projetos Finais

Se você está entregando o projeto final do roadmap, siga os passos abaixo:

1. Faça um fork deste repositório → [Git Roadmap](https://github.com/AngelOttoni/git-roadmap).
2. Clone o fork na sua máquina:

    ```bash
    git clone https://github.com/seu-usuario/git-roadmap.git
    ```

3. Crie uma nova branch para suas modificações (substitua minha-entrega por um nome relevante):

    ```bash
    git checkout -b minha-entrega
    ```
4. Crie um arquivo `.md` com o nome da dupla na pasta `modules/05-project/submissions/`:    
    Exemplo:
    ```bash
    modules/05-project/submissions/nome1-e-nome2.md
    ```
5. Preencha o arquivo seguindo o modelo: [`modules/05-project/templates/TEMPLATE_ENTREGA.md`](./modules/05-project/templates/TEMPLATE_ENTREGA.md).
6. Faça o commit com uma mensagem semântica:

    ```bash
    git add modules/05-project/submissions/nome-da-dupla.md
    git commit -m "feat(submission): adiciona entrega final da dupla Nome1 & Nome2"
    ```

7. Envie (push) a branch para seu fork:

    ```bash
    git push origin minha-entrega
    ```
8. Abra um **Pull Request** para o repositório original, selecionando sua branch recém enviada.

9. Aguarde a revisão e sua entrada no Hall da Fama 🎉

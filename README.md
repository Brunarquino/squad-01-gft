# Trabalhando em equipe com git

O versionamento de código com Git é uma ferramenta muito importante na hora de desenvolver um projeto em equipe, é essencial pois diminui ricos de conflitos por perda de arquivos ou linhas de código e aumenta a produtividade de toda a equipe na hora de juntar as tarefas.

Os principais comandados na hora de trabalhar em equipe são:

[$ git clone](https://git-scm.com/docs/git-clone/pt_BR) → faz uma copia local exata do repositório remoto.

[$ git branch](https://git-scm.com/docs/git-branch/pt_BR) → criação de branches, listar branches, excluir branches e etc…

[$ git checkout](https://git-scm.com/docs/git-checkout/pt_BR) → Alterna entre branches ou restaura arquivos da working tree

[$ git switch](https://git-scm.com/docs/git-switch/pt_BR) →  Alterna entre branches 

[$ git pull](https://git-scm.com/docs/git-pull/pt_BR) → Atualiza e altera o repositório ou branch local

[$ git fetch](https://git-scm.com/docs/git-fetch/pt_BR) → Atualiza o repositório ou branch local

[$ git merge](https://git-scm.com/docs/git-merge/pt_BR) → Une dois ou mais históricos de desenvolvimento - ou seja une o histórico de branches - Único commit 

[$ git rebase](https://git-scm.com/docs/git-rebase/pt_BR) → Une e replica os commits em cima do topo de outra base

Branches

Existem 3 formas de criar e altenar para branch

Criando com git branch e alternando com git switch

```bash
git branch nova_branch
git switch 
```

Também criando com git branch e alternando com git checkout

```bash
git branch nova_branch
```

criando e alterando com git checkout

```bash
git checkout -b nova_branch
```

Um dos conceitos mas importantes na hora de trabalhar em equipe é os fluxos de trabalho, mas conhecidos como workflows. Que basicamente é alinhamento do fluxo de qual branch deve se trabalhar quando fazer commit e merges

### Referências

- [https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
- [https://www.varonis.com/pt-br/blog/git-branching](https://www.varonis.com/pt-br/blog/git-branching)
- [https://www.alura.com.br/curso-online-git-github-controle-de-versao](https://www.alura.com.br/curso-online-git-github-controle-de-versao)
- [https://medium.com/@patrickporto/4-branching-workflows-for-git-30d0aaee7bf](https://medium.com/@patrickporto/4-branching-workflows-for-git-30d0aaee7bf)
- [https://www.zup.com.br/blog/git-workflow](https://www.zup.com.br/blog/git-workflow)
- [https://www.atlassian.com/br/git/tutorials/comparing-workflows](https://www.atlassian.com/br/git/tutorials/comparing-workflows)
- [https://blog.cedrotech.com/git-o-minimo-que-voce-precisa-saber-para-trabalhar-em-equipe](https://blog.cedrotech.com/git-o-minimo-que-voce-precisa-saber-para-trabalhar-em-equipe)
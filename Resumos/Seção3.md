# O que é um Branch?

Um branch no Git é a forma como o código é separado em diferentes versões do projeto. Geralmente, cada nova feature de um projeto é desenvolvida em um branch separado. Após a finalização das alterações, os branches são unidos para formar o código-fonte final.

## Comandos Básicos de Branches:

- `VISUALIZAR BRANCHS (git branch)`: Exibe a lista de branches no projeto.
- `CRIAR BRANCH (git branch <nome>)`: Cria um novo branch com o nome especificado.
- `DELETAR BRANCH (-d ou --delete)`: Remove um branch. Use -d ou --delete.
- `MUDAR DE BRANCH (git checkout -b <nome>)`: Muda para um branch existente ou cria um novo enquanto muda.
- `UNIR BRANCHES (git merge <nome>)`: Une as alterações de um branch específico ao branch atual.

## Stash: Salvando Modificações Temporariamente

Podemos salvar as modificações atuais usando o stash para prosseguir com outra abordagem de solução sem perder o código. Após o comando `git stash`, o branch será resetado para a versão de acordo com a main.

- `VERIFICAR STASH (git stash list)`: Lista os stashes salvos.
- `RECUPERAR STASH (git stash apply <nome>)`: Recupera as modificações salvas em um stash específico.
- `REMOVER STASH (git stash clear)`: Remove todos os stashes ou `git stash drop <nome>` para uma stash específica.

## Tags: Marcando Pontos Importantes

Podemos criar tags nos branches usando o comando `git tag -a <nome> -m "msg"`. A tag é diferente do stash; ela serve como um checkpoint de um branch.

- `VERIFICAR TAG (git show / git show <nome>)`: Exibe informações sobre uma tag específica.
- `TROCAR TAG (git checkout <nome>)`: Muda para a versão marcada por uma tag.
- `ENVIAR TAG PARA O REPOSITÓRIO (git push origin <nome>)`: Envia uma tag específica para o repositório remoto. Para enviar todas as tags, use `git push origin --tags`.


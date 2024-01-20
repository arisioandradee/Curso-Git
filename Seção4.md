# ANOTAÇÕES SEÇÃO 3

Novos branches são criados a todo momento, e seu Git pode não estar mapeando todos eles. Com o comando `git fetch`, você é atualizado sobre todos os branches e tags que ainda não estão conhecidos por você.

- **Atualizar todas as branches:** `git fetch`
- **Receber atualizações:** `git pull`
- **Enviar alterações:** `git push`
- **Adicionar ou remover repositórios para rastrear:** `git remote`
  - Obs: Quando criamos um repositório remoto, adicionamos ele ao Git com `git remote add origin <link>`.

## TRABALHANDO COM SUBMÓDULOS

Submódulo é a maneira que temos de possuir dois ou mais projetos em um só repositório. Podemos adicionar uma dependência ao nosso projeto atual, mantendo suas estruturas separadas.

- **Adicionar submódulo:** `git submodule add <repo>`
- **Verificar submódulos:** `git submodule`
- **Atualizar submódulo:** Primeiramente, commitar as mudanças e enviar para o repositório do submódulo, utilizando `git push --recurse-submodules=on-demand`.

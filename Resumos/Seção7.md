# Melhorando commits do projeto

## A importância dos commits
Commits sem sentido atrapalham o projeto, por isso precisamos padronizar-los para que o projeto cresça de forma saudável também no versionamento, isso ajuda em: review do pull request, melhoria dos log em git log e manutenção do projeto.

## Técnica de private branch
Há uma solução para o problema anterior que se chama private branches. Onde criamos branches que não serão compartilhadas no repositório, então podemos colocar qualquer commit. O comando é 'git rebase <repo_atual> <repo_privado> -i'. Escolhemos os branches para excluir(squash) e renomear com (reword).

## Melhorando as mensagens dos commits
- Separar assunto do corpo da mensagem;
- Assunto com no máximo 50 caracteres;
- Assunto com letra inicial maiúscula;
- Corpo com no máximo 72 caracteres;
- Explicar o por que e como do commit, e não como o código foi escrito.
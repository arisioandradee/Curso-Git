## Controle de Versão
O controle de versão é uma técnica essencial para gerenciar o código-fonte de uma aplicação, permitindo criar e alternar entre diferentes versões do software em vários estágios de desenvolvimento. Essa prática facilita o trabalho colaborativo, permitindo que cada membro da equipe trabalhe em uma versão específica.
Existem ferramentas específicas para implementar o controle de versão, sendo duas delas notáveis: GIT e VSN.

## Git
O Git é o sistema de controle de versão mais amplamente utilizado no mundo hoje. Baseado em repositórios, o Git protege todos os objetos com criptografia, evitando alterações indevidas. Como projeto de código aberto, é uma ferramenta poderosa para o gerenciamento eficiente de versões.

## Repositório
O repositório é onde o código é armazenado. Geralmente, cada projeto possui seu próprio repositório, permitindo que cada desenvolvedor baixe o código e crie versões independentes em sua máquina.

### Comandos Git Básicos:

- `git status`: Verifica o estado do projeto.
- `git init`: Inicializa um repositório.

### O Que Aprendi na Seção:

Durante o curso, adquiri conhecimentos fundamentais sobre o Git, incluindo:

1. **Criar um Repositório:**
   - Estabelecer um novo repositório para o projeto.

2. **Verificar Mudanças do Projeto (`git status`):**
   - Monitorar alterações no projeto.

3. **Adicionar Arquivos Novos (`git add`):**
   - Adicionar novos arquivos ao projeto.

4. **Salvar Alterações (`git commit`):**
   - Registrar alterações no projeto com opções como `-a` (todos) e `-m` (mensagem).

5. **Enviar Código ao Repositório (`git push`):**
   - Enviar alterações para o repositório remoto.

6. **Receber Alterações (`git pull`):**
   - Atualizar o projeto com alterações do repositório remoto.

7. **Clonar Repositórios (`git clone`):**
   - Criar uma cópia local de um repositório remoto.

8. **Remover Arquivos (`git rm`):**
   - Remover arquivos do projeto.

9. **Acessar Histórico de Alterações (`git log`):**
   - Visualizar o histórico de alterações.

10. **Mover e Renomear Arquivos (`git mv`):**
    - Mover e renomear arquivos no projeto.

11. **Desfazer Alterações (`git checkout`):**
    - Desfazer modificações em arquivos específicos.

12. **Ignorar Arquivos no Projeto (`.gitignore`):**
    - Criar um arquivo de ignorados para especificar quais arquivos devem ser ignorados.

13. **Resetar uma Branch (`git reset`):**
    - Resetar uma branch, geralmente usado com a flag `--hard`.

    ```
    git reset --hard origin/master
    ```
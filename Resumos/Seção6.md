# Administração de Repositórios

## Limpando Arquivos Untracked
O comando `git clean` verifica e limpa arquivos que não estão sendo rastreados, ou seja, que não foram adicionados usando `git add`. Essa ação é útil para remover arquivos gerados automaticamente que podem prejudicar a visualização do que é realmente importante. Observação: é aconselhável adicionar os arquivos necessários antes de realizar a limpeza.

## Otimizando Repositório
O comando `git gc` é uma abreviação para garbage collector. Ele identifica arquivos que não são mais necessários e os exclui, otimizando assim o desempenho do repositório.

## Verificando Integridade dos Arquivos
O comando `git fsck` é uma abreviação de File System Check. Essa instrução verifica a integridade dos arquivos e sua conectividade, detectando possíveis corrupções nos arquivos.

## Reflog
O `git reflog` mapeia todos os seus passos no repositório, incluindo mudanças de branch. Ao contrário do `git log`, que armazena apenas os commits de um branch.

## Comprimindo o Repositório
Com o comando `git archive`, é possível transformar o repositório em um arquivo compactado. Por exemplo:
```bash
git archive --format zip --output master_files.zip master

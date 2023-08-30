## Desfazendo alterações no repositório local:

- ```rm -rf .git```: remover o versionamento (diretório .git e conteúdo) de uma pasta;
- ```git restore <nome-do-arquivo>```: descarta alterações feitas localmente e restaura o arquivo para a última versão;
- ```git commit  -- amend -m”nova-mensagem”```: corrige/altera a mensagem do último commit;
    - OUTRA OPÇÃO: ```git commit  -- amend```: (abre o editor para fazer a alteração);
- ```git reset - - soft <identificação-do-commit>```: desfaz último commit, retornando ao commit anterior e adicionando os arquivos na área de preparação
- ```git reset -- mixed <identificação-do-commit>```: desfaz último commit, retornando ao commit anterior e adicionando os arquivos na árvore de trabalho como “Untracked files”;
- ```git reset - - hard```: desfaz último commit, ignorando os arquivos do commit anterior e desfazendo-os;
- ```git reflog```: fornece informação mais detalhada dos commit’s;
- ```git reset <nome-do-arquivo>```:remove arquivos adicionados na área de preparação;
- ```git restore --staged <nome-do-arquivo>```: remove arquivos adicionados na área de preparação.

## Enviando e baixando alterações com o repositório remoto:

- ```git push```: envia as alterações do repositório local para o repositório remoto;
- ```git pull```: puxa as alterações do repositório remoto e mescla com as informações do repositório local.

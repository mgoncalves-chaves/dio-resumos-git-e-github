## Criando e clonando repositórios:

- ```git init```: para inicializar o repositório;
- ```git remote add origin URL```: conectar o repositório local com o repositório remoto;
- ```git clone URL nome-do-diretorio-local```: sobre o repositório clonado;
- ```git clone URL - - branch feature-1 - - single-branch```: para selecionar quando há mais de uma branch.

## Salvando alterações no repositório local:

- ```touch <nome-do-arquivo.md>```: cria o arquivo em branco dentro da pasta;
- ```git status```: mostra o status da árvore de trabalho e da área de preparação;
- ```git add README```: adicionar o arquivo na área de preparação;
- ```git commit -m “commit inicial”```: salvar alterações dentro de um commit;
- ```git log```: exibe o histórico do commit criado;
- ```echo nome-da-pasta/ > .gitignore```: insire o arquivo na pasta git ignore para que não seja mostrado no commit;
- ```.gitkeep```: utilizado para que um diretório vazio seja reconhecido;
- ```git add. ```: insere todos os arquivos na área de preparação.

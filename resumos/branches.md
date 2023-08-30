## Trabalhando com branches:

- Uma Branch é uma ramificação do seu projeto;
- Serve para testar funcionalidades sem afetar a branch principal;
- Quando se cria uma branch nova a partir de uma existente, essa nova branch passa a apontar para o mesmo commit que a originou;
- ```git checkout -b teste```: cria uma nova branch “teste” e troca a branch atual para esta nova;
- ```git checkout main```: retorna para a branch “main”;
- ```git branch -v```: lista a último commit de cada branch;
- ```git merge teste```: mescla a branch “teste” com a branch “main”;
- ```git branch```: lista as branches existentes no repositório;
- ```git branch -d teste```:  exclui a branch “teste”;
- ```git fetch```: baixa as alterações;
- ```git fetch origin main```: baixa as alterações do respositório sem mesclar;
- ```git diff main origin/main```: mostra a diferença entre as branches, nesse caso “main” e “origin”;
- ```git merge origin/main```: após ter baixado, esse comando mescla os arquivos da branch “origin” e “main”;
- ```git pull —> git fetch + git merge```;
- ```git clone <endereço-do-repositório> -- branch teste --single-branch```: para um repositório que tenha várias branches, se deseja clonar apenas uma delas;
- ```git stash```: arquiva uma modificação;
- ```git stash list```: lista as modificações arquivadas;
- ```git stash pop```: traz as alterações arquivadas para a branch e exclui a alteração mais recente da lista;
- ```git stash apply```: traz as alterações arquivadas para a branch e mantém a alteração mais recente na lista para uso posterior.

*Possível conflito ao trabalhar com branches:*

- Conflito de Merge: acontece quando há alterações concorrentes.

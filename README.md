# DIO Bootcamp Santander - Resumo Git e Github

Repositório criado para armazenar resumos sobre as aulas do curso de Versionamento de Código com Git e Github da [Digital Innovation One](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/f3cbaa66-efbd-4c25-842e-2069c188c066?back=/track/santander-bootcamp-2023-ciencia-de-dados-com-python&tab=undefined&moduleId=undefined)

# Versionamento de Código

- **Sistemas de Controle de Versão:** Controlam as versões de um arquivo ao longo do tempo;
- ****************************************Tipo de Sistemas de Versão (VCS):****************************************
    - ******************************************************VCS Centralizado (CVCS) — Ex: CVS, Subversion******************************************************
        - Apenas um servidor;
        - Áreas de trabalho conectadas ao mesmo servidor;
        - Desvantagem: Impossibilidade de salvar, alterar, caso fique fora do ar. Além disso, é mais suscetível a perda de arquivos se não houver backup adequado.
    - **********************************************************************VCS Distribuído (DVCS) — Ex: Git, Mercurial**********************************************************************
        - O banco de versão é duplicado localmente;
        - Permite edição e alteração mesmo que o servidor esteja fora do ar;
        - Cada clone é como um backup;
        - Clona o repositório completo, o que inclui o histórico de versões.

# GIT

- Gratuito e open source;
- **********************git clone —>********************** Clona um repositório Git existente para um novo diretório (pasta) local;
- ********************git commit —>******************** Grava alterações no repositório;
- ****************************git pull —>**************************** “puxa” as alterações do repositório remoto para o local (busca e mescla);
- ****************************git push —>**************************** “empurra” as alterações do respositório local para o remoto.

# GitHub

- Plataforma de hospedagem de código para controle de versão com Git, e colaboração;
    - **Criando e clonando repositórios:**
    - **git init:** para inicializar o repositório;
    - **git remote add origin URL**: Conectar o repositório local com o repositório remoto
    - **git clone URL nome-do-diretorio-local:** Sobre o repositório clonado
    - **git clone URL - - branch feature-1 - - single-branch:** Para selecionar quando há mais de uma branch;
    - ************************git status:************************ mostra o status da árvore de trabalho e da área de preparação
    - ********************************git add README:******************************** adicionar o arquivo na área de preparação
    - ********************************git commit -m “commit inicial”:******************************** salvar alterações dentro de um commit
    - ******************git log:****************** exibe o histórico do commit criado
    - ********************************echo nome-da-pasta/ > .gitignore:******************************** insire o arquivo na pasta git ignore para que não seja mostrado no commit
    - ********************.gitkeep:******************** utilizado para que um diretório vazio seja reconhecido
    - **********************git add. :********************** insere todos os arquivos na área de preparação

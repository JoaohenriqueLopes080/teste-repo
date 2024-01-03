# Estudando e aprendendo GIT e GITHUB - STUDYING AND LEARNING GIT AND GITHUB

Aprendendo o basico de git and github - learning the basic of git and github.
<br>
Comandos CMD
<br>
Repositorio Remoto - GITHUB  
<br>
REPOSITORIO LOCAL - PC(VISUAL STUDIO CODE -ETC..)<br>



Git INIT - inicialize a empty repository
<br>

Git ADD . 
<br>
PUT all the items into . and make the items tracked
<br>


git reset . = Put everything untracked and reset
<br>

gitreset [file name} - reset only the file we put the name on
<br>

--
GIT STATUS - Show the status of the files and what can be committed<br>

--------------
git log - show the author and time of the last commit<br>

-----
git commit - m "Message of the file" - send the file to the github and the message we put into it<br>

--------
git commit -a -m "Message" - send all the files and the message we put into it<br>

----------

aprendemos a fazer COMMITS - STATUS - LOGS - ADDS E RESETS-AGORA IREMOS CONECTAR AO REPOSITORIO DO
NOSSO GIT HUB<br>

Git Remote - mostra qual repositorio estamos conectados no momento - se não tiver nenhum conectado, não apareça nada.<br>

Git remote add ORIGIN "LINK" - adiciona o repositorio com o url que adicionarmos<br>

git remote -V - mostra o url do nosso repositorio<br>

git remote show origin - apareça informações extras alem do link, como a branch do momento
<br>

VAI LINKAR ou dar um upload do nosso repositório local ao repositório remoto<br>

Precisa de dois argumentos
Git Push - o nome do repositorio remoto (Exemplo "ORIGIN")<br>

A branch que vai ser adicionada ( EXEMPLO "MASTER")<br>

ASSIM o codigo fica<br>

Git Push Origin Master<br>

----------------<br>
Git push Origin master -u - set the origin repo to the upstream remote<br>
------------<br>
assim enviamos o nosso codigo ao github-<br>
Git Fetch and Merge<br>
Nesse descobrimos como sincronizar o nosso repositorio local com o remoto<br>
Git Fetch - pega as ultimas atualizações feitas no repositorio Remoto - GITHUB<br>


Existem 2 metodos<br>
o Mais dificil<br>
Se usarmos o git fetch depois de termos feito uma atualização no repositorio remoto(Github) ele ira sincronizar com o nosso local, mas as diferenças não apareceram no nosso codigo, pois precisamos dar um merge para que os dois se JUNTEM.<br>

Git Merge - pega duas branchs ou commits diferentes e junta em um so arquivo.<br>

git merge "EXEMPLO1/EXEMPLO2" nomes das branchs<br>

git merge "origin/master"<br>
--------------<br>
agora o 2 metodo - o mais facil<br>
Git pull origin master - mas se usarmos o -u no git push, não precisamos especifar o origin master e simplesmente utilizar<br>
GIT PULL<br>
----------------------------
Git Branch - da uma lista de todas as branchs do projeto.renomear a branch master para main<br>

git branch -M main                     assim renomeamos a master para MAIN<br>

AGORA iremos criar uma Branch<br>

Git branch INCRÍVEL<br>

basta apenas citar qualquer nome depois de branch e assim teremos criado uma nova branch.<br>

agora deletar uma BRANCH<br>

Git Branch -d "NOME" <br>
usando -d ira deletar de forma mais segura<br>
usando -D ira deletar fazendo o que for necessario, então use mais -d<br>

---<br>
TROCAR DE BRANCH<br>
--------<br>
git checkout "nome"<br>
-----<br>
agora se eu quiser CRIAR E TROCAR para uma nova branch ao mesmo tempo utilizamos<br>
 git checkout -b "nome"<br>
-------------<br>
Retornar a branch anterior "caso esqueça o nome da branch"<br>
Git checkout -

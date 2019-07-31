# AulaGit
Aula Git - DigitalHouse

Comandos iniciais de Git (https://gitforwindows.org  -  Git Bash)

Outros repositorios: gitLab / bitbucket / ...

Definições:

Github  > repositório Web
Git     > software de versionamento
GitBash > terminal onde digitamos/utilizamos os comandos

Comandos básicos:

git init -> sempre que iniciar um novo projeto na pasta
pwd -> mostra a pasta atual 
cd .. -> volta um diretório 
cd <nome diretorio> -> entra no diretório
ls -> lista arquivos
ls -la -> lista arquivos com mais detalhes
mkdir <nome diretorio> -> cria pasta / diretorio
touch <nome do arquivo.txt> -> cria arquivo
rm <nome do arquivo / diretorio> -> remove arquivo / pasta
clear -> limpa tela de comandos
git remote add origin <url do github> -> faz link entre diretorio e github
git remote get-url origin -> checa o diretorio do github que está linkado o diretorio da maquina
git status -> mostra os arquivos que estão no diretório e status
git add <nome do arquivo> -> insere arquivo para enviar para o repositorio
git commit -m "mensagem / etiqueta" -> confirma o arquivo que será enviado para o repositorio
git push -u origin master - envia para o repositorio (se local e repositorio estiver atualizado)
git pull origin master - envia para o repositorio (se local e repositorio estiver desatualizado fazer este passo antes do push)
** git pull --rebase origin master -> se der problema no PUSH/PULL use este comando
git status -> verifica o que está pendente na pasta  
git config --global user.name "Rodrigo Cordeiro"
git config --global user.email "rodrigo_cordeiro@hotmail.com"
git checkout -b <nome da branch> -> cria a nova branch (sem o -b ele só sai da branch)

>> Mão na Massa <<
Para clonar branch Develop
copia a URL da branch a ser copiada
vai no fitbash e cd.. para sair da branch
cd nome do documemto
abre no explorer o arquivo copiado e modifica/atualiza
git status para ver o que está pendente
git add <nome do arquivo> -> insere arquivo para enviar para o repositorio
git commit -m "mensagem / etiqueta" -> confirma o arquivo que será enviado para o repositorio
git pull -> atualiza o que a equipe tbem enviou
git push -u origin master - envia para o repositorio (se local e repositorio estiver atualizado
  


  











  
  





  
  




#Instruções Utilizadas neste exemplo

1. Primeiro Commit
  1. Criar repositório local - git init
  2. Adicionar arquivos ao staging - git add [nome do arquivo]
  3. Commitar arquivos - git commit -m "Meu primeiro commit"
  4. Visualizar log de commits - git log

2. Criando Branch
  1. Criar branch funcionalidade1 - git branch funcionalidade1 -b
  2. Adicionar arquivo funcionalidade1 ao staging - git add [nome do arquivo]
  3. Commitar arquivo funcionalidade1 - git commit -m "Adicionado funcionalidade1"
  4. Mudar para o branch master - git checkout master
  5. Fazer merge do branch funcionalidade1 no master - git merge funcionalidade1
  
3. Primeiro Push  
  1. Adicionar url do repositório remoto - git remote add origin git@github.com:MuriloDagostini/git-code-education.git
  2. Fazer push do branch master no repositório remoto - git push origin master

4. Adicionar Branch Remoto
  1. Mudar para branch funcionalidade1 - git checkout funcionalidade1
  2. Fazer push do branch funcionalidade1 - git push origin funcionalidade1

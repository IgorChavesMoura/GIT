#GIT

##Comando de help:
git

##Clonar um repositorio do github para o pc:
git clone URL

##Acessar uma versao de um arquivo por tag:
git diff tag

##Inicializar um repositorio:
git init


##Comando para mostrar o status do repositorio:
git status

##Comando para listar os arquivos no repositorio que sao controlados pelo git:
git ls-files

##Comando para fazer o git monitorar um arquivo no repositorio:
git add (arquivo)

##Comando para fazer o commit:
git commit -m "mensagem"

##Comando para mostrar o histórico de commits:
git log

##Comando para mostrar as mudanças feitas em cada commit:
git whatchanged

se passar a flag -p ele mostra as linhas que foram alteradas

##Comando para criar repositorio remoto:
git remote add origin (URL do repositorio github)

##Comando para adicionar arquivos no repositorio remoto:
git push -u (nome do repositorio remoto) (nome da branch)

nome do repositorio geralmente é origin
nome da branch geralmente é master

##Comando para checar quais branchs existem no repositorio:
git branch

##Comando para criar uma nova branch:
git branch (nome da branch)

##Comando para mudar a branch:
git checkout (nome da branch)

##Comando para atualizar as branchs do repositorio local com as do remoto:
git pull

##Comando para criar uma branch local e associar a uma branch remota:
git branch -r (nome da branch local) (nome do repositorio remoto/nome da branch remota)

##Comando para criar e trocar para branch:
git checkout -b (nome da branch)

##Comando para trazer os commits de uma outra branch:
git merge (nome da branch com os commits)

##Comando para atualizar uma branch com base em outra:
git rebase (nome da branch de base) (nome da branch a ser atualizada)

##Comando para voltar um arquivo para o ultimo commit:
git checkout (nome do arquivo)

##Comando para voltar um arquivo para o ultimo estado antes de ser commitado:
git reset HEAD (nome do arquivo)

para escolher o commit no lugar do HEAD poe o identificador(hash) do commit

##Comando para desfazer um commit:
git revert (identificador do commit)

##Comando para guardar alterações que nao foram commitadas:
git stash

##Comando para ver o que tem dentro do stash:
git stash list

##Comando para aplicar as alterações no stash:
git stash apply

##Comando para zera o stash:
git stash drop

##Comando para trazer alteracoes de um repositorio remoto:
git fetch (nome do repositorio)












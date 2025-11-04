# lista de comandos

## como iniciar o repositório git

`git init`

## verificar e modificar confirgurações do git

- verificar
git config --global --list

- modificar 
git config --global user.name "meu nome"

git config --global user.email "meu@email.com"

## rotina básica do git (esses sempre estarão juntos)

git add <arquivo>

git commit -m (mensagem relevante)

## rotina não tão básica do git com github
1. Situação: Atualizei meus arquivos no repositório local

   salvei

   git add arquivo.md

   git commit -m "mensagem relevante"

   git push

2. Situação:
a) Atualizei meus arquivos no git hub e quero sincronizar com o repositório local
b) Meu colaborador atualizou o arquivo e eu quero sincronizar com o meu repositório local

 git pull

3. Situação: Mundo ideal

   git pull

   editar os arquivos

   git status

   git add arquivo.md

   git commit -m "mensagem relevanta"

   git push
# outros comandos

ls (mostra o arquivo)
ls -la (mostra arquivos escondidos)

git status -> changes to be commited (file a, file c); changes not staged (file b); untracked files (filex)

`git status`conferir em qual área meu arquivo está 
`git add <arquivo>`adicionar na staging area
<<<<<<< HEAD
`git commit -m`enviar para o repositorio local

`git log`utilizado para ver o histórico de versões do arquivo

# comando para destravar terminal 
`ctrl z ou x ou c`

# comando git diff e git show
`git diff`mostra as alterações feitas no repositório alterações velhas e novas
`git show`mostra mais detalhadamente as alterações mais detalhadamente (no caso mostra o ultimo commit salvo)

`git remote add <name> <ssh>`

# push and pull
`git push`: mandar informações do computador para o git hub
`git pull`: puxar informações do git hub para o computador
=======

`git commit -m`enviar para o repositorio local
>>>>>>> 43b71a489bd1fbacad9d5d19e0cff3decb6ff561

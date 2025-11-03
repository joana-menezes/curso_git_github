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

# outros comandos

ls (mostra o arquivo)
ls -la (mostra arquivos escondidos)

git status -> changes to be commited (file a, file c); changes not staged (file b); untracked files (filex)

`git status`conferir em qual área meu arquivo está 
`git add <arquivo>`adicionar na staging area
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

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
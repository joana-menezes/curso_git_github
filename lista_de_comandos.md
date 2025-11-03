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

`git commit -m`enviar para o repositorio local

Git: é uma ferramenta para manter versões salvas de um mesmo projeto, de forma a otimizar o tempo. Apresenta linha do tempo com todas as modificações.
GitHub: Funciona como backup da linha do tempo. 
# Dicionário de conceitos 

## Subtítulo

NÃO ESQUECER DE SEMPRE ALTERAR DE POWERSHELL PARA WSL (caso a alteração automática não funcione)

### Sub-subtítulo

- tópico 1

- tópico 2

- tópico 3

**negrito**

*italico* 

# alguns comandos usados no vs e git
pwd - encontrar pasta
ls - encontrar arquivo
cd - entrar na pasta
cd .. - sair da pasta

commit - tornar permanente um conjunto de alterações
git add file - adicionar file

nao esquecer de salvar com .md os files

main / master

## rotina básica de criação de um ponto na linha do tempo
git add (add o file)
git commit -m (aicionar mensagem) - (a mensagem precisa ser relevante)
pq precisa ser relevante? avisa sobre mudança; como o problema foi resolvido; efeitos causados pela alteração; limitações das atualizações feitas. Mais detalhes na mensagem > informação
git config --global --list (verificar informação)

## novos conceitos 
- Área de desenvolvimento: Adiciona e modifica os arquivos. Onde está a pasta do projeto, que inicia o repositório (git init)

- Staging area: Organiza o histórico (stig add). Administrar o que pertence junto e o que está separado.

- Repositório local: Local de envio dos commit (versões do arquivo). Encontrado como forma de arquivo na pasta .git a qual deve ser protegido e salvo com cuidado. 

## pq usamos git status?

- Git Status é usado para verificar quais arquivos estão salvos no repositório e seu status.
- Usado para verificar se os arquivos se encontram todos compilados no repositório. 

`Changes to be commited`mudanças a serem submetivas -> o arquivo encontra-se na area staging (o que significa que ja teve o git add)
`Untracked files`arquivos novos sem nenhuma versão salva (arquivos nao monitorados)
`Changes not staged for commit`arquivo com mudanças que não foram enviadas para o staging.


## para sair do git log é so apertar a letra Q de quit
### informações adicionais para o git log
`--help`
`-n <nº> (o n é numero)`
`--abbrev-commit`
### viajando na linha do tempo
`git diff <ID versão antiga> <ID versão nova>` -> comparação de pares
`git show`mostra o ultimo commit salvo no repositório

# local to remote
## timeline backup
copiar do git hub no repositório

# README.txt
- Descrição do projeto ou ferramenta utilizada 

# .gitignore
- Lista de arquivos que **NÃO** serão adicionados ao repositório git
1. Data files
2. Backup files
3. Intermediate files
- Os arquivos podem ser ignorados quando colocados dentro do arquivo .gitignore 

## Passo a passo colaboração (clone)
- Fazer pull para visualizar atualizações do colaborador
- Fazer push a cada alteração que eu fiz no doc do meu colaborador
- **Não** esquecer do add e commit -m (quando fizer as alterações) git push após conclusão



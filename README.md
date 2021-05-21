# Curso de Git e Github

Os trê estágios do Git:
- **Working Tree**
- **Stage**
- **Head**


## Comandos Git


### Comando úteis
`git init`

`ls -a`

`ls -al .git`

`cd .git`

`ls`

`cat config`

`git config --list`

`git help`

`git help log`


### init
Inicializa repositório local
`git init`


### config
`git config --list`
`git --local --list`

`cat ~/.gitconfig` ou `cat ~/.config/git/config`

`git config --global user.name "seu nome"`

`git config --global user.email "seu email"`

`git config --global core.editor "code -w"`


### add
`git add "nome do arquivo"`
`git add .`  adiciona vários arquivos
`git add *.md`

### commit
Cria ponto na hitória do repositório
`git commit -m "sua mensagem com detalhes do commit"`

Corrige mensagem do commit
`git commit -m "mensagem" --amend`


# rm 
`git rm --cached "nome do arquivo"`
`git rm "nome do arquivo"` // deleta arquivo do sistema


# restore
`restore --staged "nome do arquivo"`

# mv
`git mv "arquivo" "novo nome do arquivo"`
`git mv "arquivo" "diretório/novo nome do arquivo"`


### log
`git log`
`git log --oneline`
`git log -n 5`
`git log --since=2020-08-21`
`git log --until=2020-08-21`
`git log --author=Marcelo`
`git log --grep="home"`

### shortlog

Resumo de logs
`git shortlog`

### reflog
`git reflog`

### checkout
`git checkout`

### reset
`git reset --hard origin/main`

### branch
Visualizar lista de branch
`git branch`

Criar nova branche
`git branch nome_da_nova_branch`

Alternar branch
`git checkout nome_da_branch`

Cria nova branch e já alterna para ela
`git checkout -b "nome_nova_branch"`

Deletar branch
`git branch -d nome_da_branch `


### fetch
Busca novas branches no repositório remoto
`git fetch -a`


### merge
`git merge nome_da_branch`


### stash
Cria nova stash
`git stash`

Lista stash
`git stash list`

Alterna para stash
`git stash applay 0`

Mostra conteúdo da stash
`git stash show -p 2`


### tags
Criar uma nova tag (marcar uma versão)
`git tag -a v1.0 -m "Mensagem..."`

Listar tags
`git tag`

Mostra detalhes da tag
`git show v1.0`

Alternar entre tags
`git checkout v1.0`

Enviar uma tag para Github
`git push origin v1.0`

Enviar todas as tags para o Github
`git push origin --tags`


### pull
`git pull`

### git gc
Usar com atenção
`git gc`


### diff
`git diff`
`git diff --staged` // staged area

## pull
Busca alterações remotas
``git pull``

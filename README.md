# Curso de Git e Github

## Comandos Git

### log
``git log``

### checkout
``git checkout``

### reset
``git reset --hard origin/main``

### branch
Visualizar lista de branch
``git branch``


Criar nova branche
``git branch nome_da_nova_branch``


Alternar branch
``git checkout nome_da_branch``


Cria nova branch e já alterna para ela
``git checkout -b "nome_nova_branch"``


Deletar branch
``git branch -d nome_da_branch ``



### merge
``git merge nome_da_branch``


### stash
Cria nova stash
``git stash``


Lista stash
``git stash list``


Alterna para stash
``git stash applay 0``


Mostra conteúdo da stash
``git stash show -p 2``


### tags
Criar uma nova tag (marcar uma versão)
``git tag -a v1.0 -m "Mensagem..."``


Listar tags
``git tag``


Mostra detalhes da tag
``git show v1.0``


Alternar entre tags
``git checkout v1.0``


Enviar uma tag para Github
``git push origin v1.0``


Enviar todas as tags para o Github
``git push origin --tags``


## fetch
```git fetch -a``


## pull
``git pull``
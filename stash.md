## Git stash


```git stash save "nomeDoStash"```  salva o que esta no staging area(arquivos verdes, depois de git add) no stash

```git stash list```  lista os stash

```git stash apply stash@{0}```  traz de volta pra staging area o stash(stash@{0} = é a referencia do stash obtido no stash list)

```git stash drop stash@{0}```  apaga o stash
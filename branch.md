## Git branch

```git branch```  mostra todos os branch

```git branch feature1```  cria um novo branch chamado feature1

```git branch -d feature1```  deleta o branch feature1


### HEAD

```cat .git/HEAD``` traz a referencia do commit na qual o HEAD está, ou seja é o ponto em que se esta trabalhando


## Git checkout

``` git checkout -b feature2``` cria a branch feature2 e aponta o HEAD para essa branch

## Pegar o conteudo da master e mesclar em otra brach(feature1)

```git checkout feature1```
```git merge master```

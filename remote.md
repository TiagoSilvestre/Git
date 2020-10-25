## Git remote

*O comando git remote permite criar, ver e excluir conexões com outros repositórios.*


```git remote -v ``` exite o remoto, no caso mais comun mostra o remote origin com seu fetch e push

```git remote add nomeDoRemoto endereçoParaRepositorioRemoto ``` linka o repositorio local, que já foi iniciado com o git init, ao endereço do repositorio 
remoto(endereçoParaRepositorioRemoto), criando o nome desse remoto com o nome(nomeDoRemoto), normalmente usado origin

```git remote add origin https://github.com/TiagoSilvestre/Git.git``` esta adicionado no repositorio local a origem https://github.com/TiagoSilvestre/Git.git, 
no caso esta definindo a origin remota como essa url ai

```git remote remove origin``` irá remover a ligaçao com o remoto origin


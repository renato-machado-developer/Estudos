# Git pelo Terminal

## Enviando suas alterações para o GitHub(Commit)
* Navegue até a pasta do repositório que será criada a *branch*.

`cd Documentos/GitHub/Teste`

* Adicionando as modificações na área de preparação.

`git add .`

* Salvando as alterações no repositório local.

`git commit -m conteúdo-teste`

* Enviando as alterações para o GitHub.

`git push origin conteúdo-teste`

* Insira sua senha.

---
## Criando uma ramificação do repositório pelo terminal (Branch)
* Nesse exemplo vou criar uma branch do repósitorio Teste que está na pasta GitHub dentro de Documentos, o nome dessa branch será, conteúdo-teste.

---
* Navegue até a pasta do repositório que será criada a *branch*.

`cd Documentos/GitHub/Teste`

* Crie a branch:

`git branch conteúdo-teste`

* Troque para a branch que você acabou de criar:

`git checkout conteúdo-teste`

* Envie sua branch para o GitHub:

`git push origin conteúdo-teste`

* Abra seu Visual Code Studio:

`code .`

* No canto inferior esquerdo do Visual Studio você vera a branch que acabou de criar.

---

## Fundindo a ramificação no repositório principal (Merge).

* Confira se você está na branch que deseja mesclar, estara marcada com um '*'
 git branch

 * caso não esteja na branch correta, mude com o comando
 git checkout branch








Se a pasta *Teste* estiver dentro de *GitHub* dentro de *Documentos*, vamos colocar`cd`seguido do nome da pasta`/`nome da pasta`/`nome da pasta em ordem crescente, até chegar dentro da pasta do repositório.
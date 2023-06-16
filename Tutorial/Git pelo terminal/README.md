# Git pelo Terminal

## Criando um repositorio.
* Navegue até a pasta onde será criado o repositório.

`cd Documentos`

* Inicie o novo repositório.
`git init`

* Crie a pasta através do site GitHub.

* Clique em `Repositorios` depois em`Novo`.

* Coloque o nome do Repositorio, selecione publico ou privado, selecione para adicionar o README.md, escolha a licensa MIT e clique em criar repositorio.

* Clique em 'Código' selecione HTTPS e Copie o URL do repositório.

* Adicione a URL do repositório remoto no repositório local.

`git remote add origin URL do Repositorio`

* Adicione as modificações na área de preparação.

`git add .`

* Salve as alterações no repositório local.

`git commit -m conteúdo-teste`

* Envie as alterações para o GitHub.

`git push -u origin main`

*Digite seu usuário e senha do GitHub.

*Após autênticado, o repositório será criado no GitHub e seu repositório local será sincronizado.

## Enviando suas alterações para o GitHub(Commit).
* Navegue até a pasta do repositório que será criada a *branch*.

`cd Documentos/GitHub/Teste`

* Adicione as modificações na área de preparação.

`git add .`

* Salve as alterações no repositório local.

`git commit -m conteúdo-teste`

* Envie as alterações para o GitHub.

`git push origin conteúdo-teste`

* Insira sua senha.

---
## Criando uma ramificação do repositório pelo terminal (Branch).
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

* Confira se você está na branch que deseja mesclar, estará marcada com um`*`.
`git branch`

 * Caso não esteja na branch correta, mude com:
`git checkout branch`

 * Mescle a ramificação na principal.
`git merge conteúdo-teste`

* Adicione as modificações na área de preparação.
`git add ` 

* Confirme as alterações de mesclagem junto com uma mensagem apropriada.
`git commit -m mesclando a ramificação conteúdo na principal`

* Envie as alterações mesclandas para o GitHub.
`git push origin main`

Se a pasta *Teste* estiver dentro de *GitHub* dentro de *Documentos*, vamos colocar`cd`seguido do nome da pasta`/`nome da pasta`/`nome da pasta em ordem crescente, até chegar dentro da pasta do repositório.
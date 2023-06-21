# Git pelo Terminal
* Neste exemplo vou criar um repósitorio **Teste** dentro da pasta **GitHub** dentro de **Documentos**, e uma **branch** chamado **conteúdo-teste**.

## Conectando seu Git com GitHub.
* Abra o Terminal **CRTL+T**

* Gere uma chave SSH com **`ssh-keygen`** pressione **Enter** para aceitar as opções padrão:

* Copie a chave pública SSH, para exibir-la **`cat ~/.ssh/id_rsa.pub`**

* Adicione sua chave pública SSH no GitHub em **Configurações**, **Chaves SSH**, **GPG**, **Nova chave SSH"**. Dê um título e cole a chave em **Chave** e **Salve a chave**
  
## Criando um Repositório.
* Crie a pasta através do site GitHub.

* Clique em **Repositórios**, **Novo**.

* Coloque **Nome do Repositório**, **Descrição**, **Público** ou **Privado**, adicione o **README.md**, escolha **Licença MIT**, **Criar**.

* Crie uma pasta GitHub dentro de Documentos.

* Clique em **Código**, **HTTPS**, Copie o URL.

* Adicione a URL do repositório remoto no repositório local:

 `git remote add origin URL do Repositório`

* Adicione as modificações na área de preparação.

 `git add .`

* Salve as alterações no repositório local.

 `git commit -m conteúdo-teste`

* Envie as alterações para o GitHub.

 `git push -u origin main`

*Digite seu usuário e senha do GitHub.

## Enviando suas alterações para o GitHub (Commit).
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
* Neste exemplo vou criar uma branch do repósitorio Teste que está na pasta GitHub dentro de Documentos, o nome dessa branch será, conteúdo-teste.

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

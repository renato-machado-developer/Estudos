# Git pelo Terminal
* Criarei um repósitorio **Teste** dentro da pasta **GitHub** dentro de **Documentos**, e uma **branch** chamado **conteúdo-teste**.

---
## Conectando seu Git com GitHub.
* Abra o Terminal **CRTL+ALT+T**

* Gere uma chave pública SSH **`ssh-keygen`** pressione **Enter** para aceitar as opções padrão.

* Coloque uma senha.

* Para exibir a chave **`cat ~/.ssh/id_rsa.pub`** copie a chave.

* Adicione a chave no GitHub: **Configurações**, **Chaves SSH e GPG**, **Nova chave SSH"**. Dê um título, cole em **Chave**, **Adicione Chave SSH**

---
## Criando um Repositório (Clone).
* Crie a pasta através do site GitHub.

* Clique em **Repositórios**, **Novo**.

* Coloque **Nome do Repositório**, **Descrição**, **Público** ou **Privado**, adicione o **README.md**, escolha **Licença MIT**, **Criar**.

* Crie uma pasta GitHub dentro de Documentos.

* No GitHub clique em **Código**, **HTTPS**, **Copie o URL**.

* Abra o Terminal **CRTL+ALT+T**

* Navegue até a pasta GitHub.

`cd Documentos/GitHub`

`git clone https://github.com/nome-usuário/nome-repositório`

* Inicie o Repositório.

 `git init`

* Adicione a URL do repositório remoto no repositório local:

 `git remote add origin url-do-repositório`

* Abra o Visual Studio Code.
  
`code .`

* **Arquivo**, **Abrir Pasta**, Documentos, GitHub, Teste, **Abrir**.

* Trabalhe no seu código.

---
## Enviando suas alterações para o GitHub (Commit).
* Adicione as modificações na área de preparação.

`git add .`

* Salve as alterações no repositório local.

`git commit -m conteúdo-teste`

* Envie as alterações para o GitHub.

`git push origin conteúdo-teste`

*Digite seu usuário e senha do GitHub.

---
## Criando uma ramificação do repositório pelo terminal (Branch).
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

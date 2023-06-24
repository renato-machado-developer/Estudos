# Git pelo Terminal
* Criarei um repósitorio **Teste** dentro da pasta **GitHub** dentro de **Documentos** e uma **branch** chamado **conteudo-teste**.

---
## Conectando seu Git com GitHub
* Abra o Terminal **CRTL+ALT+T**.

* Gere uma chave pública SSH **`ssh-keygen`** pressione **Enter** para aceitar as opções padrão.

* Coloque uma senha.

* Para exibir a chave **`cat ~/.ssh/id_rsa.pub`** copie a chave.

* Adicione a chave no GitHub: **Configurações**, **Chaves SSH e GPG**, **Nova chave SSH"**. Dê um título, cole em **Chave**, **Adicione SSH**.

* Configure seu E-mail.
  
`git config --global user.email coloque-email`

* Configure seu nome de usuário.
  
`git config --global user.name coloque-usuário`

---
## Criando um Repositório (Clone)
* Crie a pasta através do site GitHub.

* Clique em **Repositórios**, **Novo**.

* Coloque **Nome do Repositório**, **Descrição**, **Público** ou **Privado**, adicione o **README.md**, escolha **Licença MIT**, **Criar**.

* Crie uma pasta GitHub dentro de Documentos.

* No GitHub clique em **Código**, **HTTPS**, **Copie o URL**.

* Abra o Terminal **CRTL+ALT+T**.

* Navegue até a pasta **GitHub**.

`cd Documentos/GitHub`

* Clone.

`git clone https://github.com/nome-usuário/nome-repositório`

* Entre na Pasta.

`cd Documentos/GitHub/Teste`

* Inicie o Repositório.

 `git init`

* Atualize a URL remota.

`git remote set-url origin git@github.com:nome-usuário/nome-repositório.git`

* Abra o Visual Studio Code.
  
`code .`

* **Arquivo**, **Abrir Pasta**, Documentos, GitHub, Teste, **Abrir**.

* Trabalhe no código.

---
## Enviando suas alterações para o GitHub (Commit)
* Adicione as modificações na área de preparação.

`git add .`

* Salve as alterações no repositório local.

`git commit -m conteudo-teste`

* Envie as alterações para o GitHub.

`git push origin main`

* Digite seu usuário e senha (SSH) do GitHub.

---
## Criando uma ramificação do repositório pelo terminal (Branch)
* Navegue até a pasta do repositório que será criada a **branch**.

`cd Documentos/GitHub/Teste`

* Crie a branch.

`git branch conteudo-teste`

* Troque para a branch que você acabou de criar.

`git checkout conteudo-teste`

* Envie sua branch para o GitHub.

`git push origin conteudo-teste`

* Abra seu Visual Code Studio.

`code .`

* No canto inferior esquerdo do Visual Studio você vera a branch que acabou de criar.

---
## Fundindo a ramificação no repositório principal (Merge)
* Confira se você está na branch que deseja mesclar, estará marcada com um`*`
  
`git branch`

* Caso não esteja na branch correta, mude com:
   
`git checkout branch`

* Ramificação que será mesclada.
   
`git merge conteudo-teste`

* Adicione as modificações na área de preparação.
  
`git add .`

* Confirme as alterações de mesclagem.

`git commit -m "Mesclando a ramificação conteudo-teste para main"`

* Envie as alterações mesclandas para o GitHub.
  
`git push origin main`

---
## Bibliografia
---
[ChatGPT](https://chat.openai.com/auth/login?next=/chat)

---

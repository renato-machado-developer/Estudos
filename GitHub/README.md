# Git e GitHub
* Resumo simplista de versionamento com Git e GitHub.

---
## Git
* Criado por Linus Torvalds em 2005.

* Sistema de Controle de Versão Distribuído (VCS).

* Registra as alterações no código ao longo do tempo em um repositório local.

* Criar versões da aplicação, como pontos de restauração.

* Permite que compartilhe as alterações com outras pessoas no repositório remoto.

* Permite trabalhar offline.

---
## Sistema Distribuído
* Cada desenvolvedor tem sua própria cópia de todo o repositório.

---      
## Repositório Local
* Diretório no computador que armazena tudo sobre o projeto.

---
## Repositório Remoto
* Uma cópia do projeto armazenada em servidor compartilhado.

---
## GitHub
* Fundado em 2008 por Tom Preston-Werner, Chris Wanstrath e PJ Hyett.

* Adquirida em 2018 pela Microsoft por US$ 7,5 bilhões.

* Redes sociais para programadores.

* Servidor remoto e Compartilhado baseado em Git.

* Mantém um histórico completo de todas as alterações feitas no projeto.

* Permitindo voltar a versões anteriores do código, caso seja necessário.

* Permite várias pessoas trabalhando no mesmo projeto ao mesmo tempo.

---
## Principais Comandos
* git clone: Cria uma Cópia local de um reposotório remoto.

* git commit: Salva alterações do repositório local.

* git push: Carrega alterações do repositório local para o repositório remoto.

* git pull: Baixa alterações do repositório remoto para o repositório local.

---
## Ramificação (Branch)
* Cria uma versão separada do código principal.

* Permite fazer alterações sem afetar a código principal.

* Cada ramificação e trabalhada independentemente.

* Usada para testar isoladamente novos recursos e alterações.

* Permite que cada desenvolvedor trabalhe em aspectos diferentes do projeto.

---
## Mesclar (Merge)
* Incorporar alterações da ramificação ao código principal ou outra ramificação.

* Compara o código antigo com as novas alterações.

* Outros desenvolvedores revisam as alterações antes de unir ao codigo principal.

---
## Bifurcação (Fork)
* Cria uma cópia do repositorio de outro usuario.

* Permite testar, modificar recursos e corrigir bugs sem afetar o repositório original.

* Permite solicitar “Pull”, para que suas alteraçoes mesclem com o original.

* O usuario original, aceita ou não que suas alterações façam parte do projeto dele.

---
## Problemas (Issues)
* Permite usuários comunicarem problemas ou ideias sobre o repositório.

* Rastreia e gerência, tarefas, bugs e solicitações de recursos sobre o repositório.

* Outros membros podem fornecer feedback, perguntas ou soluções.

* As Issues são encerradas quando o problema for resolvido ou recurso implantado.

---
## GitHub Páginas
* Permite criar ilimitadas páginas web.

* Permite hospedar sites estáticos em HTML, CSS e JavaScript.

* Limitado quanto ao tamanho e uso de largura de banda.

* Não pode ser usado para hospedar sites dinâmicos.

---
# Linguagem Markdown
* Formata o texto para melhor legibilidade.

Abaixo estarão as formatações seguindo de como fazê-las. 

---
**Negrito**

`**Negrito**`

---
_Itálico_

`_Itálico_`

---
~~Riscado~~

`~~Riscado~~`

---
**_Negrito com Itálico_**

`**_Negrito com Itálico_**`

---
**~~Negrito Riscado~~**

`**~~Negrito Riscado~~**`

---
_~~Itálico Riscado~~_

`_~~Itálico Riscado~~_`

---
**_~~Negrito Itálico Riscado~~_**

`**_~~Negrito Itálico Riscado~~_**`

---
**Lista Numerada**
1. Teste
1. Teste
   1. Teste
   1. Teste
1. Teste
```
1. Teste
1. Teste
   1. Teste
   1. Teste
1. Teste
```

---
**Lista Demarcada**
 * Teste
 * Teste
    * Teste
    * Teste
 * Teste
 ```
  * Teste
 * Teste
    * Teste
    * Teste
 * Teste
 ```
 
 ---
 **Lista de Tarefas**
- [ ] Tarefa 1
- [ ] Tarefa 2
- [x] Tarefa 3
- [x] Tarefa 4
- [ ] Tarefa 5
```
- [ ] Tarefa 1
- [ ] Tarefa 2
- [x] Tarefa 3
- [x] Tarefa 4
- [ ] Tarefa 5
```
---
**Tabelas**
Num|Nome|Nota
---|---|---
1|Renato|10,00
2|Machado|10,00
3|Developer|10,00
4|GitHub|10,00
5|Manjaro|10,00

```
Num|Nome|Nota
---|---|---
1|Renato|10,00
2|Machado|10,00
3|Developer|10,00
4|GitHub|10,00
5|Manjaro|10,00
```

---
**Destacando um comando**

`document.get.ElementByid()`

Crase | Comando | Crase
---|---|---
`|Comando|`

---
**Destacar um trecho**
```
num = int(input('Digite um valor: ')
if num % 2 == 0:
    print(f'O valor {num} é PAR')
else:
    print(f'O valor {num} é ÍMPAR')
```
Crase | Trecho | Crase
---|---|---
```|Trecho|```

---
**Colocando Imagem**

![octo]()

`![Descrição Imagem](URL)`

Tamanho Ideal **400px ou 500px**

Formato Ideal **png ou jpg**

---
**Colocando Link**

[Descrição Link](https://)

`[Descrição Link](URL)`

---
# Título Nível 1

`# Título Nível 1`

---
## Título Nível 2

`## Título Nível 2`

---
### Título Nível 3

`### Título Nível 3`

---
**Colocando uma linha acima e uma linha abaixo para dividir o tópico.**

`---`

Tópico

`---`

---
## Bibliografia

YouTube: [Curso em Vídeo](https://www.youtube.com/@CursoemVideo)

Professor: Gustavo Guanabara

Playlist: [Curso de Git e GitHub: grátis, prático e sem usar comandos no terminal](https://www.youtube.com/watch?v=xEKo29OWILE&list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA&index=1)

---
[ChatGPT](https://chat.openai.com/auth/login?next=/chat)

---
[Documentação Oficial Git](https://git-scm.com/doc)

[Documentação Oficial GitHub](https://docs.github.com/pt)

---

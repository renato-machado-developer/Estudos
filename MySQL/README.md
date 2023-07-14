# MySQL
* Resumo simplista de banco de dados com MySQL.

## Principais Características
* MySQL é um Sistema de gerenciador de banco de dados relacionais. 
    
* Open Source - (Softwares de código aberto).
      
* Utilizado para inserir, acessar e gerenciar o conteúdo armazenado em banco de dados.
      
* Atraves da linguagem SQL (Structure Query Language) - ( Linguagem de Consulta Estruturada).
      
* Possui o servidor e uma interface gráfica cliente.
      
* Um dos componentes centrais da maioria das aplicações públicas da Internet.
    
---
## Historia 
* 1994 - Teve seu surgimento através da empresa sueca MySQL AB.
     
* 2008 - Foi comprada pela empresa norte-americana Sun Microsystems.
     
* 2010 - A Sun Micrososystems foi comprada pela Oracle, que se mantém dona do MySQL.
      
---
## Servidor
* Armazena os dados.
     
* Responder às requisições.
     
* Controlar a consistência dos dados.
     
* Execução de transações concomitantes.
     
* Entre outras.
      
---
## Cliente
* Se comunica com o servidor através da interface.
     
---
## O que é chave SSH
* Protocolos de rede seguros baseados em TLS (Transport Layer Security).
     
* Usam criptografia assimétrica durante o início de cada conexão, para
definir uma chave simétrica comum entre os dois computadores que se comunicam remotamente.
    
* Essa chave simétrica, chamada chave de sessão, usada para cifrar/decifrar os dados trocados entre os dois computadores durante aquela conexão, sendo descartada quando a sessão encerra.
    
* O SSH é usado para transferência remota de arquivos, gerenciamento de rede e acesso remoto ao sistema operacional.
    
*  O acrônimo SSH também é usado para descrever um conjunto de ferramentas usadas para interagir com o protocolo SSH.
      
### Funcionameto da chave SSH
* Alice sorteia uma chave secreta simétrica (chave de sessão).
    
* E a cifra com a chave pública de Bob (Para que só ele possa decifrá-la) (Garantindo Cofidencialidade).
    
* Alice cifra com sua chave privada (Garante Autenticidade).
    
* A chave duplamente cifrada e enviada a Bob.
    
* Bob usa sua chave privada para decrifar.
    
* Bob resgata a chave secreta (chave de sessão).
    
* Agora Alice e Bob podem usar a chave de sessão.
    
* Fazem agora suas transferencias e gerenciamentos.

### O que terceiros  podem acessar
* Se Mallory estiver capturando mensagens no canal de comunicação, ela terá acesso somente a chave privada de Alice.
    
* A mensagem que está cifrada. (Texto criptografado) (Informação incompreensível para aqueles que não devem ter acesso a ela).
    
* As chaves pública de Alice e Bob.
    
* O que não a permite descobrir a chave de sessão nem a mensagem aberta.

---
## Gerar chaves SSH no Mac e Linux 
* As chaves SSH são criadas usando uma ferramenta de geração de chaves.
    
* Os sistemas operacionais OS e Linux têm aplicativos de terminal que vêm com o pacote SSH instalado.
    
* Abra o Terminal `CTRL+ALT+T`.
    
* Execute `ssh-keygen` para iniciar a criação da chave.
  
* Vai ser solicitado um lugar para salvar a chave `Created directory '/home/username/.ssh'`
    
* Vai solicitar a criação de uma frase secreta `Enter passphrase (empty for no passphrase)` adicionando uma camada extra de segurança ao SSH e vai ser necessária sempre que a chave SSH for usada.
    
* Vai solicitar que confirme a frase secreta `Enter same passphrase again`.
    
* Se alguém obtivesse acesso ao computador em que as chaves privadas estão armazenadas, teria  acesso a qualquer sistema que use essa chave. Adicionar uma frase secreta vai evitar esse cenário.
    
* Vai ser gerada uma nova chave SSH no caminho especificado.
    
* Agora você tem uma chave pública e privada que pode usar para autenticar.

---
## Bibliografia

YouTube: [Curso em Vídeo](https://www.youtube.com/@CursoemVideo)

Professor: Gustavo Guanabara

Playlist:

---
[ChatGPT](https://chat.openai.com/auth/login?next=/chat)

---
---
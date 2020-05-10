# Aula TP - 11/Mai/2020

Cada grupo deve colocar a resposta às perguntas dos seguintes exercícios na área do seu grupo no Github até ao final do dia 25/Mai/2020. Por cada dia de atraso será descontado 0,15 valores à nota desse trabalho.

Note que estes exercícios podem ser feitos na máquina virtual disponibilizada.


**Instruções de instalação do _WebGoat_, para quem não utiliza a máquina virtual disponibilizada:**

Nesta aula vamos utilizar o **WebGoat** a partir de uma imagem Docker. O **WebGoat** é uma aplicação Web deliberadamente insegura mantida pelo OWASP, cujo objetivo é ser um complemento às aulas de segurança de aplicações Web, pelo que contém falhas aplicacionais comuns.

Pode instalar o Docker diretamente no sistema operativo do seu computador.

Se quiser **instalar o docker no seu computador** siga as instruções em https://store.docker.com/search?type=edition&offering=community relativas ao seu sistema operativo.  

Caso o sistema operativo do seu computador seja o mesmo da  máquina virtual, siga as seguintes instruções para instalar o docker:

1. `sudo apt-get update`

2. `sudo apt-get install apt-transport-https ca-certificates curl gnupg2 software-properties-common`

3. `curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -`

4. `sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/debian  $(lsb_release -cs) stable"`

5. `sudo apt-get update`

6. `sudo apt-get install docker-ce`


----

**Nota:** Sempre que nos exercícios abaixo lhe for pedido para utilizar o **WebGoat**, deve executar os seguintes passos:

1. Garantir que já instalou o docker no seu computador ou na máquina virtual.

2. Obter a versão 8.0 do WebGoat, através do comando `sudo docker pull webgoat/webgoat-8.0`

3. Arrancar o WebGoat com o comando `sudo docker run -p 8080:8080 -t webgoat/webgoat-8.0`.

    Note que o WebGoat demora 30 - 50 segundos a arrancar, tendo arrancado quando lhe aparecer no ecran uma linha que contenha a seguinte informação `INFO: Started StartWebGoat`

5. No Firefox da máquina virtual aceder a http://localhost:8080/WebGoat.


No final, para parar o docker e WebGoat, deverá efectuar os seguintes comandos:
+ `sudo docker ps` para obter o Container ID
+ `sudo docker kill <Container ID>` em que `<Container ID>` é o valor indicado no comando anterior para esse campo.
----


## Exercícios


### 1\. _Injection_

#### Experiência 1.1

Aceda a https://free.codebashing.com/courses/java e siga o exemplo de _SQL Injection_.


#### Experiência 1.2

Aceda a https://free.codebashing.com/courses/dotnet e siga o exemplo de _XXE Processing_.



#### Pergunta 1.1 - _SQL Injection_

No WebGoat siga a lição _(A1) Injection > SQL Injection (jntro)_.
Indique o que foi fazendo em cada um dos passos e qual o resultado.


Em todos os passos tente primeiro resolver sem ajuda. Se chegar a um ponto em que não consegue avançar, utilize "Show Hints" para ajuda. 



### 2\. XSS

#### Experiência 2.1

Aceda a https://free.codebashing.com/courses/nodejs e siga o exemplo de _Persistent (Stored) XSS_.

#### Pergunta 2.1 - _XSS_

No WebGoat siga a lição _(A7) Cross-site Scripting_.

Indique o que foi fazendo em cada um dos passos e qual o resultado.


Em todos os passos tente primeiro resolver sem ajuda. Se chegar a um ponto em que não consegue avançar, utilize "Show Hints" para ajuda. 




### 3\. Quebra na Autenticação

#### Pergunta 3.1 - _Password Reset_

No WebGoat siga a lição _(A2) Broken Authentication > Password Reset_.

Indique o que foi fazendo em cada um dos passos e qual o resultado.


Em todos os passos tente primeiro resolver sem ajuda. Se chegar a um ponto em que não consegue avançar, utilize "Show Hints" para ajuda. 

### 4\. Componentes vulneráveis

#### Pergunta 4.1 - _Vulnerable components_

No WebGoat siga a lição _(A9) Vulnerable Components_.

Indique o que foi fazendo em cada um dos passos e qual o resultado.


Em todos os passos tente primeiro resolver sem ajuda. Se chegar a um ponto em que não consegue avançar, utilize "Show Hints" para ajuda. 

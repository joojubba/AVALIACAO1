![N|Solid](https://apn-portal--c.na211.content.force.com/servlet/servlet.ImageServer?id=0158a000005eHP3AAM&oid=00DE0000000c48tMAA)

# Avaliação Sprint 1  📝





## Tema: Segurança de redes: Conheça as vulnerabilidades de servidores e clientes 



### 1. O que é um ataque DDoS e como posso me proteger?

​	É um ataque que consiste em tirar a concentração do ataque em um usuário e distribuir o ataque por vários usuários, um meio para acontecer é através de downloads de arquivos infectados, quando isso ocorre e a máquina é infectada, o hacker pode controlá-las para iniciar um ataque distribuído contra um serviço.  Uma medida para se proteger de ataques DDoS é utilizando Firewall, que é uma ferramenta de segurança que verifica o tráfego de rede dividindo em uma rede segura/interna e rede não segura/internet com uma política de acesso.

### 2. Por que o firewall é uma ferramenta muito importante de proteção?

​	O firewall faz essa divisão em rede segura e rede não segura analisando o tráfego de rede para determinar quais requisições de transmissão ou recepção de dados podem ser executadas, onde um usuário na rede interna (segura) poderá acessar dados que estão na rede externa (internet), mas um usuário da rede não segura não terá permissão de acessar dados da rede interna.



## Tema: Git e GitHub 



### 3. Explique de forma sucinta, o fluxo e envio de um arquivo novo para o repositório do projeto.

​	No terminal: cd (comando para navegar entre pastas) > ls (para listar os arquivos) > git init (iniciando um repositório) > git status (para verificar o estado do repositório) > git add . (para adicionar todos os arquivos da pasta ou colocar apenas o nome do arquivo) > git commit -m “” (para commitar/salvar o arquivo e “” para escrever a mensagem que deseja) > cd .. (volta uma pasta, ou onde queira salvar o servidor) > mkdir servidor (criar a pasta) > cd servidor/ (entra na pasta) >  git init --bare (repositório puro ) > cd (navega na pasta do arquivo/projeto) > git remote add local {url da pasta recém criada} > git remot -v (para verificar se o endereço está certo).

### 4. Descreva sobre os ganhos de se utilizar a funcionalidade da branch do git.

​	Como as branches são “ramos” usados para desenvolver funcionalidades isoladas umas das outras, a vantagem de utilizar é justamente poder alterar o código numa branch separada para não influenciar no funcionamento de outra, no qual é possível posteriormente unir os trabalhos. 

### 5. Explique a diferença entre criar o repositório na nuvem e iniciar o repositório a partir de um código existente local.

​	Na nuvem, como o GitHub, é criado o repositório com o nome desejado, pode adicionar uma descrição, direcionar se será público ou privado, escolher se deseja adicionar arquivos não rastreáveis e até licença para o que os outros podem ou não fazer no seu projeto, já que é possível outras pessoas contribuírem no projeto. Já iniciando o repositório a partir de um código existente local, como no Git, é feito através de linha de comando como no Git Bash, no qual pode ser criado o repositório com comandos, adicionar arquivos, colocar comentários, mas ao contrário da nuvem não tem essa interação com outros na internet para ajudar no projeto.

### 6. Qual a diferença entre Git e GitHub?

​	O Git é um sistema de versionamento de código distribuído que ajuda a criar e monitorar diversas versões do seu código e o GitHub é o repositório online onde armazena o seu código na nuvem. 



## Tema: Fundamentos de Agilidade: seus primeiros passos para a transformação ágil 



### 7. Quais as principais diferenças entre o modelo ágil e o waterfall (modelo em cascata)?

​	O modelo ágil tem como princípio entregar valor rápido, reduzindo custos de mudanças, o que implica que há uma priorização do que deve ser feito naquele momento para entregar ao cliente algo que tenha valor obtendo um feedback mais rápido e direcionando o fluxo de uma forma melhor e mais inteligente. Já que o Waterfall, ele só tinha um caminho a ser seguido, divido em fases e dependia da aprovação da fase anterior para prosseguir, que acaba demorando ainda mais para receber feedbacks para ter a avaliação se o fluxo estava no caminho certo ou precisaria ser alterado. 

### 8. Quais são as 3 perguntas que devem ser respondidas na Daily?

O que fez? O que fará? E quais problemas enfrentou? 

### 9. Qual o intuito das seguintes cerimônias?
#### • Daily

Ser uma reunião diária rápida, onde é compartilhado na equipe o que foi feito, o que fará e quais problemas enfrentando para que seja possível identificar qualquer problema e solucionar mais rápido.

#### • Planning

Nesse processo de planejamento, no qual o time inteiro participa para entender os itens trazidos pelo Product Owner, é planejar as tarefas no tempo disponível e definir a meta para a equipe na Sprint (time-box/tempo que o time tem para agregar valor para o usuário do projeto). 

#### • Refinamento

Nesse processo é de fragmentar as histórias mais importantes contidas no Product Backlog (a lista priorizada das histórias organizada pelo P.O) em partes menores para que seja adicionado valor ao usuário final.

#### • Review

Na reunião de revisão, onde se reúnem o cliente e a equipe, é de  avaliar os itens prontos e, se surgem novas mudanças adicionar no Product Backlog, de acordo com a prioridade.

#### • Retrospectiva

Nessa reunião participam todos da equipe e é dedicada à melhoria contínua, o intuito é de verificar as possibilidades para melhoria no próximo contato e apresentar ações tanto dos pontos positivos quanto dos negativos.

### 10. O que é a estimativa na metodologia ágil?

​	A estimativa na metodologia ágil mede o tamanho do trabalho e a velocidade da equipe para entregar valor com qualidade e rapidez ao cliente.



## Tema: Fundamentos HTTP

​	

### 11. O que é o protocolo HTTP? Qual a diferença entre HTTP e HTTPS?

O protocolo HTTP refere-se ao protocolo, conjunto de regras, que determina as regras de comunicação entre o cliente e servidor na internet. No HTTP, Hypertext Transfer Protocol, os dados são enviados em texto puro para o servidor, sendo visível para qualquer pessoa. Já o HTTPS é o protocolo HTTP com mais uma camada de segurança/criptografia SSL/TLS (Secure Sockets Layer / Transport Layer Security) com chave privada e com certificado digital, que guarda a chave pública, no servidor.

### 12. Cite 4 métodos HTTP

GET: receber dados, utilizado para busca de informações, parâmetro na URL;

POST: submeter dados, criação de recursos, parâmetros no corpo da requisição;

DELETE: remover um recurso;

PUT: atualizar um recurso.

# [Homework 2](https://github.com/vinicius3w/if1007-Microservices/blob/master/hw/HW2.md)

## 2.1 SOA - Service-Oriented Architecture

### Concepts & Principles 

È um conceito de arquitetura que seu fundamento se baseia na disponibilização de funcionalidades através de serviços, esses serviços se comunicam através de uma interface que são comumente acessiveis através de web services.

Seus princípios se baseiam em uma explicita definição de limites que fala sobre o fornecimento de tudo que for necessário para que uma função de um serviço seja executada, o compartilhamento de contratos e esquemas que fala sobre o provedor ter tudo o que for necessário para prover quanto o consumidor tenha tudo que for necessário para consumir os serviços, a autonomia que define que um serviço tenha seu escopo bem definido e que sua comunicação deva ser feita através de sua interface e orientação a documentos que define que toda comunicação entre os serviços deva ser feita através de dados passados no formato de documentos.

### Service-oriented integration

Service-oriented integration casa bem com SOA pelo fato dos serviços terem suas interfaces bem definidas e por muitas vezes se comunicarem através de web services se utilizando de tecnologias como REST ou RESTfull, todos os serviços são construídos para serem integrados e os princípios presentes no conceito de arquitetura orientada a integração batem com os princípios da arquitetura orientada a serviço fazendo com que ambos os conceitos possam ser aplicados ao mesmo tempo.

### Legacy modernization

A migração de softwares monolícos para uma arquitetura SOA pdoe ser feita através de várias estratégias, são elas: Ativação de serviços, Conversão de linguagens, Re-arquitetura ou uma Re-hospedagem de aplicações, ou seja, os monolíticos também podem ser migrados para um arquitetura SOA atarvés das estratégias sitadas anteriormente, cada uma delas tem seus pontos positivos e negativos, a utilização de uma delas se vai de acordo com a realidade atual do software a ser migrado e das condições atuais de investimento que possam sser realizadpos em uma das estratégias.

### Service-oriented application

Arquitetura orientada a serviço trata da arquitetureação da aplicação do seu ponto de vista de infraestrutura para que as funcionalidades possam ser fornecidas através de serviços já a arquitetura orientada a aplicação trata da arquitetura interna da aplicação para que seu desenvolvimento seja de tal forma que facilite a disponibilização de suas funcionalidades através de serviços fazendo com que ambos os conceitos possam ser utilizados para arquiteturar uma aplicação tanto do ponto de vista de sua infraestrtutura como de código.


## 2.2 Relations between microservices and [Twelve-Factor](https://12factor.net/) apps

Os conceito de arquitetura orientada a serviço se adequam em todos os pontos das metodologias levantadas no Twelve-Factor, durante oprocesso de desenvolvimento do serviço pode-se aplicar as metodologias do Twelve-Factor para que a aplicação se beneficie com os pontos positivos trazidos pelos conceitos de SOA bem como pela aplicação das metologias.

## 2.3 Orbitz transition to SOA

## Fontes

1. [Vantagens e Desvantagens de SOA](https://www.devmedia.com.br/vantagens-e-desvantagens-de-soa/27437)
1. [Service-oriented architecture](https://pt.wikipedia.org/wiki/Service-oriented_architecture#Defini%C3%A7%C3%B5es_de_SOA)
1. [10 Principles of SOA](https://www.infoq.com/articles/tilkov-10-soa-principles)
1. [service-oriented integration (SOI)](http://searchmicroservices.techtarget.com/definition/service-oriented-integration-SOI)
1. [Service-Oriented Integration](https://msdn.microsoft.com/en-us/library/ff647687.aspx)
1. [Legacy Evolution to SOA – Best Practices](http://www.opengroup.org/soa/source-book/l2soa/p4.htm)
1. [Service Oriented Applications: What is SOA?](https://www.youtube.com/watch?v=w-JxEJg20Ps)
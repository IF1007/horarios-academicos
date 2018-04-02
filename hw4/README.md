# [Homework 4](https://github.com/vinicius3w/if1007-Microservices/blob/master/hw/HW4.md)

## 4.1. Service endpoint design consideration

### What is the main concepts and principles of Consumer Driven Contracts (CDC)?
    É um padrão definido para que dados sejam transferidos entre consumidor(aplicação) e provedor(api) fazendo com que ambos se comuniquem
    através de padrões estabelecidos, normalmente o formato em que os dados serão trasnferidos é definido pelo consumidor e correspondido pelo
    fornecedor.

### How does it fit into the microservices approach?
    Em microserviços o conceito de CDC é utilizado para a transferencias de dados através das apis, comumente em microserviços
    são fornecidos apis e nessas apis são estabelecidas padrões de comunicações para que outras aplicações possam se comunicar com esse
    serviço fornecendo as informações suficientes para que ele possa ser executado e retorne as informações desejadas, com isso
    esses padrões estabelecidos podem ser vercionados para que a atualizações dessas apis não causem problemas quando seus contratos são
    alterados para a utilização de novas funcionalidades nesses serviços.

### How Postel's law could be also relevant in this scenario?
    Sim, como Postel's law fala sobre ser claro no que você aceita dos outros e no que você faz isso casa perfeitamente com os principios
    de microserviços utilizando o CDC quando que os contratos devem ser 100% claros para que as comunicações sejam o mais eficientes possíveis.

### What are the main solutions (patterns, architectural styles, tools, etc.) to implement:

    - Message-oriented services
        - Pode-se se utilizar de middlewares que possibilitem esse serviço de menssagem, Message-oriented middleware(MOM) possibilita essa funcionalidade,
    podendo ele ser um software ou um hardware ele pode ser incorporado nos serviços para que possa dar suporte a menssagens em sistemas distribuidos.
    - HTTP and REST endpoints;
        - SOA é um dos estilos de arquitetura muito difundido para a criação de apis rest.
    - Optimized communication protocols;
        - ProtocolBuffers é uma linguagem neutra do google utilizada para sereliação de dados pequena, rápida e simples.
    - API documentations.
        - A utilização do swagger é muito comum para as pessoas que trabalham com Spring para uma geração automatica de documentação da API. 

## Fontes

1. [Consumer-Driven Contracts](https://thoughtworks.github.io/pacto/patterns/cdc/)
1. [Introduction to Microservices Testing and Consumer Driven Contract Testing with PACT](https://blog.novatec-gmbh.de/introduction-microservices-testing-consumer-driven-contract-testing-pact/)
1. [Consumer-Driven Contracts: A Service Evolution Pattern](https://www.martinfowler.com/articles/consumerDrivenContracts.html)
1. [Robustness principle](https://en.wikipedia.org/wiki/Robustness_principle)
1. [Message-oriented middleware](https://en.wikipedia.org/wiki/Message-oriented_middleware)
1. [Google Protocol Buffers](https://developers.google.com/protocol-buffers/)
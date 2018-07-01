# Projeto para a cadeira [IF1007](https://github.com/vinicius3w/if1007-Microservices) - Horários acadêmicos

### Descrição
O projeto tem como intuito fornecer a grade de horários do período no qual o aluno está matriculado, para isso temos um [serviço de autenticação](https://github.com/jbsn94/apiauthescolas)
que fornecerá todas as informações necessárias do aluno e o [serviço de horários acadêmicos](https://github.com/jbsn94/laravel-horarioaulas) que contem todos os horários dos períodos de cada curso.

### Equipe
* José Barbosa da Silva Neto ([jbsn@cin.ufpe.br](mailto:jbsn@cin.ufpe.br))

### Repositórios
- API de autenticação
    - https://github.com/jbsn94/apiauthescolas
- API dos horários acâdemicos
    - https://github.com/jbsn94/laravel-horarioaulas
- Docker para levantamento dos serviços
    - https://github.com/jbsn94/docker01

No **README** de cada repositório constam explicações mais detalhadas de cada serviço bem como do levantamento dos serviços utilizando o *docker* e *docker-compose*.

### Tecnologias utilizadas
- PHP 7.1
- Mysql 5.7
- Docker
- Docker-compose
- Framework laravel 5.6

### Cronograma
| Data   | Descrição                              |
|:------:|----------------------------------------|
|Jun-01|Início do projeto|
|Jun-01 ~ Jun-03|Elaboração conceitual da arquitetura do projeto|
|Jun-04 ~ Jun-11|Construção da aplicação de horários acadêmicos|
|Jun-12 ~ Jun-15|Construção da aplicação de autenticação|
|Jun-16 ~ Jun-26|Adaptando a aplicação para utilização dos containers em Docker|
|Jun-27 ~ Jun-29|Utilizando o docker-compose para o levantamento de ambientes para os serviços|

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
|Semanas| Data   | Descrição                              |
|:----:|:-------:|------------------------------|
|**1**|01 a 09|Início do projeto e elaboração conceitual da arquitetura do projeto|
|**2**|10 a 16|Construção da aplicação de horários acadêmicos|
|**3**|17 a 23|Construção da aplicação de autenticação|
|**4**|24 a 30|Ajustes finais do projeto e criação das imagens *Dockers* e utilização do *Docker-compose*|

### Arquitetura
![arquitetura](/arquitetura.png)

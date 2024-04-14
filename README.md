# Desafio dio - REST API de Reuniões 
# Sistema para reserva de sala de reunião.

O objetivo deste é permitir que um usuário responsável pela tarefa (agendamento de salas), consiga cadastrar colaboradores, salas e por fim com esses registros, agendar a sala específica para o colaborador solicitante. Neste Labs iremos desenvolver uma API com Spring Boot para gerenciar nossas salas de reunião, utilizaremos o Spring Data para persistência de dados e o banco in-memory H2. E o Front End que irá consumir essa API será uma SPA escrita em Angular.

### Projeto consiste em um gerenciador de salas de reuniões com uma API Java e o front em Angular

-    O Front End que irá consumir essa API será uma SPA escrita em Angular.      

  ​            

### Lógica geral do sistema

Ao inserir um novo agendamento, ele irá filtrar as salas disponiveis de acordo com a data, hora inicial e final da reunião, se a sala necessita ter computador, sistema para videoconferência, ou projetor, dados esses, especificados pelo solicitante da reunião. Desafio para desenvolver uma API com Spring Boot para gerenciar salas de reunião, com Backend em Java e Front End em Angular, onde podemos criar salas de reunião, listar as salas, e buscar, atualiza ou deletar uma sala pelo id.

### O sistema

Este sistema foi desenvolvido com duas tecnologias atuais, uma para o frontend (Angular 9), e outra para o backend (Laravel 6), sendo esta última desenvolvida no formato API RestFull. Para entender os requisitos e processo de instalação de cada framework e suas bibliotecas, segue o guia (Readme) de cada um

#### Pasta Back-end --> Crud-SalaDeReuniao

- Foi desenvolvido uma API com Spring Boot para gerenciar nossas salas de reunião
- Utilizaremos o Spring Data para persistência de dados e o banco in-memory H2.

#### Pasta front-end --> front-SalaDeReuniao

- O Front End que irá consumir essa API será uma SPA escrita em Angular.

  

## Server de Desenvolvimento

Rode o servidor local através do comando`ng serve`. Vá até o endereço `http://localhost:4200/`.

É necessário também rodar a aplicação SpringBoot para termos acesso a API

## Endpoints criados na API

- Criar sala de reuniao (POST - /api/v1/rooms)
- Listar todas as salas (GET - /api/v1/rooms)
- Buscar uma sala pelo Id (GET - /api/v1/rooms/{id})
- Atualizar uma sala pelo Id (PUT - /api/v1/rooms/{id})
- Excluir uma sala pelo id (DELETE - /api/v1/rooms/{Id})

## Requirements

* Linux
* Git
* Java 11
* Netbeans 13

## DataBase

H2

## Spring Boot

* [https://start.spring.io/](https://start.spring.io/)

+ Java 11
+ Maven Project
+ Spring Web
+ Spring Data JPA
+ H2 Driver

### Spring Data

* [jpa.query-methods](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.query-methods)

### Properties

* [appendix-application-properties](https://docs.spring.io/spring-boot/docs/current/reference/html/appendix-application-properties.html)
* [jdbc-database-connectio](https://www.codejava.net/java-se/jdbc/jdbc-database-connection-url-for-common-databases)

### Types

* [JsonTypes](https://github.com/vladmihalcea/hibernate-types)
* [UserType](https://docs.jboss.org/hibernate/orm/3.5/api/org/hibernate/usertype/UserType.html)

## Heroku

* [DevCenter](https://devcenter.heroku.com/articles/getting-started-with-gradle-on-heroku)


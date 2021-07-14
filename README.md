# API Rest para Gerenciamento de Usuários 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/valsonpereira/person-api/blob/main/LICENSE) 

# Sobre o projeto

Esta API Rest para gerenciamento de usuários é uma aplicação back-end com desenvolvida durante a live coding do instrutor Rodrigo Peleias organizada pela [Digital Innovation One](https://digitalinnovation.one/ "Site da Digital Innovation One").

A aplicação consiste em uma API construída com Spring Boot que realiza as operações básicas de CRUD (criação, leitura, atualização e exclusão) para gerenciamento de usuários. 

### Link da API em produção 

https://peopleapi-valson.herokuapp.com/v1/people

Obs.: Em razão do deploy ser realizado utilizando o plano gratuito do Heroku, a API pode levar alguns segundos para realizar as requisições.


## Modelo de dados
![Modelo de dados](https://raw.githubusercontent.com/valsonpereira/my-assets/main/person-api/modelo_dados.png)

# Tecnologias utilizadas
## Back-end
- Java 11
- Spring Boot
- Spring Data JPA 
- Maven
- H2 Database

# Como executar o projeto

Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/valsonpereira/person-api.git

# entrar na pasta do projeto back-end
cd person-api

# executar o projeto
./mvnw spring-boot:run

# endereço local para realizar as requisições REST
http://localhost:8080/api/v1/people
```


# Autor

Valson Pereira

https://www.linkedin.com/in/valson-java-developer
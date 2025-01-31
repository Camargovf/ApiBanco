


<h1 align="center">
    <img alt="Springboot" title="#Springboot" src="https://raw.githubusercontent.com/Camargovf/v1-restapi-produtos/cf7d945cf5c13aa553bfc93006f69942ce8e0bba/springboot.jpeg" />
</h1>

### ⚙️ Acesso direto ao repositório: [CODE FONTE](https://github.com/Camargovf/ApiBanco/tree/master)<br>
 Código Fonte : https://github.com/Camargovf/ApiBanco/tree/master<br>

<h1 align="center">Rest API realizada em Springboot  </h1>

## 📄Descrição do Projeto
<p align="center"> Aplicação criada em ambiente Spring - Crud para cadastro de clientes relacionados com conta e regra de negocio bancario.<br> 
 Projeto ambientado com Springboot em IDE Intelijj com banco de dados PostgreSQL.  </p>
 
 ## Novas Features
 <p align="center"> O projeto esta ambientado para receber novas features, a implementacao de funcoes como deposito-saque e afins prontos para implementacao.  </p>
 

## 📝 CURL - COMANDOS RESTAPI. 

Listar todos os clientes.

```javascript

curl --location --request GET 'http://localhost:8080/clientes'

```

Criar/Alterar/Deletar um cliente (POST, PUT, DELETE)

```javascript

curl --location --request POST 'http://localhost:8080/clientes' \
--header 'Content-Type: application/json' \
--data-raw '{
    "id": 3,
    "nome": "xxxx",
    "cpf": "223123",
    "telefone": "3278683",
    "cep": "487772"
}'

```
CURL para Conta relacionado com Cliente (Saldo)

```javascript
curl --location --request POST 'http://localhost:8080/contas' \
--header 'Content-Type: application/json' \
--data-raw '{
"cliente": {
        "id": 1
    },
"conta": {
        "saldo": 522
    }
}'
```

<a href="https://ibb.co/cQDQJys"><img src="https://i.ibb.co/Hqnq7K9/Captura-de-Tela-2022-03-29-s-16-21-21.png" alt="Captura-de-Tela-2022-03-29-s-16-21-21" border="0"></a>


### 📖 Sobre

- O projeto é a realização de um CRUD para trabalhar com clientes e relacionar com a conta do banco. Cadastrar, alterar, deletar, atualizar e puxar o saldo do cliente. - são as possibilidades dessa API. O projeto foi realizado com o banco de dados relacional PostgreSQL. 

### 🛠 Tecnologias

Ferramentas como flyway para versionar SQL com Hibernate/JPA para persistir no banco de dados e criar registros de log, Swagger para documentar a API, Maven para gerenciar as dependências, além do uso do Postman para testar o funcinamento da aplicação. Para a agilidade da construção do código foi utilizado devtools em tempo real, além de outras tecnologias de suporte.

As seguintes ferramentas foram usadas na construção do projeto:

- [SpringBoot](https://spring.io/projects/spring-boot)
- [Maven](http://maven.apache.org)
- [PostgreSQL](https://www.postgresql.org)
- [Flyway](https://flywaydb.org)
- [Hibernate](https://hibernate.org)
- [SpringBoot](https://spring.io)

### 📚 Documentação 

- Realizada em Swagger para fácil manutenção e consumo da api.


### Author.   Valdeir Camargo -  BackEnd Java/Javascript Dev.
<br />
<img alt="Camargovf" title="#Camargovf" src="https://github.com/Camargovf/Camargovf/blob/main/IMG_1202_Easy-Resize.com.jpg?raw=true" /> 

[![Github](https://img.shields.io/badge/-Github-000?style=flat&logo=Github&logoColor=white)](https://github.com/Camargovf)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/camargovf/)
[![Gmail](https://img.shields.io/badge/-Gmail-c14438?style=flat&logo=Gmail&logoColor=white)](mailto:contato@valdeircamargo.com)

<br />

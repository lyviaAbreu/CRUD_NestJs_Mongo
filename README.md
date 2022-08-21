# CRUD_NestJs_Mongo

Projeto realizado por Lyvia e Arthur para a disciplina de Computação em Nuvem da UFLA.

## O que faz:

O projeto é uma api para fazer CRUD de um usuário na nuvem. O banco de dados é o MongoDb, que tambem está na nuvem.

## Como utilizar na nuvem:

Get:
https://crudnestjsmongo.herokuapp.com/users/ <br><br>

Get específico de um usuário: https://crudnestjsmongo.herokuapp.com/users/{id} <br><br>

Post:
https://crudnestjsmongo.herokuapp.com/users <br>
Body:
{
"name": "lyvia",
"email": "lyvia.a.ne@gmail.com",
"password": "lyvia"
}
<br><br>

Patch: https://crudnestjsmongo.herokuapp.com/user/{id}
<br>
Body:
{
"name": "lyvia",
"email": "lyvia.a.ne@gmail.com",
"password": "lyvia"
}
<br><br>

Delete:
https://crudnestjsmongo.herokuapp.com/user/{id}
<br>
<br>

## Como utilizar localmente:

Para instalar os pacotes:
npm install
<br>

Para rodar: npm start

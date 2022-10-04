# Desafio 2 - Trabalhando com middlewares

## Desafio:

- Criar um usuário com username
- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

## Requisitos

- [x] Should be able to find user by username in header and pass it to request.user
- [x] Should be able to let user create a new todo when is in free plan and have less than ten todos
- [x] Should be able to let user create infinite new todos when is in Pro plan
- [x] Should be able to put user and todo in request when both exits
- [x] Should be able to find user by id route param and pass it to request.user
- [x] Should be able to delete a todo

## Regras de Negócio

- [x] Should not be able to find a non existing user by username in header
- [x] Should not be able to let user create a new todo when is not Pro and already have ten todos
- [x] Should not be able to put user and todo in request when user does not exists
- [x] Should not be able to put user and todo in request when todo id is not uuid
- [x] Should not be able to put user and todo in request when todo does not exists
- [x] Should not be able to pass user to request.user when it does not exists

# Install

Clone this repository and install it dependencies with this command:
```sh
$ npm install
```
Run the application with npm run dev command, it will start the app:
```sh
$ npm run dev
```
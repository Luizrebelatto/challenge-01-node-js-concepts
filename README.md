<h1 align="center">To Do</h1>

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-bibliotecas">Bibliotecas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-rotas">Rotas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;
</p>

<br>

## 💻 Projeto

Aplicação para Gerenciamento de Tarefas

## ✨ Tecnologias
- Node
- JavaScript
- Insomnia
- express
- nodemon

## 📚 Bibliotecas
- uuid
- supertest
- cors
- jest

## 💻 Funcionalidades
- Criar Usuário
- Cadastrar Tarefas
- Mostrar Tarefas
- Atualizar titulo e prazo da tarefa
- Alterar estado da tarefa
- Deletar tarefa

## ✔️ Requisitos

- [x] checksExistsUserAccount
- [x] checksExistsTodos

## 💻 Testes
- [x] Users should be able to create a new user
- [x] Users should not be able to create a new user when username already exists
- [x] Todos should be able to list all user's todo
- [x] Todos should be able to create a new todo
- [x] Todos should be able to update a todo
- [x] Todos should not be able to update a non existing todo
- [x] Todos should be able to mark a todo as done
- [x] Todos should not be able to mark a non existing todo as done
- [x] Todos should not be able to delete a non existing todo
- [x] Todos should be able to delete a todo


## 📱 Rotas

- POST → /users
- POST → /todos
- GET → /todos
- PUT → /todos/:id
- PATCH → /todos/:id/done
- DELETE → /todos/:id


## 🚀 Como executar

1) Clonar o projeto do github:
    `git clone https://github.com/Luizrebelatto/challenge-01-node-js-concepts.git`

2) Abrir terminal(CMD/TERMINAL ou VSCode/CMD) e acessar a pasta raiz do projeto (pelo terminal).
    

3) Instalar Dependências:
  execute `yarn`


4) Rodar Aplicação no http://localhost:3333:
    `yarn dev`
    
5) Rodar testes:
    `yarn test`
      
---

Desenvolvido por👋🏻:
- [Luiz Gabriel Rebelatto](https://www.linkedin.com/in/luiz-gabriel-rebelatto-bianchi-67097413b/)



<p align="right"><a href="#-descrição">Leia em Português</a></p>

# ByteBank API

![Project Screenshot](bytebank-api-screenshot-0.png)

A mock RESTful API for the ByteBank application, built with **Node.js** and **json-server**. It simulates a backend for managing financial transactions and includes JWT-based user authentication.

---

## 📝 Description

This project serves as a mock backend for a conceptual ByteBank frontend application. It uses `json-server` to provide RESTful endpoints that serve transaction and balance data from a `db.json` file. Additionally, it implements a custom authentication layer with public routes for registration and login, while protecting other routes with JSON Web Tokens (JWT). The goal is to provide a realistic backend experience for frontend development without the need for a real database.

## ✨ Key Features

- **User Authentication:** Endpoints for user registration (`/public/cadastrar`) and login (`/public/login`).
- **JWT Token Generation:** Secure authentication using JSON Web Tokens (JWT) for protected routes.
- **Transaction Management:** CRUD operations on financial transactions served via `json-server`.
- **Balance Inquiry:** An endpoint to retrieve the current account balance.

## 🛠️ Technologies Used

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![JSON Server](https://img.shields.io/badge/JSON%20Server-333333?style=for-the-badge&logo=json&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

**Prerequisites**

You need to have [Node.js](https://nodejs.org/) installed on your system.

**Installation**

1.  Clone the repository:
    ```bash
    git clone https://github.com/Buenohy/bytebank-api.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd bytebank-api
    ```
3.  Install the dependencies:
    ```bash
    npm install
    ```
4.  Run the server:
    ```bash
    npm run start-api
    ```
5.  The server will be running at `http://localhost:8000`.

## 👨‍💻 Author

Made with ❤️ by **Gabriel Bueno Hygino**

## ⚖️ License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for more details.

---

<p align="right"><a href="#-description">Read in English</a></p>

# API do ByteBank

![Screenshot do Projeto](bytebank-api-screenshot-0.png)

Uma API RESTful mock para a aplicação ByteBank, construída com **Node.js** e **json-server**. Ela simula um backend para gerenciar transações financeiras e inclui autenticação de usuários baseada em JWT.

---

## 📝 Descrição

Este projeto serve como um backend simulado (mock) para uma aplicação de frontend do ByteBank. Ele utiliza `json-server` para fornecer endpoints RESTful que servem dados de transações e saldo a partir de um arquivo `db.json`. Além disso, implementa uma camada de autenticação personalizada com rotas públicas para cadastro e login, protegendo as demais rotas com JSON Web Tokens (JWT). O objetivo é fornecer uma experiência de backend realista para o desenvolvimento do frontend, sem a necessidade de um banco de dados real.

## ✨ Principais Funcionalidades

- **Autenticação de Usuários:** Endpoints para cadastro (`/public/cadastrar`) e login (`/public/login`) de usuários.
- **Geração de Token JWT:** Autenticação segura utilizando JSON Web Tokens (JWT) para as rotas protegidas.
- **Gerenciamento de Transações:** Operações CRUD em transações financeiras servidas via `json-server`.
- **Consulta de Saldo:** Endpoint para recuperar o saldo atual da conta.

## 🛠️ Tecnologias Utilizadas

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![JSON Server](https://img.shields.io/badge/JSON%20Server-333333?style=for-the-badge&logo=json&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🚀 Como Executar

Siga estas instruções para obter uma cópia do projeto em execução na sua máquina local para fins de desenvolvimento e teste.

**Pré-requisitos**

Você precisa ter o [Node.js](https://nodejs.org/) instalado no seu sistema.

**Instalação**

1.  Clone o repositório:
    ```bash
    git clone https://github.com/Buenohy/bytebank-api.git
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd bytebank-api
    ```
3.  Instale as dependências:
    ```bash
    npm install
    ```
4.  Execute o servidor:
    ```bash
    npm run start-api
    ```
5.  O servidor estará rodando em `http://localhost:8000`.

## 👨‍💻 Autor

Feito com ❤️ por **Gabriel Bueno Hygino**

## ⚖️ Licença

Este projeto está licenciado sob a Licença ISC. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

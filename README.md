![Node.js](https://img.shields.io/badge/Node.js-Backend-339933)
![Express](https://img.shields.io/badge/Express-REST_API-black)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748)
![Status](https://img.shields.io/badge/API-Online-success)

# ⚙️ User Management API

API REST desenvolvida com Node.js, Express, Prisma ORM e MongoDB para gerenciamento de usuários.

A aplicação fornece operações completas de CRUD, servindo como camada de dados para aplicações frontend e demonstrando conceitos fundamentais de desenvolvimento backend moderno.

## 🌐 Aplicação Integrada

Frontend em produção:

https://cadastro-usuarios-react-eight.vercel.app

A API está publicada em ambiente cloud e integrada ao frontend através de requisições HTTP utilizando Axios.

---

## 📖 Visão Geral

A API foi construída seguindo a arquitetura REST, permitindo que aplicações clientes realizem operações de criação, consulta, atualização e remoção de usuários.

---

## 🚀 Funcionalidades

### Gestão de Usuários

* Cadastro de usuários
* Consulta de usuários cadastrados
* Atualização de registros
* Exclusão de usuários

### Persistência de Dados

* Integração com MongoDB
* Modelagem através do Prisma ORM
* Operações otimizadas de leitura e escrita

### Integração

A API foi desenvolvida para integração com aplicações frontend utilizando requisições HTTP.

---

## 🛠️ Tecnologias

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb" />
</p>

### Backend

* Node.js
* Express

### Banco de Dados

* MongoDB

### ORM

* Prisma ORM

### Utilitários

* CORS

---

## ☁️ Infraestrutura

### Backend

* Render

### Banco de Dados

* MongoDB Atlas

### ORM

* Prisma ORM

---

## 📡 Endpoints

| Método | Endpoint      | Descrição         |
| ------ | ------------- | ----------------- |
| GET    | /usuarios     | Listar usuários   |
| POST   | /usuarios     | Criar usuário     |
| PUT    | /usuarios/:id | Atualizar usuário |
| DELETE | /usuarios/:id | Remover usuário   |

---

## 🏗️ Arquitetura

```text
Client
   │
   ▼
Express
   │
   ▼
Prisma Client
   │
   ▼
MongoDB
```

---

## 📂 Estrutura do Projeto

```text
prisma
│
└── schema.prisma

server.js
```

---

## 🔄 Fluxo da Requisição

```text
Request
   │
   ▼
Express
   │
   ▼
Prisma ORM
   │
   ▼
MongoDB
   │
   ▼
Response
```

---

## 🎯 Objetivos Técnicos

* Desenvolvimento de APIs REST
* Integração com MongoDB
* Utilização do Prisma ORM
* Operações CRUD
* Comunicação entre Frontend e Backend
* Estruturação de aplicações Full Stack
* Deploy de APIs em produção

---

## 👨‍💻 Autor

Desenvolvido por Lucas Fernandes.

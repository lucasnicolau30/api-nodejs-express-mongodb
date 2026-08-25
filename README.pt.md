# API NodeJs Express MongoDb SQL

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

Leia em: [English](README.md) | **Português**

API REST backend construída com Node.js, Express e MongoDB (Mongoose), seguindo o padrão MVC. Inclui sessões de usuário, gerenciamento de recursos e um pequeno módulo introdutório de Express.

## Estrutura

```
.
├── backend/               (API REST principal - Express + Mongoose)
│   └── src/
│       ├── controllers/    (SessionController, HouseController, DashboardController, ReserveController)
│       ├── models/         (User, House, Reserve)
│       ├── routes.js
│       ├── app.js
│       └── server.js
└── modulo01/               (Módulo/exercícios introdutórios de Express)
```

## Funcionalidades

- Autenticação de sessão (`POST /sessions`)
- CRUD de casas (`GET`, `POST`, `PUT`, `DELETE /houses`)
- Criação, listagem e cancelamento de reservas (`/houses/:house_id/reserve`, `/reserves`)
- Resumo do dashboard (`GET /dashboard`)

## Configuração

```
cd backend
npm install
npm run dev
```

## Autor

Lucas Nicolau — Estudante de Engenharia de Software na [@UFAM](https://github.com/UFAM)

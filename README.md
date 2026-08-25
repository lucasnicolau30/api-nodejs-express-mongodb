# API NodeJs Express MongoDb SQL

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

Read in: **English** | [Português](README.pt.md)

Backend REST API built with Node.js, Express and MongoDB (Mongoose), following the MVC pattern. Includes user sessions, resource management, and a small introductory Express module.

## Structure

```
.
├── backend/               (Main REST API - Express + Mongoose)
│   └── src/
│       ├── controllers/    (SessionController, HouseController, DashboardController, ReserveController)
│       ├── models/         (User, House, Reserve)
│       ├── routes.js
│       ├── app.js
│       └── server.js
└── modulo01/               (Introductory Express module/exercises)
```

## Features

- Session authentication (`POST /sessions`)
- CRUD for houses (`GET`, `POST`, `PUT`, `DELETE /houses`)
- Reserve creation, listing and cancellation (`/houses/:house_id/reserve`, `/reserves`)
- Dashboard summary (`GET /dashboard`)

## Setup

```
cd backend
npm install
npm run dev
```

## Author

Lucas Nicolau — Software Engineering Student at [@UFAM](https://github.com/UFAM)

# Nest Backend

This is a TypeScript-based backend project built with the [NestJS Framework](https://github.com/nestjs/nest). 

## Description

This project serves as a starter template for creating scalable and modular backends using NestJS. It includes support for MongoDB, environment configuration, and testing.

---

## Requirements

- Node.js - v^18.19.1 or newer
- npm (Node Package Manager, usually bundled with Node.js)
- Docker and Docker Compose (for database setup)
- MongoDB (via Docker)
- MongoDB Compass

---

## Project setup

#### Install Dependencies

Run the following command to install the required Node modules and dependencies:

```bash
npm install
```

#### Environment configuration

Copy the ```.env.template``` file and rename it to ```.env```


#### Database Setup

To run the MongoDB database using Docker, execute the following command:

```bash
docker compose up -d
```

## Compile and run the project

```bash
# development
npm run start

# watch mode
npm run start:dev

# production mode
npm run start:prod
```

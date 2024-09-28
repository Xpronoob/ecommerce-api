# Ecommerce API using clean architecture

## Description

Ecommerce system and JWT Authentication build on clean architecture

## Stack / Framework used

Built with:

[Typescript](https://www.typescriptlang.org/) | [Node.js](https://nodejs.org/en/) | [Express.js](https://expressjs.com/) | [Mongo](https://mongodb.com/) | [JWT](https://jwt.io/) | [Bcrypt](https://www.npmjs.com/package/bcrypt) | [Docker](https://www.docker.com/) | [Jest](https://jestjs.io/)

## Authentication

    GET     /api/auth/login
    GET     /api/auth/register
    GET     /api/auth/logout
    GET     /api/auth/me

## Users

    GET     /api/v1/users
    GET     /api/v1/users/:id
    POST    /api/v1/users
    PUT     /api/v1/users/:id
    DELETE  /api/v1/users/:id
    GET     /api/v1/users/get/count

## License

## Installation

Run docker

    docker compose up -

Configure environment variables .env file

    # Configuration
    FRONTEND_URL=
    PORT=3030
    DEBUG_MODE=

    # Database
    MONGO_URL=
    MONGO_DB_NAME=

    # JWT Private Key
    JWT_ACCESS_TOKEN=
    JWT_REFRESH_TOKEN=

    # Cookies expiration time
    # Time units: s, m, h, d
    COOKIE_EXPIRES_ACCESS_TOKEN=5s
    COOKIE_EXPIRES_REFRESH_TOKEN=120d

Run development environment

    pnpm run dev

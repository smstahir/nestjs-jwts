# Intro to NestJs

A brief Intro how to implement an authentication system in NestJs using passport.js, and json web tokens (JWT) and end to end testing.

## Pre-req

You have to install

- Node js 16
- Docker
- Nestjs

## Installation

Install modules

```bash
  npm install
  or
  yarn install
```

## Run the API in development mode

```
npm run db:dev:restart // start postgres in docker and push migrations
or
yarn db:dev:restart
npm run start:dev // start api in dev mode
or
yarn start:dev
```

## Running Tests

To run tests, run the following command

```bash
  npm run test:e2e
  or
  yarn test:e2e
```

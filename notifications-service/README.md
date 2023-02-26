## Description

Projeto do ignite lab de nodejs da Rocketseat

## Tecnologies

NestJs

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## PrismaConfig

npm i prisma -D

npm i @prisma/client

npx prisma init --datasource-provider SQLite

criat tabela:
npx prisma migrate dev

visualizar banco:
npx prisma studio


test:cov para ver cobertura de testes

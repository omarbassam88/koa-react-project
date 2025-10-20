# Koa + React project

A minimal Fullstack repo using Typescript, Koa for the backend and React for the frontend.

## Requirements

- Node.js
- pnpm
- docker

## Setup

To install the dependencies for all packages:

``` shell
pnpm i
```

## Build

To build all packages in the packages folder
``` shell
pnpm -r build
```

## Running the application

You first need to run the database using docker-compose:

``` shell
docker compose up -d
```

This will start the database and the pgadmin (optional) containers in the background.

You can run the backend and the frontend in parallel:

``` shell
pnpm -r start
```

## Development

You also need to have the database running using the `docker compose up -d` command.

Then run the development server for both the backend and the frontend in parallel with hot reloading:

``` shell
pnpm run --parallel dev
```

## References

- [KoaJS](https://koajs.com/)
- [pnpm](https://pnpm.io/)
- [React](https://react.dev/)
- [Vite](https://vite.dev/)
- [docker](https://docs.docker.com/reference/)
- [docker compose](https://docs.docker.com/compose/)

# Functional Programming with JavaScript

[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)

This is an easy, basic and raw (minimum styles attached) example of **HOW to** implement `Immutability` in the client's side.

## Installation

```shell
npm install
```

## Setting NASA

Before running the server, create a `.env` (at the root level of your project) including the API key generated here: https://api.nasa.gov/

Your file should look like:
(don't worry, Vd8hasdga6dq3wadhdeygd333 is a dummy key)

```
API_KEY=Vd8hasdga6dq3wadhdeygd333
```

## Running development server

```shell
npm run watch
```

## Running production server

```shell
npm start
```

## Notes
1. We are using `node-fetch` to keep consistency between "fetching" in the client and server side. If you want to see other ways of making HTTP requests in Node, [check the attached material](./extra-materials/node-http-requests.md)
1. `dotenv` will load all the environment variables declared in `.env` into `process.env`, so you will be able to access them through: `process.env.YOUR_VARIABLE`
1. The project uses `bootstrap` to provide minimum styling (mostly grid and mobile friendly) 
1. `immutable-js` helps us to keep our data store immutable. More information: [immutable-js](https://immutable-js.github.io/immutable-js/)

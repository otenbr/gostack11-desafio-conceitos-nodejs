<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/otenbr/gostack11-desafio-conceitos-nodejs?color=%2304D361">

  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/otenbr/gostack11-desafio-conceitos-nodejs?color=%2304D361">

  <img alt="Made by José Antonio" src="https://img.shields.io/badge/made%20by-José%20Antonio-%2304D361">

  <img alt="GitHub" src="https://img.shields.io/github/license/otenbr/gostack11-desafio-conceitos-nodejs?color=%2304D361">

</p>

# GoStack 11: Desafio Conceitos Node.js

Segundo desafio do bootcamp GoStack 11: Conceitos Node.js

_Second challenge of the GoStack 11 bootcamp: Node.js Concepts_

## Getting Started

### Prerequisites

-   Node.js
-   Yarn (_optional_)

### Install

Clone the repository to your machine.

```sh
git clone https://github.com/otenbr/gostack11-desafio-conceitos-nodejs.git
```

Change to solution directory

```sh
$ cd gostack11-desafio-conceitos-nodejs
```

Run the command `npm` or `yarn`.

```sh
$ yarn
yarn install v1.22.4
[1/4] Resolving packages...
[2/4] Fetching packages...
info fsevents@2.1.2: The platform "linux" is incompatible with this module.
info "fsevents@2.1.2" is an optional dependency and failed compatibility check. Excluding it from installation.
[3/4] Linking dependencies...
[4/4] Building fresh packages...
Done in 3.14s.
```

### Run

Run the command `npm run dev` or `yarn dev`.

```sh
$ yarn dev
yarn run v1.22.4
$ nodemon
[nodemon] 2.0.2
[nodemon] to restart at any time, enter `rs`
[nodemon] watching dir(s): *.*
[nodemon] watching extensions: js,mjs,json
[nodemon] starting `node src/server.js`
Server started on port http://localhost:3333

```

### Test

To execute the unit tests, run the command `npm run test` or `yarn test`.

```sh
$ yarn test
yarn run v1.22.4
$ jest
 PASS  src/__tests__/likes.spec.js
 PASS  src/__tests__/repositories.spec.js

Test Suites: 2 passed, 2 total
Tests:       9 passed, 9 total
Snapshots:   0 total
Time:        1.645s
Ran all test suites.
Done in 3.35s.
```

## Credits

This software uses the following open source packages:

-   [Node.js](https://nodejs.org/)
-   [express](https://expressjs.com/)
-   [cors](https://github.com/expressjs/cors)
-   [uuidv4](https://github.com/thenativeweb/uuidv4)
-   [nodemon](https://nodemon.io/)
-   [jest](https://jestjs.io/)
-   [supertest](https://github.com/visionmedia/supertest)

## License

[MIT](LICENSE.md)

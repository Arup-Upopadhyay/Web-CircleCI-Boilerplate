# Web boilerplate:

[![NPM version][npm-image]][npm-url] [![License: MIT][mit-badge]][mit-link] [![CircleCI][circleci-part-one]][circleci-part-two]

## Features

Boilerplate for Dockerised, React WebApp coupled with CircleCI loadbalanced with nginx.

- Repo supports only React , Express in a Mono-repo setup based on Lerna + Yarn workspace environment.
- Repo supports building docker images of WebApps and Nginx, and orchestration with docker-compose
- Rest is all ✨Magic ✨

## Installation

Application Setup requires [Node.js](https://nodejs.org/) v16+ to run.

Install the dependencies and devDependencies and start the server.

```sh
yarn global add lerna
git clone https://github.com/Arup-Upopadhyay/express-react-fullstack.git
cd express-react-fullstack
lerna bootstrap
```

**For generating web build**:

```sh
lerna run build
```

**For starting the application**:

```sh
lerna run start
```

**For building docker images**:

```sh
lerna run docker-build
```

**For running App using docker-compose**:

```sh
docker-compose up
```

## License

MIT

**Maintained by the [Arup Upopadhyay]**

[//]: # "These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax"
[arup upopadhyay]: https://www.linkedin.com/in/arupupopadhyay/
[npm-url]: https://npmjs.org/package/eslint-plugin-react
[npm-image]: https://img.shields.io/npm/v/eslint-plugin-react.svg
[circleci-part-one]: https://circleci.com/gh/Arup-Upopadhyay/Web-CircleCI-Boilerplate/tree/main.svg?style=svg
[circleci-part-two]: https://circleci.com/gh/Arup-Upopadhyay/Web-CircleCI-Boilerplate/tree/main
[mit-badge]: https://img.shields.io/badge/License-MIT-green.svg
[mit-link]: https://opensource.org/licenses/MIT

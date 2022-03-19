# Web boilerplate:

[![NPM version][npm-image]][npm-url] [![License: MIT][mit-badge]][mit-link] [![CircleCI][circleci-part-one]][circleci-part-two]

## Objective

Created a Boilerplate for React based WebApp coupled with CircleCI, so that I dont have to re-invent the wheel again and again.

- Repo supports only React , Express in a Mono-repo setup based on Lerna + Yarn workspace environment.
- Rest is all ✨Magic ✨

## Features

- React + Redux boiler plate code in a Monorepo env.
- Maintained by the [Arup Upopadhyay]

## Installation

Express-React-Fullstack requires [Node.js](https://nodejs.org/) v16+ to run.

Install the dependencies and devDependencies and start the server.

```sh
yarn global add lerna
git clone https://github.com/Arup-Upopadhyay/express-react-fullstack.git
cd express-react-fullstack
lerna bootstrap
```

For development environments...open two terminal
first terminal:

```sh
lerna run build --stream
```

second terminal:

```sh
lerna run start --stream
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # "These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax"
[arup upopadhyay]: https://www.linkedin.com/in/arupupopadhyay/
[npm-url]: https://npmjs.org/package/eslint-plugin-react
[npm-image]: https://img.shields.io/npm/v/eslint-plugin-react.svg
[circleci-part-one]: https://circleci.com/gh/Arup-Upopadhyay/Web-CircleCI-Boilerplate/tree/main.svg?style=svg
[circleci-part-two]: https://circleci.com/gh/Arup-Upopadhyay/Web-CircleCI-Boilerplate/tree/main
[mit-badge]: https://img.shields.io/badge/License-MIT-green.svg
[mit-link]: https://opensource.org/licenses/MIT

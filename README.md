# dbcli

[![build status](https://img.shields.io/travis/com/shadowgate15/dbcli.svg)](https://travis-ci.com/shadowgate15/dbcli)
[![code coverage](https://img.shields.io/codecov/c/github/shadowgate15/dbcli.svg)](https://codecov.io/gh/shadowgate15/dbcli)
[![code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/sindresorhus/xo)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![made with lass](https://img.shields.io/badge/made_with-lass-95CC28.svg)](https://lass.js.org)
[![license](https://img.shields.io/github/license/shadowgate15/dbcli.svg)](LICENSE)
[![npm downloads](https://img.shields.io/npm/dt/dbcli.svg)](https://npm.im/dbcli)

> A command line interface for interacting with databases.


## Table of Contents

* [Install](#install)
* [Usage](#usage)
* [Contributors](#contributors)
* [License](#license)


## Install

[npm][]:

```sh
npm install dbcli
```

[yarn][]:

```sh
yarn add dbcli
```


## Usage

```js
const Dbcli = require('dbcli');

const dbcli = new Dbcli();

console.log(dbcli.renderName());
// script
```


## Contributors

| Name              | Website                           |
| ----------------- | --------------------------------- |
| **Taylor Schley** | <https://github.com/shadowgate15> |


## License

[MIT](LICENSE) © [Taylor Schley](https://github.com/shadowgate15)


##

[npm]: https://www.npmjs.com/

[yarn]: https://yarnpkg.com/

This repository has been migrated. For ongoing updates, please see https://github.com/thinkjs/thinkjs/tree/master/packages/think-router-rest.

# think-router-rest

[![npm](https://img.shields.io/npm/v/think-router-rest.svg?style=flat-square)]()
[![Travis](https://img.shields.io/travis/thinkjs/think-router-rest.svg?style=flat-square)]()
[![Coveralls](https://img.shields.io/coveralls/thinkjs/think-router-rest/master.svg?style=flat-square)]()
[![David](https://img.shields.io/david/thinkjs/think-router-rest.svg?style=flat-square)]()

Let think-router recognize REST router easily without custom router for ThinkJS 3.x.

## Installation

```sh
npm install think-router-rest --save
```

## How To Use

append this middleware in `src/config/middleware.js`:

```js
const router = require('think-router');
const routerREST = require('think-router-rest');

module.exports = [
  {handle: router, options: {}},
  {handle: routerREST, options: {}}
];
```

## Contributing

Contributions welcome!

## License

[MIT](https://github.com/thinkjs/think-router-rest/blob/master/LICENSE)



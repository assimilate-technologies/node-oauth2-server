
# oauth2-express

[![npm Version][npm-image]][npm-url]
[![npm Downloads][downloads-image]][downloads-url]
[![MIT Licensed][license-image]][license-url]

Module for implementing an OAuth2 server in [Node.js](https://nodejs.org).

## Installation

```bash
npm install oauth2-express
```

## Features

- Supports `authorization_code`, `client_credentials`, `refresh_token` and `password` grant, as well as *extension grants*, with scopes.
- Can be used with *promises*, *Node-style callbacks*, *ES6 generators* and *async*/*await* (using [Babel](https://babeljs.io)).
- Fully [RFC 6749](https://tools.ietf.org/html/rfc6749.html) and [RFC 6750](https://tools.ietf.org/html/rfc6750.html) compliant.
- Implicitly supports any form of storage, e.g. *PostgreSQL*, *MySQL*, *MongoDB*, *Redis*, etc.

## Documentation

[Documentation](https://oauth2-express.readthedocs.io) is hosted on Read the Docs.

[npm-image]: https://img.shields.io/npm/v/oauth2-express.svg
[npm-url]: https://npmjs.org/package/oauth2-express
[downloads-image]: https://img.shields.io/npm/dm/oauth2-express.svg
[downloads-url]: https://npmjs.org/package/oauth2-express
[license-image]: https://img.shields.io/badge/license-MIT-blue.svg
[license-url]: https://raw.githubusercontent.com/zilurrane/oauth2-express/master/LICENSE

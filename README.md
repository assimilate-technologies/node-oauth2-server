
# oauth2-express

[![npm Version][npm-image]][npm-url]
[![npm Downloads][downloads-image]][downloads-url]
[![MIT Licensed][license-image]][license-url]

Tweaked Module for implementing an OAuth2 server in [Node.js](https://nodejs.org).

## Installation

```bash
npm install oauth2-express
```

## Features

- Supports `authorization_code`, `client_credentials`, `refresh_token` and `password` grant, as well as *extension grants*, with scopes.
- Can be used with *promises*, *Node-style callbacks*, *ES6 generators* and *async*/*await* (using [Babel](https://babeljs.io)).
- Fully [RFC 6749](https://tools.ietf.org/html/rfc6749.html) and [RFC 6750](https://tools.ietf.org/html/rfc6750.html) compliant.
- Implicitly supports any form of storage, e.g. *PostgreSQL*, *MySQL*, *MongoDB*, *Redis*, etc.
- Along with all OAuth functionalities, we have tweaked this package to detect client based on the user's username and redirect the user to the client-specific portal. This helped us to have a single login screen and client-specific portals. User can enable this mode using ```authWithoutClientCredentials``` flag.
- When this flag is set to true, then the user will not be needed to specify client id and client secrete with limitation is that an email id can be used only once for all clients in system.
- By-default this flag is set to false and default oauth implementation will work as per standard.


[npm-image]: https://img.shields.io/npm/v/oauth2-express.svg
[npm-url]: https://npmjs.org/package/oauth2-express
[downloads-image]: https://img.shields.io/npm/dm/oauth2-express.svg
[downloads-url]: https://npmjs.org/package/oauth2-express
[license-image]: https://img.shields.io/badge/license-MIT-blue.svg
[license-url]: https://raw.githubusercontent.com/zilurrane/oauth2-express/master/LICENSE

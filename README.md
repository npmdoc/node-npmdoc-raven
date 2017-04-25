# npmdoc-raven

#### basic api documentation for  [raven (v1.2.1)](https://github.com/getsentry/raven-node#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-raven.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-raven) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-raven.svg)](https://travis-ci.org/npmdoc/node-npmdoc-raven)

#### A standalone (Node.js) client for Sentry

[![NPM](https://nodei.co/npm/raven.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/raven)

- [https://npmdoc.github.io/node-npmdoc-raven/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-raven/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-raven/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-raven/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-raven/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-raven/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Robenolt"
    },
    "bin": {
        "raven": "./bin/raven"
    },
    "bugs": {
        "url": "https://github.com/getsentry/raven-node/issues"
    },
    "contributors": [
        {
            "name": "https://github.com/mattrobenolt/raven-node/graphs/contributors"
        }
    ],
    "dependencies": {
        "cookie": "0.3.1",
        "json-stringify-safe": "5.0.1",
        "lsmod": "1.0.0",
        "stack-trace": "0.0.9",
        "uuid": "3.0.0"
    },
    "description": "A standalone (Node.js) client for Sentry",
    "devDependencies": {
        "coffee-script": "~1.10.0",
        "connect": "*",
        "eslint": "2.13.1",
        "express": "*",
        "glob": "~3.1.13",
        "istanbul": "^0.4.3",
        "koa": "*",
        "mocha": "~3.1.2",
        "nock": "~9.0.0",
        "should": "11.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "949c134db028a190b7bbf8f790aae541b7c020bd",
        "tarball": "https://registry.npmjs.org/raven/-/raven-1.2.1.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "394ca230cae8bbb887095f151a657bdda9b43fd4",
    "homepage": "https://github.com/getsentry/raven-node#readme",
    "keywords": [
        "raven",
        "sentry",
        "python",
        "errors",
        "debugging",
        "exceptions"
    ],
    "license": "BSD-2-Clause",
    "main": "index",
    "maintainers": [
        {
            "name": "benvinegar"
        },
        {
            "name": "lewisjellis"
        },
        {
            "name": "mattrobenolt"
        },
        {
            "name": "zeeg"
        }
    ],
    "name": "raven",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/getsentry/raven-node.git"
    },
    "scripts": {
        "lint": "node_modules/eslint/bin/eslint.js .",
        "pretest": "npm install && npm run lint",
        "test": "NODE_ENV=test istanbul cover _mocha  -- --reporter dot && NODE_ENV=test node_modules/coffee-script/bin/coffee ./test/run.coffee",
        "test-full": "npm run test && cd test/instrumentation && ./run.sh",
        "test-mocha": "NODE_ENV=test mocha"
    },
    "version": "1.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

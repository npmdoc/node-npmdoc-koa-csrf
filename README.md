# npmdoc-koa-csrf

#### basic api documentation for  [koa-csrf (v3.0.5)](https://github.com/koajs/csrf)  [![npm package](https://img.shields.io/npm/v/npmdoc-koa-csrf.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-koa-csrf) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-koa-csrf.svg)](https://travis-ci.org/npmdoc/node-npmdoc-koa-csrf)

#### CSRF tokens for koa

[![NPM](https://nodei.co/npm/koa-csrf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-csrf)

- [https://npmdoc.github.io/node-npmdoc-koa-csrf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-csrf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-csrf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-csrf/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-koa-csrf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-koa-csrf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/koajs/csrf/issues"
    },
    "contributors": [
        {
            "name": "Nick Baugh"
        }
    ],
    "dependencies": {
        "csrf": "^3.0.3"
    },
    "description": "CSRF tokens for koa",
    "devDependencies": {
        "babel-cli": "^6.14.0",
        "babel-preset-crocodile": "^1.0.0",
        "chai": "^3.5.0",
        "codecov": "^1.0.1",
        "dirty-chai": "^1.2.2",
        "eslint": "^3.17.1",
        "eslint-config-crocodile": "^1.0.0",
        "istanbul": "^1.1.0-alpha.1",
        "koa": "^2.0.0-alpha.3",
        "koa-bodyparser": "^3.2.0",
        "koa-convert": "^1.2.0",
        "koa-generic-session": "^1.11.3",
        "mocha": "^3.0.2",
        "supertest": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "df876b010ac1454e93dc1a4f3ab24a8e644b65e7",
        "tarball": "https://registry.npmjs.org/koa-csrf/-/koa-csrf-3.0.5.tgz"
    },
    "engines": {
        "node": ">= 6.x"
    },
    "gitHead": "19628eb24da46d810b084f2108f3e58389834d5a",
    "homepage": "https://github.com/koajs/csrf",
    "keywords": [
        "cross",
        "csrf",
        "forgery",
        "koa",
        "koa2",
        "koa@2",
        "koa@next",
        "koanext",
        "next",
        "request",
        "security",
        "site"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "aheckmann"
        },
        {
            "name": "coderhaoxin"
        },
        {
            "name": "dead-horse"
        },
        {
            "name": "dead_horse"
        },
        {
            "name": "eivifj"
        },
        {
            "name": "fengmk2"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "juliangruber"
        },
        {
            "name": "niftylettuce"
        },
        {
            "name": "popomore"
        },
        {
            "name": "stephenmathieson"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "koa-csrf",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/koajs/csrf.git"
    },
    "scripts": {
        "analyze-coverage": "babel-node node_modules/.bin/istanbul cover node_modules/.bin/_mocha",
        "check-coverage": "babel-node node_modules/.bin/istanbul check-coverage",
        "compile": "rm -rf lib/ && babel -d lib src",
        "coverage": "rm -rf coverage/ && npm run analyze-coverage && npm run check-coverage && node_modules/.bin/codecov",
        "lint": "eslint .",
        "mocha": "NODE_ENV=test node_modules/.bin/_mocha",
        "prepublish": "npm run test",
        "test": "npm run lint && npm run compile && npm run coverage"
    },
    "version": "3.0.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

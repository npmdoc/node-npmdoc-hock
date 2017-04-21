# npmdoc-hock

#### api documentation for  hock (v1.3.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-hock.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hock) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hock.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hock)

#### A mocking server for HTTP requests

[![NPM](https://nodei.co/npm/hock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hock)

- [https://npmdoc.github.io/node-npmdoc-hock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hock/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hock",
    "description": "A mocking server for HTTP requests",
    "version": "1.3.2",
    "author": "Maciej Małecki <me@mmalecki.com>",
    "contributors": [
        {
            "name": "Ken Perkins"
        }
    ],
    "repository": {
        "type": "git",
        "url": "http://github.com/mmalecki/hock.git"
    },
    "keywords": [
        "mock",
        "http",
        "test"
    ],
    "devDependencies": {
        "mocha": "^2.1.0",
        "request": "2.20.x",
        "should": "^5.0.1",
        "should-http": "0.0.2"
    },
    "main": "./lib/hock",
    "scripts": {
        "test": "make test"
    },
    "engines": {
        "node": ">=0.8.x"
    },
    "dependencies": {
        "deep-equal": "0.2.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmdoc-negotiator

#### api documentation for  negotiator (v0.6.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-negotiator.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-negotiator) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-negotiator.svg)](https://travis-ci.org/npmdoc/node-npmdoc-negotiator)

#### HTTP content negotiation

[![NPM](https://nodei.co/npm/negotiator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/negotiator)

- [https://npmdoc.github.io/node-npmdoc-negotiator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-negotiator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-negotiator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-negotiator/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-negotiator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-negotiator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "negotiator",
    "description": "HTTP content negotiation",
    "version": "0.6.1",
    "contributors": [
        "Douglas Christopher Wilson <doug@somethingdoug.com>",
        "Federico Romero <federico.romero@outboxlabs.com>",
        "Isaac Z. Schlueter <i@izs.me> (http://blog.izs.me/)"
    ],
    "license": "MIT",
    "keywords": [
        "http",
        "content negotiation",
        "accept",
        "accept-language",
        "accept-encoding",
        "accept-charset"
    ],
    "repository": "jshttp/negotiator",
    "devDependencies": {
        "istanbul": "0.4.3",
        "mocha": "~1.21.5"
    },
    "files": [
        "lib/",
        "HISTORY.md",
        "LICENSE",
        "index.js",
        "README.md"
    ],
    "engines": {
        "node": ">= 0.6"
    },
    "scripts": {
        "test": "mocha --reporter spec --check-leaks --bail test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

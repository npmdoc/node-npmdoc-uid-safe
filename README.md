# npmdoc-uid-safe

#### api documentation for  [uid-safe (v2.1.4)](https://github.com/crypto-utils/uid-safe#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-uid-safe.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-uid-safe) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-uid-safe.svg)](https://travis-ci.org/npmdoc/node-npmdoc-uid-safe)

#### URL and cookie safe UIDs

[![NPM](https://nodei.co/npm/uid-safe.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/uid-safe)

- [https://npmdoc.github.io/node-npmdoc-uid-safe/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-uid-safe/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-uid-safe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-uid-safe/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-uid-safe/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-uid-safe/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/crypto-utils/uid-safe/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {
        "random-bytes": "~1.0.0"
    },
    "description": "URL and cookie safe UIDs",
    "devDependencies": {
        "bluebird": "3.4.7",
        "eslint": "3.16.1",
        "eslint-config-standard": "7.0.0",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "3ad6f38368c6d4c8c75ec17623fb79aa1d071d81",
        "tarball": "https://registry.npmjs.org/uid-safe/-/uid-safe-2.1.4.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "gitHead": "4964cfbf8aa89e1988e30f26e2ecaa4ba239222d",
    "homepage": "https://github.com/crypto-utils/uid-safe#readme",
    "keywords": [
        "random",
        "generator",
        "uid",
        "safe"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "fishrock123"
        },
        {
            "name": "jongleberry"
        }
    ],
    "name": "uid-safe",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/crypto-utils/uid-safe.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --trace-deprecation --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --trace-deprecation --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --trace-deprecation --reporter spec --check-leaks test/"
    },
    "version": "2.1.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

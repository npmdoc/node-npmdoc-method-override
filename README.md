# npmdoc-method-override

#### api documentation for  [method-override (v2.3.8)](https://github.com/expressjs/method-override#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-method-override.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-method-override) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-method-override.svg)](https://travis-ci.org/npmdoc/node-npmdoc-method-override)

#### Override HTTP verbs

[![NPM](https://nodei.co/npm/method-override.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/method-override)

- [https://npmdoc.github.io/node-npmdoc-method-override/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-method-override/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-method-override/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-method-override/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-method-override/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-method-override/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/expressjs/method-override/issues"
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
        "debug": "2.6.3",
        "methods": "~1.1.2",
        "parseurl": "~1.3.1",
        "vary": "~1.1.0"
    },
    "description": "Override HTTP verbs",
    "devDependencies": {
        "eslint": "3.18.0",
        "eslint-config-standard": "7.1.0",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "178234bf4bab869f89df9444b06fc6147b44828c",
        "tarball": "https://registry.npmjs.org/method-override/-/method-override-2.3.8.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "96422fdbc34d01d4d68624823aa71de345cea9da",
    "homepage": "https://github.com/expressjs/method-override#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "defunctzombie"
        },
        {
            "name": "dougwilson"
        },
        {
            "name": "fishrock123"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "mscdex"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "method-override",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/method-override.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --check-leaks --reporter spec --bail test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --check-leaks --reporter dot test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --check-leaks --reporter spec test/"
    },
    "version": "2.3.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

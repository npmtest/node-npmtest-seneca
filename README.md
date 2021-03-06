# npmtest-seneca

#### basic test coverage for  [seneca (v3.3.0)](http://senecajs.org)  [![npm package](https://img.shields.io/npm/v/npmtest-seneca.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-seneca) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-seneca.svg)](https://travis-ci.org/npmtest/node-npmtest-seneca)

#### A Microservices Framework for Node.js

[![NPM](https://nodei.co/npm/seneca.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/seneca)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-seneca/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-seneca/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-seneca/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-seneca/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-seneca/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-seneca/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-seneca/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-seneca/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-seneca/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-seneca/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-seneca/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-seneca/build/test-report.html](https://npmtest.github.io/node-npmtest-seneca/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-seneca/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-seneca/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-seneca/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-seneca/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-seneca/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-seneca/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-seneca/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-seneca/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Richard Rodger",
        "url": "http://richardrodger.com/"
    },
    "bugs": {
        "url": "https://github.com/senecajs/seneca/issues"
    },
    "contributors": [
        {
            "name": "Adrien Becchis",
            "url": "https://github.com/AdrieanKhisbe"
        },
        {
            "name": "Alexandru Mircea",
            "url": "https://github.com/mirceaalexandru"
        },
        {
            "name": "Adrian Rossouw",
            "url": "http://daemon.co.za"
        },
        {
            "name": "Colin Ihrig",
            "url": "https://github.com/cjihrig"
        },
        {
            "name": "Cristian Ianto",
            "url": "https://github.com/iantocristian"
        },
        {
            "name": "Cristian Kiss",
            "url": "https://github.com/ckiss"
        },
        {
            "name": "David Mark Clements",
            "url": "https://github.com/davidmarkclements"
        },
        {
            "name": "Dean McDonnell",
            "url": "https://github.com/mcdonnelldean"
        },
        {
            "name": "Dominic Tarr",
            "url": "https://github.com/dominictarr"
        },
        {
            "name": "Dustin Deus",
            "url": "https://github.com/StarpTech"
        },
        {
            "name": "Glen Keane",
            "url": "https://github.com/thekemkid"
        },
        {
            "name": "Gege Pincin",
            "url": "https://github.com/Georgette"
        },
        {
            "name": "Jake Pruitt",
            "url": "https://github.com/jakepruitt"
        },
        {
            "name": "Maciej Małecki",
            "url": "http://mmalecki.com"
        },
        {
            "name": "Matteo Collina",
            "url": "https://github.com/mcollina"
        },
        {
            "name": "Marian Radulescu",
            "url": "https://github.com/marianr"
        },
        {
            "name": "Marius Ursache",
            "url": "https://github.com/bamse16"
        },
        {
            "name": "Martin Betak",
            "url": "https://github.com/matobet"
        },
        {
            "name": "Maxence Dalmais",
            "url": "https://github.com/maxired"
        },
        {
            "name": "Mihai Dima",
            "url": "https://github.com/mihaidma"
        },
        {
            "name": "Naomi Feehan",
            "url": "https://github.com/naomifeehan"
        },
        {
            "name": "Paolo Chiodi",
            "url": "https://github.com/paolochiodi"
        },
        {
            "name": "Peter Elger",
            "url": "https://github.com/pelger"
        },
        {
            "name": "Reto Inderbitzin",
            "url": "https://github.com/indr"
        },
        {
            "name": "Reid Rankin",
            "url": "https://github.com/reidrankin"
        },
        {
            "name": "Tane Piper",
            "url": "https://github.com/tanepiper"
        },
        {
            "name": "Wyatt Preul",
            "url": "https://github.com/geek"
        },
        {
            "name": "Vald Houbiev",
            "url": "https://github.com/vladgolubev"
        },
        {
            "name": "Vito Tardia",
            "url": "https://github.com/vtardia"
        }
    ],
    "dependencies": {
        "archy": "1.0.0",
        "eraro": "0.4.1",
        "gate-executor": "1.1.1",
        "gex": "0.2.2",
        "json-stringify-safe": "5.0.1",
        "jsonic": "0.2.2",
        "lodash": "4.15.0",
        "lru-cache": "4.0.1",
        "minimist": "1.2.0",
        "nid": "0.3.2",
        "norma": "0.3.0",
        "ordu": "0.1.1",
        "patrun": "0.5.1",
        "rolling-stats": "0.1.1",
        "semver": "5.3.0",
        "seneca-log-filter": "0.1.0",
        "seneca-transport": "2.1.0",
        "use-plugin": "0.3.2"
    },
    "description": "A Microservices Framework for Node.js",
    "devDependencies": {
        "async": "2.0.x",
        "bench": "0.3.x",
        "body-parser": "1.15.x",
        "code": "3.0.x",
        "connect": "3.4.x",
        "connect-query": "0.2.x",
        "coveralls": "2.11.x",
        "docco": "0.7.x",
        "eslint-config-seneca": "3.x.x",
        "eslint-plugin-hapi": "4.x.x",
        "eslint-plugin-standard": "2.x.x",
        "lab": "11.0.x",
        "seneca-entity": "1.3.x",
        "seneca-error-test": "0.2.x"
    },
    "directories": {},
    "dist": {
        "shasum": "b8c07575fa074284e2407d702ddf35c30fa199bc",
        "tarball": "https://registry.npmjs.org/seneca/-/seneca-3.3.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "files": [
        "LICENSE",
        "README.md",
        "CHANGES.md",
        "lib",
        "seneca.js"
    ],
    "gitHead": "38595f6e4909c1ac71f073a49a772a177a1af690",
    "homepage": "http://senecajs.org",
    "keywords": [
        "micro",
        "service",
        "microservice",
        "micro-service",
        "microservices",
        "micro-services",
        "services",
        "micro services",
        "micro service",
        "framework",
        "minimum",
        "viable",
        "product",
        "toolkit",
        "startup"
    ],
    "license": "MIT",
    "main": "seneca.js",
    "maintainers": [
        {
            "name": "matteo.collina"
        },
        {
            "name": "mcdonnelldean"
        },
        {
            "name": "naomifeehanmoran"
        },
        {
            "name": "rjrodger"
        },
        {
            "name": "wyatt"
        }
    ],
    "name": "seneca",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/senecajs/seneca.git"
    },
    "scripts": {
        "annotate": "docco seneca.js lib/*.js -o docs/annotated",
        "coverage": "lab -v -P test -L -t 80 -r html > docs/coverage.html",
        "coveralls": "lab -s -P test -r lcov | coveralls",
        "smoke": "node test/stubs/launch.js",
        "test": "lab -v -P test -L -t 80"
    },
    "version": "3.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

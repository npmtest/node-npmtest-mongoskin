# test coverage for  [mongoskin (v2.1.0)](https://github.com/kissjs/node-mongoskin)  [![npm package](https://img.shields.io/npm/v/npmtest-mongoskin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mongoskin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mongoskin.svg)](https://travis-ci.org/npmtest/node-npmtest-mongoskin)
#### The future layer above node-mongodb-native

[![NPM](https://nodei.co/npm/mongoskin.png?downloads=true)](https://www.npmjs.com/package/mongoskin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mongoskin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongoskin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mongoskin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mongoskin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mongoskin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mongoskin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mongoskin/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongoskin/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-mongoskin/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-mongoskin/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-mongoskin%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mongoskin/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongoskin/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-mongoskin%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongoskin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mongoskin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mongoskin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gui Lin",
        "email": "guileen@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/kissjs/node-mongoskin/issues"
    },
    "contributors": [
        {
            "name": "Gui Lin",
            "email": "guileen@gmail.com",
            "url": "https://github.com/guileen"
        },
        {
            "name": "François de Metz",
            "email": "francois@2metz.fr",
            "url": "https://github.com/francois2metz"
        },
        {
            "name": "fengmk2",
            "email": "fengmk2@gmail.com",
            "url": "http://fengmk2.github.com"
        },
        {
            "name": "Quang Van",
            "email": "quangvvv@gmail.com",
            "url": "https://github.com/quangv"
        },
        {
            "name": "Matt Perpick",
            "email": "clutchski@gmail.com",
            "url": "https://github.com/clutchski"
        },
        {
            "name": "humanchimp",
            "email": "morphcham@gmail.com",
            "url": "https://github.com/humanchimp"
        },
        {
            "name": "Joe Faber",
            "email": "joe.faber@mandiant.com",
            "url": "https://github.com/jlfaber"
        },
        {
            "name": "Harvey McQueen",
            "email": "hmcqueen@gmail.com",
            "url": "https://github.com/hmcqueen"
        },
        {
            "name": "Paul Gebheim",
            "email": "pgebheim@monkeyinferno.com",
            "url": "https://github.com/paulirish"
        },
        {
            "name": "Aneil Mallavarapu",
            "email": "aneil@blipboard.com",
            "url": "https://github.com/amallavarapu"
        },
        {
            "name": "wmertens",
            "email": "Wout.Mertens@gmail.com",
            "url": "https://github.com/wmertens"
        },
        {
            "name": "Rakshit Menpara",
            "email": "deltasquare4@gmail.com",
            "url": "https://github.com/deltasquare4"
        }
    ],
    "dependencies": {},
    "description": "The future layer above node-mongodb-native",
    "devDependencies": {
        "coveralls": "~2.10.0",
        "istanbul": "0.3.17",
        "mocha": "~1.17.1",
        "mocha-lcov-reporter": "0.0.1",
        "mongodb": "^2.0",
        "should": "~3.1.2",
        "travis-cov": "~0.2.5"
    },
    "directories": {
        "example": "./examples",
        "lib": "./lib/mongoskin"
    },
    "dist": {
        "shasum": "1fda6814b21de53e36b4396f6126c979c5e9ee60",
        "tarball": "https://registry.npmjs.org/mongoskin/-/mongoskin-2.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "gitHead": "60d677e287c8841fd5aa028b4a5ed6e4a6108467",
    "homepage": "https://github.com/kissjs/node-mongoskin",
    "keywords": [
        "mongodb",
        "database",
        "nosql"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "guileen",
            "email": "guileen@gmail.com"
        },
        {
            "name": "fengmk2",
            "email": "fengmk2@gmail.com"
        },
        {
            "name": "vkarpov15",
            "email": "val@karpov.io"
        }
    ],
    "name": "mongoskin",
    "optionalDependencies": {},
    "peerDependencies": {
        "mongodb": "^2.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/kissjs/node-mongoskin.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha",
        "test": "mocha"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

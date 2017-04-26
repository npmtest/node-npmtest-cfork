# npmtest-cfork

#### basic test coverage for  [cfork (v1.6.0)](https://github.com/node-modules/cfork)  [![npm package](https://img.shields.io/npm/v/npmtest-cfork.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cfork) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cfork.svg)](https://travis-ci.org/npmtest/node-npmtest-cfork)

#### cluster fork and restart easy way

[![NPM](https://nodei.co/npm/cfork.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cfork)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cfork/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cfork/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cfork/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cfork/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cfork/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-cfork/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-cfork/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cfork/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cfork/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cfork/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cfork/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cfork/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cfork/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cfork/build/test-report.html](https://npmtest.github.io/node-npmtest-cfork/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cfork/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cfork/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cfork/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cfork/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cfork/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cfork/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cfork/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cfork/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "fengmk2",
        "url": "http://fengmk2.com"
    },
    "bugs": {
        "url": "https://github.com/node-modules/cfork/issues"
    },
    "contributors": [
        {
            "name": "fengmk2",
            "url": "https://github.com/fengmk2"
        },
        {
            "name": "JacksonTian",
            "url": "https://github.com/JacksonTian"
        },
        {
            "name": "dead-horse",
            "url": "https://github.com/dead-horse"
        },
        {
            "name": "coderhaoxin",
            "url": "https://github.com/coderhaoxin"
        },
        {
            "name": "luckydrq",
            "url": "https://github.com/luckydrq"
        },
        {
            "name": "hustxiaoc",
            "url": "https://github.com/hustxiaoc"
        },
        {
            "name": "Flandre Scarlet",
            "url": "https://github.com/XadillaX"
        }
    ],
    "dependencies": {},
    "description": "cluster fork and restart easy way",
    "devDependencies": {
        "childprocess": "1",
        "contributors": "*",
        "eslint": "3.9.0",
        "graceful": "1",
        "istanbul": "^0.4.0",
        "mocha": "2",
        "pedding": "1",
        "should": "11.1.1",
        "urllib": "2"
    },
    "directories": {},
    "dist": {
        "shasum": "24fba60015d4ad9c648040247a85401bb664c390",
        "tarball": "https://registry.npmjs.org/cfork/-/cfork-1.6.0.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "6696f6089e155d8639771099f7c59a2d5b2c8ba2",
    "homepage": "https://github.com/node-modules/cfork",
    "keywords": [
        "cluster",
        "cluster-fork",
        "cfork",
        "restart"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fengmk2"
        }
    ],
    "name": "cfork",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/node-modules/cfork.git",
        "web": "https://github.com/node-modules/cfork"
    },
    "scripts": {
        "ci": "mocha -t 15000 test/*.test.js",
        "clean": "rm -rf coverage",
        "cover": "node --harmony node_modules/.bin/istanbul cover --include-all-sources --report none --print none node_modules/.bin/_mocha -- -t 15000 test/*.test.js",
        "lint": "eslint index.js test",
        "test": "npm run clean && npm run lint && npm run cover && istanbul report json lcov html text"
    },
    "version": "1.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

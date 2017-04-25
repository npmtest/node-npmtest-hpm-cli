# npmtest-hpm-cli

#### basic test coverage for  [hpm-cli (v2.0.1)](https://github.com/zeit/hpm#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-hpm-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hpm-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hpm-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-hpm-cli)

#### A plugin manager for Hyper.app

[![NPM](https://nodei.co/npm/hpm-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hpm-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hpm-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hpm-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hpm-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hpm-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hpm-cli/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-hpm-cli/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-hpm-cli/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hpm-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hpm-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hpm-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hpm-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hpm-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hpm-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hpm-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-hpm-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hpm-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hpm-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hpm-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hpm-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hpm-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hpm-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hpm-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hpm-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matheus Fernandes",
        "url": "http://matheus.top"
    },
    "bin": {
        "hpm": "./index.js"
    },
    "bugs": {
        "url": "https://github.com/zeit/hpm/issues"
    },
    "dependencies": {
        "args": "^2.0.0",
        "chalk": "^1.1.3",
        "columnify": "^1.5.4",
        "execa": "^0.5.0",
        "file-exists": "^2.0.0",
        "got": "^6.3.0",
        "npm-name": "^3.0.0",
        "opn": "^4.0.2",
        "ora": "^0.3.0",
        "pify": "^2.3.0",
        "recast": "^0.11.10",
        "update-notifier": "^1.0.2"
    },
    "description": "A plugin manager for Hyper.app",
    "devDependencies": {
        "ava": "^0.16.0",
        "coveralls": "^2.11.11",
        "is-ci": "^1.0.9",
        "mock-fs": "^3.11.0",
        "nyc": "^8.3.0",
        "xo": "^0.17.0"
    },
    "directories": {},
    "dist": {
        "shasum": "32073c17208dea80f19be811020bba63f3883053",
        "tarball": "https://registry.npmjs.org/hpm-cli/-/hpm-cli-2.0.1.tgz"
    },
    "engines": {
        "node": ">=6"
    },
    "files": [
        "api.js",
        "index.js"
    ],
    "gitHead": "1610fada94e68a1b1c103741743a31defa60e058",
    "homepage": "https://github.com/zeit/hpm#readme",
    "keywords": [
        "hyper.app",
        "hyperapp",
        "hyperterm",
        "package",
        "manager",
        "terminal",
        "cli",
        "🦁"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "leo"
        },
        {
            "name": "matheuss"
        }
    ],
    "name": "hpm-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeit/hpm.git"
    },
    "scripts": {
        "coverage": "nyc report --reporter=text-lcov | coveralls",
        "test": "xo && nyc ava"
    },
    "version": "2.0.1",
    "xo": {
        "space": 2,
        "semicolon": false,
        "esnext": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

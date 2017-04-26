# npmtest-tsd

#### basic test coverage for  [tsd (v0.6.5)](https://github.com/DefinitelyTyped/tsd)  [![npm package](https://img.shields.io/npm/v/npmtest-tsd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tsd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tsd.svg)](https://travis-ci.org/npmtest/node-npmtest-tsd)

#### TypeScript Definition manager for DefinitelyTyped

[![NPM](https://nodei.co/npm/tsd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tsd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tsd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tsd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tsd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tsd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tsd/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-tsd/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-tsd/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tsd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tsd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tsd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tsd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tsd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tsd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tsd/build/test-report.html](https://npmtest.github.io/node-npmtest-tsd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tsd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tsd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tsd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tsd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tsd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tsd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tsd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tsd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Bart van der Schoor",
        "url": "https://github.com/Bartvds"
    },
    "bin": {
        "tsd": "./build/cli.js"
    },
    "bugs": {
        "url": "https://github.com/DefinitelyTyped/tsd/issues"
    },
    "contributors": [
        {
            "name": "Diullei Gomes",
            "url": "https://github.com/Diullei"
        }
    ],
    "dependencies": {
        "assertion-error": "1.0.0",
        "bl": "^0.9.3",
        "bluebird": "~1.2.4",
        "chalk": "^1.0.0",
        "colors": "^1.1.0",
        "deep-freeze": "0.0.1",
        "definition-header": "~0.1.0",
        "detect-indent": "^0.2.0",
        "diff": "^1.4.0",
        "event-stream": "~3.1.5",
        "exit": "~0.1.2",
        "glob": "^4.0.6",
        "joi": "^4.7.0",
        "joi-assert": "0.0.3",
        "jsesc": "^0.5.0",
        "json-pointer": "^0.2.2",
        "lazy.js": "~0.3.2",
        "lru-cache": "~2.5.0",
        "minimatch": "^1.0.0",
        "minimist": "^1.1.0",
        "ministyle": "~0.1.3",
        "minitable": "0.0.4",
        "miniwrite": "~0.1.3",
        "mkdirp": "~0.5.0",
        "open": "~0.0.5",
        "request": "^2.45.0",
        "rimraf": "~2.2.8",
        "semver": "^4.3.1",
        "type-detect": "~0.1.2",
        "universal-analytics": "~0.3.4",
        "update-notifier": "^0.2.2",
        "uri-templates": "~0.1.5",
        "uuid": "^2.0.1",
        "verror": "~1.4.0"
    },
    "deprecated": "TSD is deprecated in favor of Typings (https://github.com/typings/typings) - see https://github.com/DefinitelyTyped/tsd/issues/269 for more information",
    "description": "TypeScript Definition manager for DefinitelyTyped",
    "devDependencies": {
        "chai": "~1.9.1",
        "chai-as-promised": "~4.1.1",
        "chai-fs": "^0.1.0",
        "chai-fuzzy": "~1.4.0",
        "chai-shallow-deep-equal": "0.0.3",
        "dir-compare": "^0.0.2",
        "grunt": "~0.4.4",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-connect": "~0.8.0",
        "grunt-contrib-copy": "^0.6.0",
        "grunt-contrib-jshint": "^0.10.0",
        "grunt-mocha-test": "^0.12.1",
        "grunt-regex-replace": "~0.2.5",
        "grunt-shell": "^1.1.1",
        "grunt-todos": "~0.3.0",
        "grunt-ts": "4.1.0",
        "grunt-ts-clean": "~0.2.0",
        "grunt-tslint": "git+https://github.com/Bartvds/grunt-tslint.git#feature/multi",
        "grunt-tv4": "~0.4.0",
        "gruntfile-gtx": "^0.3.0",
        "jshint-path-reporter": "~0.1",
        "mocha": "^1.21.4",
        "mocha-unfunk-reporter": "^0.4.0",
        "ncp": "^1.0.1",
        "package.json-schema": "~0.2.0",
        "source-map-support": "~0.2.6",
        "time-grunt": "^1.0.0",
        "tslint-path-formatter": "~0.1.1",
        "typescript": "1.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "34a0b64c1db6a70b3860fe4f5571d9d1357421ad",
        "tarball": "https://registry.npmjs.org/tsd/-/tsd-0.6.5.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "b6f7933b12a6f435deadcb042e14ab5ef8b9b638",
    "homepage": "https://github.com/DefinitelyTyped/tsd",
    "keywords": [
        "typescript",
        "definition",
        "package",
        "manager"
    ],
    "licenses": [
        {
            "type": "Apache 2.0",
            "url": "https://raw.github.com/DefinitelyTyped/tsd/master/LICENSE.txt"
        }
    ],
    "main": "./build/api.js",
    "maintainers": [
        {
            "name": "diullei"
        },
        {
            "name": "bartvds"
        },
        {
            "name": "basarat"
        },
        {
            "name": "blakeembrey"
        }
    ],
    "name": "tsd",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/DefinitelyTyped/tsd.git"
    },
    "scripts": {
        "prepublish": "grunt pre_publish",
        "test": "grunt test"
    },
    "version": "0.6.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

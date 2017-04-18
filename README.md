# npmtest-run-series

#### test coverage for  [run-series (v1.1.4)](https://github.com/feross/run-series)  [![npm package](https://img.shields.io/npm/v/npmtest-run-series.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-run-series) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-run-series.svg)](https://travis-ci.org/npmtest/node-npmtest-run-series)

#### Run an array of functions in series

[![NPM](https://nodei.co/npm/run-series.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/run-series)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-run-series/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-run-series/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-run-series/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-run-series/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-run-series/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-run-series/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-run-series/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-run-series/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-run-series/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-run-series/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-run-series/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-run-series/build/test-report.html](https://npmtest.github.io/node-npmtest-run-series/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-run-series/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-run-series/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-run-series/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-run-series/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-run-series/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-run-series/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-run-series/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-run-series/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Feross Aboukhadijeh",
        "url": "http://feross.org/"
    },
    "bugs": {
        "url": "https://github.com/feross/run-series/issues"
    },
    "dependencies": {},
    "description": "Run an array of functions in series",
    "devDependencies": {
        "standard": "^4.3.2",
        "tape": "^4.0.0",
        "zuul": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "89a73ddc5e75c9ef8ab6320c0a1600d6a41179b9",
        "tarball": "https://registry.npmjs.org/run-series/-/run-series-1.1.4.tgz"
    },
    "gitHead": "35e62fe9fdf745a952bd38163d4dee3eb9e80a54",
    "homepage": "https://github.com/feross/run-series",
    "keywords": [
        "series",
        "async",
        "function",
        "callback",
        "asynchronous",
        "run",
        "array",
        "run series"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "feross"
        }
    ],
    "name": "run-series",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/feross/run-series.git"
    },
    "scripts": {
        "test": "standard && npm run test-node && npm run test-browser",
        "test-browser": "zuul -- test/*.js",
        "test-browser-local": "zuul --local -- test/*.js",
        "test-node": "tape test/*.js"
    },
    "version": "1.1.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

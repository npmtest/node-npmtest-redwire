# npmtest-redwire

#### basic test coverage for  [redwire (v2.2.0)](https://github.com/metocean/redwire)  [![npm package](https://img.shields.io/npm/v/npmtest-redwire.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redwire) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redwire.svg)](https://travis-ci.org/npmtest/node-npmtest-redwire)

#### A dynamic, high performance, load balancing reverse proxy.

[![NPM](https://nodei.co/npm/redwire.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redwire)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redwire/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redwire/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redwire/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redwire/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redwire/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redwire/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redwire/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-redwire/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-redwire/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redwire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-redwire/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-redwire/build/test-report.html](https://npmtest.github.io/node-npmtest-redwire/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-redwire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redwire/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-redwire/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redwire/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redwire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redwire/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redwire/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redwire/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "redwire",
    "version": "2.2.0",
    "description": "A dynamic, high performance, load balancing reverse proxy.",
    "main": "index.js",
    "scripts": {
        "test": "mocha test/*.js --reporter spec"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/metocean/redwire.git"
    },
    "keywords": [
        "reverse-proxy",
        "proxy",
        "load-balancer"
    ],
    "author": "Thomas Coats",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/metocean/redwire/issues"
    },
    "homepage": "https://github.com/metocean/redwire",
    "dependencies": {
        "http-proxy": "1.11.2",
        "http2": "3.2.0"
    },
    "devDependencies": {
        "chai": "1.*",
        "mocha": "2.*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

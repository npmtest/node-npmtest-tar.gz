# npmtest-tar.gz

#### basic test coverage for  [tar.gz (v1.0.5)](https://github.com/alanhoff/node-tar.gz#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-tar.gz.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tar.gz) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tar.gz.svg)](https://travis-ci.org/npmtest/node-npmtest-tar.gz)

#### Pure javascript tarball tools for Node.js

[![NPM](https://nodei.co/npm/tar.gz.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tar.gz)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tar.gz/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tar.gz/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tar.gz/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tar.gz/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tar.gz/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tar.gz/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tar.gz/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tar.gz/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tar.gz/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tar.gz/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tar.gz/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tar.gz/build/test-report.html](https://npmtest.github.io/node-npmtest-tar.gz/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tar.gz/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tar.gz/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tar.gz/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tar.gz/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tar.gz/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tar.gz/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tar.gz/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tar.gz/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "tar.gz",
    "version": "1.0.5",
    "description": "Pure javascript tarball tools for Node.js",
    "main": "index.js",
    "scripts": {
        "test": "mocha --tdd --bail test/**/*-test.js",
        "travis": "./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- -R spec test/**/*-test.js && cat ./coverage/lcov.info | ./node_modules/.bin/coveralls && rm -rf ./coverage"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/alanhoff/node-tar.gz.git"
    },
    "keywords": [
        "compression",
        "decompression",
        "compress",
        "decompress",
        "tar",
        "tape",
        "archive",
        "tape",
        "arquive",
        "gzip",
        "gz",
        "tarball"
    ],
    "author": "Alan Hoffmeister <alanhoffmeister@gmail.com>",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/alanhoff/node-tar.gz/issues"
    },
    "bin": {
        "targz": "bin/targz"
    },
    "homepage": "https://github.com/alanhoff/node-tar.gz#readme",
    "dependencies": {
        "bluebird": "^2.9.34",
        "commander": "^2.8.1",
        "fstream": "^1.0.8",
        "mout": "^0.11.0",
        "tar": "^2.1.1"
    },
    "devDependencies": {
        "chai": "^3.2.0",
        "mocha": "^2.2.5",
        "coveralls": "^2.11.3",
        "istanbul": "^0.3.17",
        "temp": "^0.8.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

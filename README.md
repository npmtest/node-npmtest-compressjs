# npmtest-compressjs

#### basic test coverage for  compressjs (v1.0.3)  [![npm package](https://img.shields.io/npm/v/npmtest-compressjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-compressjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-compressjs.svg)](https://travis-ci.org/npmtest/node-npmtest-compressjs)

#### pure JavaScript de/compression (bzip2, etc) for node.js, volo, and the browser.

[![NPM](https://nodei.co/npm/compressjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/compressjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-compressjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-compressjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-compressjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-compressjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-compressjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-compressjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-compressjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-compressjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-compressjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-compressjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-compressjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-compressjs/build/test-report.html](https://npmtest.github.io/node-npmtest-compressjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-compressjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-compressjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-compressjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-compressjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-compressjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-compressjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-compressjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-compressjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "compressjs",
    "version": "1.0.3",
    "author": "C. Scott Ananian",
    "description": "pure JavaScript de/compression (bzip2, etc) for node.js, volo, and the browser.",
    "keywords": [
        "bzip2",
        "compression",
        "decompression"
    ],
    "main": "main",
    "repository": {
        "type": "git",
        "url": "https://github.com/cscott/compressjs.git"
    },
    "license": "GPL",
    "bin": {
        "compressjs": "./bin/compressjs"
    },
    "directories": {
        "test": "test"
    },
    "dependencies": {
        "amdefine": "~1.0.0",
        "commander": "~2.8.1"
    },
    "devDependencies": {
        "mocha": "~2.2.5"
    },
    "scripts": {
        "test": "mocha"
    },
    "amd": {},
    "volo": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

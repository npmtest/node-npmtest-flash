# npmtest-flash

#### basic test coverage for  flash (v1.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-flash.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-flash) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-flash.svg)](https://travis-ci.org/npmtest/node-npmtest-flash)

#### Simple flash messages for Express

[![NPM](https://nodei.co/npm/flash.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/flash)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-flash/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-flash/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-flash/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-flash/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-flash/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-flash/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-flash/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-flash/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-flash/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-flash/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-flash/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-flash/build/test-report.html](https://npmtest.github.io/node-npmtest-flash/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-flash/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-flash/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-flash/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-flash/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-flash/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-flash/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-flash/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-flash/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "flash",
    "description": "Simple flash messages for Express",
    "version": "1.1.0",
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com",
        "twitter": "https://twitter.com/jongleberry"
    },
    "license": "MIT",
    "repository": "expressjs/flash",
    "dependencies": {},
    "devDependencies": {
        "cookie-session": "1",
        "supertest": "0",
        "express": "4",
        "istanbul": "0",
        "mocha": "1"
    },
    "scripts": {
        "test": "mocha --reporter spec",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot"
    },
    "keywords": [
        "flash",
        "messages",
        "express"
    ],
    "files": [
        "index.js",
        "LICENSE"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

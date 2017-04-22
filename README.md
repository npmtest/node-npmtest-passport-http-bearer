# npmtest-passport-http-bearer

#### basic test coverage for  [passport-http-bearer (v1.0.1)](https://github.com/jaredhanson/passport-http-bearer#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-http-bearer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-http-bearer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-http-bearer.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-http-bearer)

#### HTTP Bearer authentication strategy for Passport.

[![NPM](https://nodei.co/npm/passport-http-bearer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-http-bearer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-http-bearer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-http-bearer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-http-bearer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-passport-http-bearer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-passport-http-bearer/build/test-report.html](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-passport-http-bearer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-http-bearer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-http-bearer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-http-bearer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-http-bearer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jared Hanson",
        "url": "http://www.jaredhanson.net/"
    },
    "bugs": {
        "url": "http://github.com/jaredhanson/passport-http-bearer/issues"
    },
    "dependencies": {
        "passport-strategy": "1.x.x"
    },
    "description": "HTTP Bearer authentication strategy for Passport.",
    "devDependencies": {
        "chai": "1.x.x",
        "chai-passport-strategy": "0.1.x",
        "mocha": "1.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "147469ea3669e2a84c6167ef99dbb77e1f0098a8",
        "tarball": "https://registry.npmjs.org/passport-http-bearer/-/passport-http-bearer-1.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "homepage": "https://github.com/jaredhanson/passport-http-bearer#readme",
    "keywords": [
        "passport",
        "auth",
        "authn",
        "authentication",
        "authz",
        "authorization",
        "http",
        "bearer",
        "token",
        "oauth"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/MIT"
        }
    ],
    "main": "./lib",
    "maintainers": [
        {
            "name": "jaredhanson"
        }
    ],
    "name": "passport-http-bearer",
    "optionalDependencies": {},
    "readmeFilename": "README.md",
    "repository": {
        "type": "git",
        "url": "git://github.com/jaredhanson/passport-http-bearer.git"
    },
    "scripts": {
        "test": "node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js"
    },
    "testling": {
        "browsers": [
            "chrome/latest"
        ],
        "harness": "mocha",
        "files": [
            "test/bootstrap/testling.js",
            "test/*.test.js"
        ]
    },
    "version": "1.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

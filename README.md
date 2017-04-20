# npmtest-enum

#### basic test coverage for  [enum (v2.4.0)](https://github.com/adrai/enum)  [![npm package](https://img.shields.io/npm/v/npmtest-enum.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-enum) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-enum.svg)](https://travis-ci.org/npmtest/node-npmtest-enum)

#### Enum is a javascript module that introduces the Enum Type. It works for node.js and in the browser.

[![NPM](https://nodei.co/npm/enum.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/enum)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-enum/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-enum/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-enum/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-enum/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-enum/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-enum/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-enum/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-enum/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-enum/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-enum/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-enum/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-enum/build/test-report.html](https://npmtest.github.io/node-npmtest-enum/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-enum/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-enum/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-enum/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-enum/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-enum/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-enum/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-enum/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-enum/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "adrai",
    "name": "enum",
    "version": "2.4.0",
    "private": false,
    "main": "index.js",
    "engines": {
        "node": ">=0.6.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dependencies": {
        "is-buffer": "^1.1.0"
    },
    "devDependencies": {
        "expect.js": ">= 0.1.2",
        "gulp": "^3.8.11",
        "gulp-babel": "^4.0.0",
        "gulp-bench": "^1.1.0",
        "gulp-browserify": "^0.5.1",
        "gulp-mocha": "^2.0.0",
        "gulp-rename": "^1.2.0",
        "gulp-rimraf": "^0.1.1",
        "gulp-shell": "^0.4.0",
        "gulp-uglify": "^1.1.0",
        "mocha": ">= 1.0.1",
        "zuul": ">= 1.0.1"
    },
    "description": "Enum is a javascript module that introduces the Enum Type. It works for node.js and in the browser.",
    "keywords": [
        "enum"
    ],
    "homepage": "https://github.com/adrai/enum",
    "repository": {
        "type": "git",
        "url": "git@github.com:adrai/enum.git"
    },
    "bugs": {
        "url": "https://github.com/adrai/enum/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.github.com/adrai/enum/master/licence"
        }
    ],
    "scripts": {
        "test": "gulp test-ci",
        "build": "gulp build",
        "prepublish": "gulp"
    },
    "testling": {
        "browsers": [
            "ie/6..latest",
            "firefox/17..latest",
            "firefox/nightly",
            "chrome/22..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ],
        "harness": "mocha",
        "files": "test/*.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

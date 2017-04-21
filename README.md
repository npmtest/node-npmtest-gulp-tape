# npmtest-gulp-tape

#### basic test coverage for  gulp-tape (v0.0.9)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-tape.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-tape) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-tape.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-tape)

#### Run Tape tests in Gulp.

[![NPM](https://nodei.co/npm/gulp-tape.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-tape)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-tape/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-tape/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-tape/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-tape/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-tape/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-tape/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-tape/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-tape/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-tape/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-tape/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-tape/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-tape/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-tape/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-tape/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-tape/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-tape/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-tape/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-tape/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-tape/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-tape/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-tape/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-tape",
    "version": "0.0.9",
    "description": "Run Tape tests in Gulp.",
    "author": "Lim Yuan Qing",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "git://github.com/yuanqing/gulp-tape.git"
    },
    "dependencies": {
        "gulp-util": "^3.0.7",
        "require-uncached": "^1.0.2",
        "through2": "^2.0.0"
    },
    "devDependencies": {
        "gulp": "^3.9.0",
        "gulp-istanbul": "^0.10.2",
        "gulp-util": "^3.0.7",
        "jshint": "^2.8.0",
        "tape": "*",
        "tap-colorize": "^1.2.0"
    },
    "peerDependencies": {
        "tape": "*"
    },
    "scripts": {
        "build": "npm run lint && npm test",
        "lint": "jshint --verbose index.js",
        "test": "gulp --cwd test test && gulp --cwd test istanbul"
    },
    "keywords": [
        "gulpplugin",
        "tape",
        "test"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

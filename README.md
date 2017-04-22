# npmtest-linklocal

#### basic test coverage for  [linklocal (v2.8.0)](https://github.com/timoxley/linklocal)  [![npm package](https://img.shields.io/npm/v/npmtest-linklocal.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-linklocal) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-linklocal.svg)](https://travis-ci.org/npmtest/node-npmtest-linklocal)

#### Install local dependencies as symlinks.

[![NPM](https://nodei.co/npm/linklocal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/linklocal)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-linklocal/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-linklocal/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-linklocal/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-linklocal/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-linklocal/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-linklocal/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-linklocal/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-linklocal/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-linklocal/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-linklocal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-linklocal/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-linklocal/build/test-report.html](https://npmtest.github.io/node-npmtest-linklocal/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-linklocal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-linklocal/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-linklocal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-linklocal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-linklocal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-linklocal/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-linklocal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-linklocal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim Oxley"
    },
    "bin": {
        "linklocal": "bin/linklocal.js"
    },
    "bugs": {
        "url": "https://github.com/timoxley/linklocal/issues"
    },
    "dependencies": {
        "commander": "^2.9.0",
        "debug": "^2.3.3",
        "map-limit": "0.0.1",
        "mkdirp": "^0.5.1",
        "rimraf": "^2.5.4"
    },
    "description": "Install local dependencies as symlinks.",
    "devDependencies": {
        "nyc": "^10.0.0",
        "standard": "^8.6.0",
        "tap-spec": "^4.1.1",
        "tape": "^4.6.3"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "77b97af16fff13da34dbb9fd3b53784c3d5baceb",
        "tarball": "https://registry.npmjs.org/linklocal/-/linklocal-2.8.0.tgz"
    },
    "engines": {
        "npm": ">=2.0.0"
    },
    "gitHead": "7f13e7da54ee894e41cb3db39251ba55f32aebe1",
    "homepage": "https://github.com/timoxley/linklocal",
    "keywords": [
        "npm",
        "packages",
        "symlink",
        "dependencies",
        "modules"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "timoxley"
        }
    ],
    "name": "linklocal",
    "nyc": {
        "cache": true,
        "exclude": [
            "test/*.js",
            "node_modules"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/timoxley/linklocal.git"
    },
    "scripts": {
        "test": "nyc -s tape test/*.js | tap-spec && nyc report --reporter=text --reporter=html && standard"
    },
    "version": "2.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# test coverage for  [dependency-check (v2.8.0)](https://github.com/maxogden/dependency-check)  [![npm package](https://img.shields.io/npm/v/npmtest-dependency-check.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dependency-check) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dependency-check.svg)](https://travis-ci.org/npmtest/node-npmtest-dependency-check)
#### checks which modules you have used in your code and then makes sure they are listed as dependencies in your package.json

[![NPM](https://nodei.co/npm/dependency-check.png?downloads=true)](https://www.npmjs.com/package/dependency-check)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dependency-check/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dependency-check/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dependency-check/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dependency-check/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dependency-check/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dependency-check/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dependency-check/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dependency-check/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-dependency-check/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-dependency-check/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-dependency-check%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dependency-check/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dependency-check/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-dependency-check%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dependency-check/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dependency-check/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dependency-check/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "max ogden"
    },
    "bin": {
        "dependency-check": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/maxogden/dependency-check/issues"
    },
    "dependencies": {
        "async": "^2.1.4",
        "builtins": "^1.0.0",
        "debug": "^2.2.0",
        "detective": "^4.0.0",
        "is-relative": "^0.2.1",
        "minimist": "^1.2.0",
        "read-package-json": "^2.0.4",
        "resolve": "^1.1.7"
    },
    "description": "checks which modules you have used in your code and then makes sure they are listed as dependencies in your package.json",
    "devDependencies": {
        "standard": "^8.6.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "ca1e08a78f6ca2dc4c7dad33e43a9040b0c23b68",
        "tarball": "https://registry.npmjs.org/dependency-check/-/dependency-check-2.8.0.tgz"
    },
    "gitHead": "656bd94862edc5363cc74a11a7aa1261a665153d",
    "homepage": "https://github.com/maxogden/dependency-check",
    "license": "BSD-3-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "blakeembrey",
            "email": "hello@blakeembrey.com"
        },
        {
            "name": "maxogden",
            "email": "max@maxogden.com"
        },
        {
            "name": "voxpelli",
            "email": "pelle@kodfabrik.se"
        }
    ],
    "name": "dependency-check",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/maxogden/dependency-check.git"
    },
    "scripts": {
        "test": "standard && node cli.js test/ && node cli.js . && node cli.js . --extra --no-dev"
    },
    "version": "2.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

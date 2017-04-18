# npmtest-jit-grunt

#### test coverage for  [jit-grunt (v0.10.0)](https://github.com/shootaroo/jit-grunt)  [![npm package](https://img.shields.io/npm/v/npmtest-jit-grunt.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jit-grunt) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jit-grunt.svg)](https://travis-ci.org/npmtest/node-npmtest-jit-grunt)

#### JIT plugin loader for Grunt.

[![NPM](https://nodei.co/npm/jit-grunt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jit-grunt)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jit-grunt/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jit-grunt/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jit-grunt/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jit-grunt/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jit-grunt/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jit-grunt/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jit-grunt/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jit-grunt/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jit-grunt/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jit-grunt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jit-grunt/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jit-grunt/build/test-report.html](https://npmtest.github.io/node-npmtest-jit-grunt/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jit-grunt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jit-grunt/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jit-grunt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jit-grunt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jit-grunt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jit-grunt/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jit-grunt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jit-grunt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "shootaroo"
    },
    "bugs": {
        "url": "https://github.com/shootaroo/jit-grunt/issues"
    },
    "dependencies": {},
    "description": "JIT plugin loader for Grunt.",
    "devDependencies": {
        "babel-cli": "^6.5.1",
        "babel-preset-es2015": "^6.5.0",
        "espower-babel": "^4.0.0",
        "grunt": "^0.4.0",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-jscs": "^2.7.0",
        "grunt-mocha-test": "^0.12.0",
        "husky": "^0.11.1",
        "mocha": "^2.4.5",
        "npm-run-all": "^1.5.1",
        "power-assert": "^1.2.0",
        "sinon": "^1.17.0"
    },
    "directories": {},
    "dist": {
        "shasum": "008c3a7fe1e96bd0d84e260ea1fa1783457f79c2",
        "tarball": "https://registry.npmjs.org/jit-grunt/-/jit-grunt-0.10.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "lib",
        "jit-grunt.js"
    ],
    "gitHead": "e37e86520322c183593ca67405a5f4a6faa2faac",
    "homepage": "https://github.com/shootaroo/jit-grunt",
    "keywords": [
        "grunt",
        "gruntplugin",
        "jit",
        "loader"
    ],
    "license": "MIT",
    "main": "jit-grunt",
    "maintainers": [
        {
            "name": "shootaroo"
        }
    ],
    "name": "jit-grunt",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/shootaroo/jit-grunt.git"
    },
    "scripts": {
        "build": "babel src -d lib",
        "jscs": "grunt jscs",
        "jshint": "grunt jshint",
        "lint": "npm-run-all -p jscs jshint",
        "mocha": "grunt mochaTest",
        "precommit": "npm test",
        "prepush": "npm test",
        "test": "npm-run-all build -p lint mocha",
        "watch": "babel src -d lib --watch"
    },
    "version": "0.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

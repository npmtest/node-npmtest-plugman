# npmtest-plugman

#### basic test coverage for  plugman (v1.4.1)  [![npm package](https://img.shields.io/npm/v/npmtest-plugman.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-plugman) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-plugman.svg)](https://travis-ci.org/npmtest/node-npmtest-plugman)

#### install/uninstall Cordova plugins

[![NPM](https://nodei.co/npm/plugman.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/plugman)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-plugman/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-plugman/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-plugman/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-plugman/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-plugman/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-plugman/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-plugman/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-plugman/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-plugman/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-plugman/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-plugman/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-plugman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-plugman/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-plugman/build/test-report.html](https://npmtest.github.io/node-npmtest-plugman/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-plugman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-plugman/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-plugman/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-plugman/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-plugman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-plugman/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-plugman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-plugman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Lunny"
    },
    "name": "plugman",
    "description": "install/uninstall Cordova plugins",
    "version": "1.4.1",
    "repository": {
        "type": "git",
        "url": "git://git-wip-us.apache.org/repos/asf/cordova-plugman.git"
    },
    "bugs": {
        "url": "https://issues.apache.org/jira/browse/CB"
    },
    "main": "plugman.js",
    "engines": {
        "node": ">=0.9.9"
    },
    "engineStrict": true,
    "dependencies": {
        "cordova-lib": "6.5.0",
        "nopt": "1.0.9",
        "q": "1.0.1"
    },
    "devDependencies": {
        "jshint": "2.5.8",
        "jasmine-node": "1.14.5"
    },
    "bin": {
        "plugman": "./main.js"
    },
    "scripts": {
        "test": "npm run jasmine && npm run jshint",
        "jshint": "node node_modules/jshint/bin/jshint src",
        "jasmine": "jasmine-node --captureExceptions --color spec"
    },
    "license": "Apache-2.0",
    "contributors": [
        {
            "name": "Anis Kadri"
        },
        {
            "name": "Tim Kim"
        },
        {
            "name": "Braden Shepherdson"
        },
        {
            "name": "Ryan Willoughby"
        },
        {
            "name": "Brett Rudd"
        },
        {
            "name": "Mike Reinstein"
        },
        {
            "name": "Shazron Abdullah"
        },
        {
            "name": "Steve Gill"
        },
        {
            "name": "Fil Maj"
        },
        {
            "name": "Michael Brooks"
        },
        {
            "name": "Jesse MacFadyen"
        }
    ],
    "dist": {
        "shasum": "6521bae13c03e91f6e52969233cb16b5d1766a1e",
        "tarball": "https://registry.npmjs.org/plugman/-/plugman-1.4.1.tgz"
    },
    "maintainers": [
        {
            "name": "agrieve"
        },
        {
            "name": "anis"
        },
        {
            "name": "bennmapes"
        },
        {
            "name": "bowserj"
        },
        {
            "name": "brianleroux"
        },
        {
            "name": "cmarcelk"
        },
        {
            "name": "filmaj"
        },
        {
            "name": "kamrik"
        },
        {
            "name": "kotikov.vladimir"
        },
        {
            "name": "mmocny"
        },
        {
            "name": "purplecabbage"
        },
        {
            "name": "sgrebnov"
        },
        {
            "name": "shazron"
        },
        {
            "name": "shepheb"
        },
        {
            "name": "stevegill"
        },
        {
            "name": "timkim"
        }
    ],
    "directories": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

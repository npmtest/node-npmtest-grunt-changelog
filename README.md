# npmtest-grunt-changelog

#### basic test coverage for  [grunt-changelog (v0.3.2)](https://github.com/ericmatthys/grunt-changelog)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-changelog.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-changelog) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-changelog.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-changelog)

#### Generate a changelog based on commit messages.

[![NPM](https://nodei.co/npm/grunt-changelog.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-changelog)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-changelog/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-changelog/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-changelog/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-changelog/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-changelog/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-changelog/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-changelog/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-changelog/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-changelog/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-changelog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-changelog/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-changelog/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-changelog/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-changelog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-changelog/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-changelog/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-changelog/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-changelog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-changelog/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-changelog/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-changelog/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-changelog",
    "description": "Generate a changelog based on commit messages.",
    "version": "0.3.2",
    "homepage": "https://github.com/ericmatthys/grunt-changelog",
    "author": {
        "name": "Eric Matthys"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/ericmatthys/grunt-changelog.git"
    },
    "bugs": {
        "url": "https://github.com/ericmatthys/grunt-changelog/issues"
    },
    "license": "MIT",
    "scripts": {
        "test": "grunt test"
    },
    "dependencies": {
        "handlebars": "~4.0.5",
        "moment": "~2.12.0",
        "semver": "^5.1.0",
        "underscore": "~1.8.3"
    },
    "devDependencies": {
        "grunt-contrib-jshint": "~1.0.0",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-nodeunit": "~1.0.0",
        "grunt": "~1.0.1"
    },
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "keywords": [
        "gruntplugin",
        "grunt",
        "changelog",
        "release notes"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

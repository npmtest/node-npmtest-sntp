# npmtest-sntp

#### basic test coverage for  [sntp (v2.0.2)](https://github.com/hueniverse/sntp#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sntp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sntp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sntp.svg)](https://travis-ci.org/npmtest/node-npmtest-sntp)

#### SNTP Client

[![NPM](https://nodei.co/npm/sntp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sntp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sntp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sntp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sntp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sntp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sntp/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-sntp/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-sntp/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sntp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sntp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sntp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sntp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sntp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sntp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sntp/build/test-report.html](https://npmtest.github.io/node-npmtest-sntp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sntp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sntp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sntp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sntp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sntp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sntp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sntp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sntp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eran Hammer",
        "url": "http://hueniverse.com"
    },
    "bugs": {
        "url": "https://github.com/hueniverse/sntp/issues"
    },
    "dependencies": {
        "hoek": "4.x.x"
    },
    "description": "SNTP Client",
    "devDependencies": {
        "code": "4.x.x",
        "lab": "10.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "5064110f0af85f7cfdb7d6b67a40028ce52b4b2b",
        "tarball": "https://registry.npmjs.org/sntp/-/sntp-2.0.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "c92f322dc1b04c958dc9e5da67e6e6947df407bb",
    "homepage": "https://github.com/hueniverse/sntp#readme",
    "keywords": [
        "sntp",
        "ntp",
        "time"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        }
    ],
    "name": "sntp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hueniverse/sntp.git"
    },
    "scripts": {
        "test": "lab -a code -t 100 -L -m 20000",
        "test-cov-html": "lab -a code -r html -o coverage.html -m 20000"
    },
    "version": "2.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-crdt

#### test coverage for  [crdt (v3.6.4)](http://github.com/dominictarr/crdt)  [![npm package](https://img.shields.io/npm/v/npmtest-crdt.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-crdt) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-crdt.svg)](https://travis-ci.org/npmtest/node-npmtest-crdt)

#### Commutative Replicated Data Types for easy distributed/collaborative apps

[![NPM](https://nodei.co/npm/crdt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/crdt)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-crdt/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-crdt/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-crdt/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-crdt/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-crdt/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-crdt/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-crdt/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-crdt/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-crdt/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-crdt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-crdt/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-crdt/build/test-report.html](https://npmtest.github.io/node-npmtest-crdt/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-crdt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-crdt/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-crdt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-crdt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-crdt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-crdt/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-crdt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-crdt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic",
        "url": "http://dominictarr.com"
    },
    "bugs": {
        "url": "https://github.com/dominictarr/crdt/issues"
    },
    "dependencies": {
        "between": "~0.1",
        "it-is": "~1.0.3",
        "scuttlebutt": ">=5.6.6 <6"
    },
    "description": "Commutative Replicated Data Types for easy distributed/collaborative apps",
    "devDependencies": {
        "assertions": "~2.3.1",
        "asynct": "~1.1",
        "event-stream": "~3.0",
        "it-is": "~1.0.1",
        "kv": "~0.5",
        "mux-demux": "~3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "8473aed93ac71953f3a1df0f8ac7f97bfef6b8d5",
        "tarball": "https://registry.npmjs.org/crdt/-/crdt-3.6.4.tgz"
    },
    "homepage": "http://github.com/dominictarr/crdt",
    "maintainers": [
        {
            "name": "dominictarr"
        }
    ],
    "name": "crdt",
    "optionalDependencies": {},
    "repository": {
        "url": "git://github.com/dominictarr/crdt.git"
    },
    "scripts": {
        "test": "asynct test/*.js"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/8..latest",
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
        ]
    },
    "version": "3.6.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

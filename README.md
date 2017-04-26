# npmtest-blynk-library

#### basic test coverage for  [blynk-library (v0.4.7)](https://github.com/vshymanskyy/blynk-library-js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-blynk-library.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-blynk-library) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-blynk-library.svg)](https://travis-ci.org/npmtest/node-npmtest-blynk-library)

#### Blynk library implementation for JavaScript (Node.js, Espruino)

[![NPM](https://nodei.co/npm/blynk-library.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/blynk-library)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-blynk-library/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-blynk-library/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-blynk-library/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-blynk-library/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-blynk-library/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-blynk-library/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-blynk-library/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-blynk-library/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-blynk-library/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-blynk-library/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-blynk-library/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-blynk-library/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-blynk-library/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-blynk-library/build/test-report.html](https://npmtest.github.io/node-npmtest-blynk-library/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-blynk-library/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-blynk-library/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-blynk-library/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-blynk-library/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-blynk-library/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-blynk-library/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-blynk-library/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-blynk-library/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Volodymyr Shymanskyy"
    },
    "bin": {
        "blynk-client": "bin/blynk-client.js",
        "blynk-ctrl": "bin/blynk-ctrl.js"
    },
    "browser": {
        "./blynk-node.js": false
    },
    "bugs": {
        "url": "https://github.com/vshymanskyy/blynk-library-js/issues"
    },
    "dependencies": {},
    "description": "Blynk library implementation for JavaScript (Node.js, Espruino)",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "ccde038bf9e9bb5748bc473036bf25701d43bd8d",
        "tarball": "https://registry.npmjs.org/blynk-library/-/blynk-library-0.4.7.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "gitHead": "79524abdf5168b5b6811ec6ef67d6ac356dbe5d2",
    "homepage": "https://github.com/vshymanskyy/blynk-library-js#readme",
    "keywords": [
        "Arduino",
        "Espruino",
        "Raspberry Pi",
        "IoT",
        "Internet of Things"
    ],
    "license": "MIT",
    "main": "./blynk.js",
    "maintainers": [
        {
            "name": "vshymanskyy"
        }
    ],
    "name": "blynk-library",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vshymanskyy/blynk-library-js.git"
    },
    "scripts": {
        "prepublish": "make clean all",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "0.4.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

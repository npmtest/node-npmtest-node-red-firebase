# npmtest-node-red-firebase

#### basic test coverage for  [node-red-firebase (v0.1.0)](https://github.com/yieme/node-red-firebase)  [![npm package](https://img.shields.io/npm/v/npmtest-node-red-firebase.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-red-firebase) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-red-firebase.svg)](https://travis-ci.org/npmtest/node-npmtest-node-red-firebase)

#### Check it out! Now you can access your Firebase data with Node-RED! This allows you to automate Firebase data manipulation or generate custom events based on what's going on with your data store.

[![NPM](https://nodei.co/npm/node-red-firebase.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-red-firebase)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-red-firebase/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-red-firebase/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-red-firebase/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-red-firebase/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-red-firebase/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-red-firebase/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-red-firebase/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-red-firebase/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-red-firebase/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-red-firebase/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-red-firebase/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-red-firebase/build/test-report.html](https://npmtest.github.io/node-npmtest-node-red-firebase/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-red-firebase/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-red-firebase/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-red-firebase/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-red-firebase/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-red-firebase/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-red-firebase/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-red-firebase/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-red-firebase/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-red-firebase",
    "version": "0.1.0",
    "description": "Check it out! Now you can access your Firebase data with Node-RED! This allows you to automate Firebase data manipulation or generate custom events based on what's going on with your data store.",
    "main": "firebase_query.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/yieme/node-red-firebase.git"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "keywords": [
        "node-red",
        "node",
        "firebase",
        "real",
        "time",
        "socket"
    ],
    "node-red": {
        "nodes": {
            "firebase_modify": "firebase_modify.js",
            "firebase_query": "firebase_query.js",
            "firebase_watch": "firebase_watch.js"
        }
    },
    "author": "Hovis <hovis@bunkercode.com>",
    "contributors": [
        "André Lademann <vergissberlin@googlemail.com>",
        "Gitter <badger@gitter.im>",
        "Yieme <yieme@>"
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/yieme/node-red-firebase/issues"
    },
    "homepage": "https://github.com/yieme/node-red-firebase",
    "dependencies": {
        "firebase": "^2.1.0",
        "firebase-login-custom": "0.0.4",
        "firebase-login-email": "^0.0.4"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-electron-dl

#### basic test coverage for  electron-dl (v1.8.0)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-dl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-dl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-dl.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-dl)

#### Simplified file downloads for your Electron app

[![NPM](https://nodei.co/npm/electron-dl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-dl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-dl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-dl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-dl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-dl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-dl/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-dl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-dl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron-dl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron-dl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-dl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron-dl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron-dl/build/test-report.html](https://npmtest.github.io/node-npmtest-electron-dl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron-dl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron-dl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron-dl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-dl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-dl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-dl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron-dl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron-dl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "electron-dl",
    "version": "1.8.0",
    "description": "Simplified file downloads for your Electron app",
    "license": "MIT",
    "repository": "sindresorhus/electron-dl",
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "scripts": {
        "start": "electron test.js",
        "test": "xo"
    },
    "files": [
        "index.js"
    ],
    "keywords": [
        "electron",
        "app",
        "file",
        "download",
        "downloader",
        "progress"
    ],
    "dependencies": {
        "pupa": "^1.0.0",
        "unused-filename": "^0.1.0"
    },
    "devDependencies": {
        "electron": "^1.3.3",
        "xo": "*"
    },
    "xo": {
        "esnext": true,
        "envs": [
            "node",
            "browser"
        ],
        "rules": {
            "import/no-extraneous-dependencies": "off"
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

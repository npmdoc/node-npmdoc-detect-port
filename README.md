# npmdoc-detect-port

#### api documentation for  [detect-port (v1.1.1)](https://github.com/node-modules/detect-port)  [![npm package](https://img.shields.io/npm/v/npmdoc-detect-port.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-detect-port) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-detect-port.svg)](https://travis-ci.org/npmdoc/node-npmdoc-detect-port)

#### detect available port

[![NPM](https://nodei.co/npm/detect-port.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/detect-port)

- [https://npmdoc.github.io/node-npmdoc-detect-port/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-detect-port/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-detect-port/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-detect-port/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-detect-port/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-detect-port/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "detect-port",
    "version": "1.1.1",
    "description": "detect available port",
    "keywords": [
        "detect",
        "port"
    ],
    "bin": {
        "detect": "./bin/detect-port",
        "detect-port": "./bin/detect-port"
    },
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/node-modules/detect-port.git"
    },
    "dependencies": {
        "debug": "^2.6.0"
    },
    "devDependencies": {
        "command-line-test": "^1.0.8",
        "egg-bin": "^1.10.3",
        "egg-ci": "^1.1.0",
        "eslint": "^3.13.1",
        "eslint-config-egg": "^3.1.0",
        "pedding": "^1.1.0"
    },
    "scripts": {
        "test": "egg-bin test",
        "ci": "npm run lint && egg-bin cov",
        "lint": "eslint ."
    },
    "engines": {
        "node": ">= 4.2.1"
    },
    "ci": {
        "version": "4, 6, 7"
    },
    "homepage": "https://github.com/node-modules/detect-port",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

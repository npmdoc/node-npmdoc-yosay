# npmdoc-yosay

#### api documentation for  [yosay (v2.0.0)](yeoman.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-yosay.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-yosay) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-yosay.svg)](https://travis-ci.org/npmdoc/node-npmdoc-yosay)

#### Tell Yeoman what to say

[![NPM](https://nodei.co/npm/yosay.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yosay)

- [https://npmdoc.github.io/node-npmdoc-yosay/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yosay/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yosay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yosay/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-yosay/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-yosay/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "yosay",
    "version": "2.0.0",
    "description": "Tell Yeoman what to say",
    "license": "BSD-2-Clause",
    "repository": "yeoman/yosay",
    "homepage": "yeoman.io",
    "author": "Yeoman",
    "bin": "cli.js",
    "engines": {
        "node": ">=4"
    },
    "scripts": {
        "test": "xo && mocha"
    },
    "files": [
        "index.js",
        "cli.js"
    ],
    "keywords": [
        "cli-app",
        "cli",
        "yeoman",
        "yo",
        "cowsay",
        "say",
        "box",
        "message",
        "ansi"
    ],
    "dependencies": {
        "ansi-regex": "^2.0.0",
        "ansi-styles": "^3.0.0",
        "chalk": "^1.0.0",
        "cli-boxes": "^1.0.0",
        "pad-component": "0.0.1",
        "string-width": "^2.0.0",
        "strip-ansi": "^3.0.0",
        "taketalk": "^1.0.0",
        "wrap-ansi": "^2.0.0"
    },
    "devDependencies": {
        "mocha": "^3.2.0",
        "xo": "^0.17.0"
    },
    "xo": {
        "space": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

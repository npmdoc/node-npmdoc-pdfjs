# npmdoc-pdfjs

#### api documentation for  [pdfjs (v2.0.0-alpha.1)](https://github.com/rkusa/pdfjs)  [![npm package](https://img.shields.io/npm/v/npmdoc-pdfjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pdfjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pdfjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pdfjs)

#### A Portable Document Format (PDF) generation library targeting both the server- and client-side.

[![NPM](https://nodei.co/npm/pdfjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pdfjs)

- [https://npmdoc.github.io/node-npmdoc-pdfjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pdfjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pdfjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pdfjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pdfjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pdfjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pdfjs",
    "author": "Markus Ast <npm.m@rkusa.st>",
    "version": "2.0.0-alpha.1",
    "description": "A Portable Document Format (PDF) generation library targeting both the server- and client-side.",
    "keywords": [
        "pdf",
        "generator"
    ],
    "license": "MIT",
    "homepage": "https://github.com/rkusa/pdfjs",
    "bugs": "https://github.com/rkusa/pdfjs/issues",
    "main": "lib/",
    "scripts": {
        "test": "node --harmony-async-await test/index.js test/pdfs/**/*.js"
    },
    "dependencies": {
        "linebreak": "^0.3.0",
        "opentype.js": "^0.6.2",
        "unorm": "^1.4.1",
        "uuid": "^3.0.1"
    },
    "devDependencies": {
        "tape": "^4.6.3"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/rkusa/pdfjs.git"
    },
    "engines": {
        "node": ">=7"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

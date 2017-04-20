# npmdoc-scrollmonitor

#### api documentation for  scrollmonitor (v1.2.3)  [![npm package](https://img.shields.io/npm/v/npmdoc-scrollmonitor.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-scrollmonitor) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-scrollmonitor.svg)](https://travis-ci.org/npmdoc/node-npmdoc-scrollmonitor)

#### A simple and fast API to monitor DOM elements as you scroll

[![NPM](https://nodei.co/npm/scrollmonitor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/scrollmonitor)

- [https://npmdoc.github.io/node-npmdoc-scrollmonitor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-scrollmonitor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-scrollmonitor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-scrollmonitor/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-scrollmonitor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-scrollmonitor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "scrollmonitor",
    "version": "1.2.3",
    "author": "Stu Kabakoff <stukabakoff@gmail.com>",
    "description": "A simple and fast API to monitor DOM elements as you scroll",
    "contributors": [
        {
            "name": "Stu Kabakoff"
        },
        {
            "name": "Terrence Lee"
        },
        {
            "name": "Roman Kalyakin"
        }
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/stutrek/scrollMonitor.git"
    },
    "keywords": [
        "scroll",
        "dom"
    ],
    "scripts": {
        "test": "webpack; testem ci",
        "start": "webpack; testem"
    },
    "license": "MIT",
    "main": "./scrollMonitor.js",
    "dependencies": {},
    "devDependencies": {
        "babel-core": "^6.2.1",
        "babel-loader": "^6.2.0",
        "babel-plugin-transform-es3-member-expression-literals": "^6.8.0",
        "babel-plugin-transform-es3-property-literals": "^6.8.0",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-stage-0": "^6.5.0",
        "sinon": "^1.17.6",
        "testem": "github:stutrek/testem",
        "webpack": "^1.13.1"
    },
    "spm": {
        "main": "scrollMonitor.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

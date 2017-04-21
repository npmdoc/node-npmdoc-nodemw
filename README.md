# npmdoc-nodemw

#### api documentation for  nodemw (v0.10.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-nodemw.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nodemw) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nodemw.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nodemw)

#### MediaWiki API client written in node.js

[![NPM](https://nodei.co/npm/nodemw.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nodemw)

- [https://npmdoc.github.io/node-npmdoc-nodemw/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nodemw/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nodemw/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nodemw/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nodemw/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nodemw/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nodemw",
    "version": "0.10.1",
    "author": "macbre <maciej.brencz@gmail.com> (http://macbre.net)",
    "description": "MediaWiki API client written in node.js",
    "main": "./lib/bot",
    "repository": {
        "type": "git",
        "url": "git://github.com/macbre/nodemw.git"
    },
    "keywords": [
        "mediawiki",
        "wiki",
        "api",
        "nodejs",
        "wikia"
    ],
    "license": "BSD",
    "engines": {
        "node": ">=0.6"
    },
    "dependencies": {
        "ansicolors": "0.3.x",
        "async": "^2.0.0-rc.5",
        "diff": "^2.2.3",
        "jshint": "^2.9.1",
        "node-version-compare": "^1.0.1",
        "request": "^2.72.0",
        "underscore": "1.8.x",
        "winston": "^2.2.0"
    },
    "devDependencies": {
        "csv-string": "2.3.x",
        "esnext": "^2.0.0",
        "jshint": "^2.9.2",
        "vows": "0.8.x"
    },
    "scripts": {
        "test": "vows --spec",
        "lint": "jshint lib/api.js lib/bot.js examples/ test/"
    },
    "jshintConfig": {
        "node": true,
        "esversion": 6,
        "-W030": false,
        "-W084": false
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

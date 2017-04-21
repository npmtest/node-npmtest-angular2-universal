# npmtest-angular2-universal

#### basic test coverage for  [angular2-universal (v2.1.0-rc.1)](https://github.com/angular/universal)  [![npm package](https://img.shields.io/npm/v/npmtest-angular2-universal.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular2-universal) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular2-universal.svg)](https://travis-ci.org/npmtest/node-npmtest-angular2-universal)

#### Universal (isomorphic) javascript support for Angular2

[![NPM](https://nodei.co/npm/angular2-universal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular2-universal)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular2-universal/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-universal/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-universal/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular2-universal/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-universal/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular2-universal/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular2-universal/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angular2-universal/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angular2-universal/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-universal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angular2-universal/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angular2-universal/build/test-report.html](https://npmtest.github.io/node-npmtest-angular2-universal/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular2-universal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular2-universal/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angular2-universal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angular2-universal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular2-universal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular2-universal/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular2-universal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular2-universal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "angular2-universal",
    "description": "Universal (isomorphic) javascript support for Angular2",
    "main": "node/index.js",
    "browser": "browser/index.js",
    "typings": "typings.d.ts",
    "files": [
        "node",
        "browser",
        "common",
        "lib",
        "src",
        "typings.d.ts",
        "browser.js",
        "browser.js.map",
        "browser.metadata.json",
        "browser.d.ts",
        "node.js",
        "node.js.map",
        "node.metadata.json",
        "node.d.ts",
        "LICENSE",
        "index.js"
    ],
    "dependencies": {
        "angular2-platform-node": "~2.1.0-rc.1",
        "css": "^2.2.1",
        "js-beautify": "^1.6.4",
        "parse5": "^2.2.1",
        "xhr2": "^0.1.3",
        "preboot": "4.5.2"
    },
    "peerDependencies": {
        "rxjs": "~5.0.0-beta.12",
        "zone.js": "~0.6.21"
    },
    "contributors": [
        "gdi2290",
        "manekinekko",
        "jeffwhelpley",
        "MarkPieszak",
        "ashsidhu",
        "jeffbcross",
        "wesleycho",
        "dbabaioff",
        "tamascsaba",
        "alexpods",
        "laskoviymishka",
        "JohnGorter",
        "valorkin",
        "playground",
        "swirlycheetah",
        "datwheat",
        "btrigueiro",
        "Krijger",
        "vangorden",
        "alfamegaxq",
        "QuinntyneBrown",
        "vvakame",
        "gitter-badger",
        "juristr",
        "filipesilva",
        "lightningtgc",
        "justindujardin",
        "wellingWilliam",
        "adams",
        "alxhub",
        "naomiblack",
        "NathanWalker",
        "basarat",
        "visikov",
        "tbosch",
        "bnjjj"
    ],
    "version": "2.1.0-rc.1",
    "homepage": "https://github.com/angular/universal",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/angular/universal"
    },
    "bugs": {
        "url": "https://github.com/angular/universal/issues"
    },
    "config": {
        "engine-strict": true
    },
    "engines": {
        "node": ">= 5.4.1 <= 7",
        "npm": ">= 3"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

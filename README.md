# npmdoc-isogram

#### api documentation for  isogram (v0.6.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-isogram.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-isogram) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-isogram.svg)](https://travis-ci.org/npmdoc/node-npmdoc-isogram)

#### Generate Google Analytics snippet with any 'isogrammic' parameters you like

[![NPM](https://nodei.co/npm/isogram.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/isogram)

- [https://npmdoc.github.io/node-npmdoc-isogram/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-isogram/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-isogram/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-isogram/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-isogram/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-isogram/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "isogram",
    "version": "0.6.0",
    "description": "Generate Google Analytics snippet with any 'isogrammic' parameters you like",
    "repository": "shinnn/isogram",
    "author": "Shinnosuke Watanabe (https://github.com/shinnn)",
    "license": "MIT",
    "bin": "cli.js",
    "files": [
        "cli.js",
        "index.js"
    ],
    "scripts": {
        "test": "gulp test",
        "pretest-only": "bower install --production",
        "test-only": "bower install --production && tape test-*.js",
        "coverage": "istanbul cover -x=bower_components/** test-api.js"
    },
    "keywords": [
        "snippet",
        "source",
        "script",
        "code",
        "analytics",
        "google analytics",
        "universal analytics",
        "parameter",
        "parameters",
        "word",
        "word play",
        "isogram",
        "nonpattern",
        "browser",
        "client-side",
        "cli",
        "command-line"
    ],
    "dependencies": {
        "array-to-sentence": "^1.0.3",
        "assert-unique": "^1.0.0",
        "chalk": "^1.0.0",
        "ga-loader-snippets": "^1.1.0",
        "ga-tracker-snippet": "^1.0.0",
        "is-var-name": "^1.0.0",
        "minimist": "^1.1.1",
        "sum-up": "^1.0.2"
    },
    "devDependencies": {
        "bower": "^1.6.5",
        "browserify": "^12.0.1",
        "each-exec": "^1.0.0",
        "gulp": "^3.9.0",
        "gulp-jscs": "^3.0.2",
        "gulp-jshint": "^1.12.0",
        "gulp-jsonlint": "^1.1.1",
        "gulp-load-plugins": "^1.0.0",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.4",
        "istanbul": "^0.4.0",
        "jshint-stylish": "^2.0.1",
        "merge-stream": "^1.0.0",
        "require-bower-files": "^3.0.0",
        "rimraf": "^2.4.3",
        "script-equal": "^1.0.1",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.2",
        "to-camel-case": "^0.2.1",
        "vinyl-source-stream": "^1.1.0"
    },
    "jscsConfig": {
        "preset": "google",
        "maximumLineLength": 98
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

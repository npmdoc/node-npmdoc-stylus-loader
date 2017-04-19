# npmdoc-stylus-loader

#### api documentation for  [stylus-loader (v3.0.1)](https://github.com/shama/stylus-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-stylus-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-stylus-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-stylus-loader.svg)](https://travis-ci.org/npmdoc/node-npmdoc-stylus-loader)

#### Stylus loader for webpack

[![NPM](https://nodei.co/npm/stylus-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stylus-loader)

- [https://npmdoc.github.io/node-npmdoc-stylus-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Robinson Young",
        "url": "http://dontkry.com"
    },
    "bugs": {
        "url": "https://github.com/shama/stylus-loader/issues"
    },
    "dependencies": {
        "loader-utils": "^1.0.2",
        "lodash.clonedeep": "^4.5.0",
        "when": "~3.6.x"
    },
    "description": "Stylus loader for webpack",
    "devDependencies": {
        "benchmark": "^1.0.0",
        "css-loader": "^0.14.0",
        "mocha": "~2.1.0",
        "mocha-loader": "^1.0.0",
        "nib": "^1.0.4",
        "node-libs-browser": "^0.5.2",
        "raw-loader": "~0.5.1",
        "should": "~4.6.1",
        "style-loader": "^0.12.2",
        "stylus": ">=0.52.4",
        "testem": "^0.8.3",
        "webpack": "^2.2.0",
        "webpack-dev-server": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "77f4b34fd030d25b2617bcf5513db5b0730c4089",
        "tarball": "https://registry.npmjs.org/stylus-loader/-/stylus-loader-3.0.1.tgz"
    },
    "files": [
        "index.js",
        "lib/"
    ],
    "gitHead": "a2725db3827f7f41d350a079ffe215005a71b159",
    "homepage": "https://github.com/shama/stylus-loader#readme",
    "keywords": [
        "webpack",
        "loader",
        "stylus"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "shama"
        },
        {
            "name": "mzgoddard"
        }
    ],
    "name": "stylus-loader",
    "optionalDependencies": {},
    "peerDependencies": {
        "stylus": ">=0.52.4"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/shama/stylus-loader.git"
    },
    "scripts": {
        "test": "testem ci",
        "test-build": "webpack --config test/webpack.config.js --output-path=test/tmp --output-filename=bundle.js",
        "test-dev": "testem -l firefox",
        "test-one": "testem ci -l firefox"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

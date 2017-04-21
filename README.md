# npmtest-ng2-validation

#### basic test coverage for  [ng2-validation (v4.1.0)](https://github.com/yuyang041060120/angular2-validate#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ng2-validation.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ng2-validation) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ng2-validation.svg)](https://travis-ci.org/npmtest/node-npmtest-ng2-validation)

#### angular2 validation

[![NPM](https://nodei.co/npm/ng2-validation.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ng2-validation)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ng2-validation/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng2-validation/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ng2-validation/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ng2-validation/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ng2-validation/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ng2-validation/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ng2-validation/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ng2-validation/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ng2-validation/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng2-validation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ng2-validation/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ng2-validation/build/test-report.html](https://npmtest.github.io/node-npmtest-ng2-validation/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ng2-validation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ng2-validation/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ng2-validation/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ng2-validation/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ng2-validation/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ng2-validation/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ng2-validation/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ng2-validation/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ng2-validation",
    "version": "4.1.0",
    "description": "angular2 validation",
    "main": "dist/index.js",
    "typings": "dist/index.d.ts",
    "scripts": {
        "test": "karma start ./karma.conf.js",
        "dev": "webpack-dev-server --port 4001 --watch",
        "example": "webpack --optimize-minimize",
        "ngc": "ngc",
        "prerollup": "rimraf bundles",
        "rollup": "rollup -c",
        "prebuild": "rimraf dist",
        "build": "npm run ngc && npm run rollup",
        "prepublish": "npm run build"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yuyang041060120/angular2-validate.git"
    },
    "keywords": [
        "angular2",
        "validate",
        "validation"
    ],
    "author": "yuyang041060120 <yuyang041060120@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/yuyang041060120/angular2-validate/issues"
    },
    "homepage": "https://github.com/yuyang041060120/angular2-validate#readme",
    "devDependencies": {
        "@angular/common": "4.0.0",
        "@angular/compiler": "4.0.0",
        "@angular/compiler-cli": "4.0.0",
        "@angular/core": "4.0.0",
        "@angular/forms": "4.0.0",
        "@angular/http": "4.0.0",
        "@angular/platform-browser": "4.0.0",
        "@angular/platform-browser-dynamic": "4.0.0",
        "@types/jasmine": "^2.2.29",
        "@types/node": "^7.0.12",
        "bootstrap": "^3.3.7",
        "core-js": "^2.4.1",
        "jasmine-core": "^2.4.1",
        "jasmine-data-provider": "^2.2.0",
        "karma": "^1.1.1",
        "karma-jasmine": "^1.0.2",
        "karma-phantomjs-launcher": "^1.0.1",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^2.0.3",
        "less": "^2.7.2",
        "less-loader": "^4.0.2",
        "phantomjs-prebuilt": "^2.1.7",
        "raw-loader": "^0.5.1",
        "reflect-metadata": "^0.1.3",
        "rimraf": "^2.5.4",
        "rollup": "^0.41.4",
        "rollup-plugin-typescript": "^0.8.1",
        "rxjs": "^5.2.0",
        "ts-loader": "^2.0.3",
        "typescript": "^2.2.2",
        "webpack": "^2.3.2",
        "webpack-dev-server": "^2.4.2",
        "zone.js": "^0.8.4"
    },
    "dependencies": {
        "libphonenumber-js": "^0.4.5"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

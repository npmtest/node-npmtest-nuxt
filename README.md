# npmtest-nuxt

#### basic test coverage for  [nuxt (v0.10.6)](https://github.com/nuxt/nuxt.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nuxt.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nuxt) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nuxt.svg)](https://travis-ci.org/npmtest/node-npmtest-nuxt)

#### A minimalistic framework for server-rendered Vue.js applications (inspired by Next.js)

[![NPM](https://nodei.co/npm/nuxt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nuxt)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nuxt/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nuxt/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nuxt/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nuxt/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nuxt/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-nuxt/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-nuxt/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nuxt/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nuxt/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nuxt/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nuxt/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nuxt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nuxt/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nuxt/build/test-report.html](https://npmtest.github.io/node-npmtest-nuxt/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nuxt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nuxt/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nuxt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nuxt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nuxt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nuxt/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nuxt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nuxt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "nuxt": "./bin/nuxt"
    },
    "bugs": {
        "url": "https://github.com/nuxt/nuxt.js/issues"
    },
    "contributors": [
        {
            "name": "Sebastien Chopin"
        },
        {
            "name": "Alexandre Chopin"
        }
    ],
    "dependencies": {
        "ansi-html": "^0.0.7",
        "autoprefixer": "^6.7.7",
        "babel-core": "^6.24.0",
        "babel-loader": "^6.4.1",
        "babel-preset-es2015": "^6.24.0",
        "babel-preset-vue-app": "^1.1.1",
        "chokidar": "^1.6.1",
        "co": "^4.6.0",
        "compression": "^1.6.2",
        "css-loader": "^0.28.0",
        "debug": "^2.6.3",
        "file-loader": "^0.11.1",
        "friendly-errors-webpack-plugin": "^1.6.1",
        "fs-extra": "^2.1.2",
        "glob": "^7.1.1",
        "hash-sum": "^1.0.2",
        "html-minifier": "^3.4.2",
        "html-webpack-plugin": "^2.28.0",
        "lodash": "^4.17.4",
        "lru-cache": "^4.0.2",
        "memory-fs": "^0.4.1",
        "offline-plugin": "^4.6.1",
        "pify": "^2.3.0",
        "post-compile-webpack-plugin": "^0.1.1",
        "preload-webpack-plugin": "^1.2.2",
        "progress-bar-webpack-plugin": "^1.9.3",
        "script-ext-html-webpack-plugin": "^1.7.1",
        "serialize-javascript": "^1.3.0",
        "serve-static": "^1.12.1",
        "url-loader": "^0.5.8",
        "vue": "^2.2.6",
        "vue-loader": "^11.3.4",
        "vue-meta": "^0.5.6",
        "vue-router": "^2.3.1",
        "vue-server-renderer": "^2.2.6",
        "vue-ssr-html-stream": "^2.2.0",
        "vue-ssr-webpack-plugin": "^3.0.0",
        "vue-template-compiler": "^2.2.6",
        "vuex": "^2.2.1",
        "webpack": "^2.3.3",
        "webpack-bundle-analyzer": "^2.3.1",
        "webpack-dev-middleware": "^1.10.1",
        "webpack-hot-middleware": "^2.18.0"
    },
    "description": "A minimalistic framework for server-rendered Vue.js applications (inspired by Next.js)",
    "devDependencies": {
        "ava": "^0.19.0",
        "babel-eslint": "^7.2.1",
        "babel-plugin-array-includes": "^2.0.3",
        "babel-plugin-transform-async-to-generator": "^6.22.0",
        "babel-plugin-transform-runtime": "^6.23.0",
        "babel-preset-stage-2": "^6.22.0",
        "codecov": "^2.1.0",
        "copy-webpack-plugin": "^4.0.1",
        "eslint": "^3.19.0",
        "eslint-config-standard": "^10.0.0",
        "eslint-plugin-html": "^2.0.1",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-node": "^4.2.2",
        "eslint-plugin-promise": "^3.5.0",
        "eslint-plugin-standard": "^3.0.1",
        "finalhandler": "^1.0.1",
        "jsdom": "^9.12.0",
        "json-loader": "^0.5.4",
        "nyc": "^10.2.0",
        "request": "^2.81.0",
        "request-promise-native": "^1.0.3",
        "webpack-node-externals": "^1.5.4"
    },
    "directories": {},
    "dist": {
        "shasum": "cdd261e9c234312ebd1dd58384c7c87d5c1bd60a",
        "tarball": "https://registry.npmjs.org/nuxt/-/nuxt-0.10.6.tgz"
    },
    "engines": {
        "node": ">=4.3.0 <5.0.0 || >=5.10",
        "npm": ">=3.0.0"
    },
    "files": [
        "bin",
        "dist",
        "index.js"
    ],
    "gitHead": "854e262445db60f8bfee2483e3e723b7be4dc35a",
    "homepage": "https://github.com/nuxt/nuxt.js#readme",
    "keywords": [
        "nuxt",
        "nuxt.js",
        "nuxtjs",
        "vue",
        "vue.js",
        "vuejs",
        "vue universal",
        "vue ssr",
        "vue isomorphic",
        "vue versatile"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "atinux"
        }
    ],
    "name": "nuxt",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nuxt/nuxt.js.git"
    },
    "scripts": {
        "build": "webpack",
        "coverage": "nyc report --reporter=text-lcov > coverage.lcov && codecov",
        "lint": "eslint --ext .js,.vue bin lib pages test/*.js --ignore-pattern lib/app",
        "precommit": "npm run lint",
        "prepublish": "npm run build",
        "test": "nyc ava --verbose --serial test/",
        "watch": "webpack --watch"
    },
    "version": "0.10.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

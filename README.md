# npmtest-website-scraper

#### basic test coverage for  [website-scraper (v2.3.0)](https://github.com/s0ph1e/node-website-scraper)  [![npm package](https://img.shields.io/npm/v/npmtest-website-scraper.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-website-scraper) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-website-scraper.svg)](https://travis-ci.org/npmtest/node-npmtest-website-scraper)

#### Download website to a local directory (including all css, images, js, etc.)

[![NPM](https://nodei.co/npm/website-scraper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/website-scraper)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-website-scraper/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-website-scraper/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-website-scraper/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-website-scraper/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-website-scraper/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-website-scraper/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-website-scraper/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-website-scraper/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-website-scraper/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-website-scraper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-website-scraper/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-website-scraper/build/test-report.html](https://npmtest.github.io/node-npmtest-website-scraper/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-website-scraper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-website-scraper/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-website-scraper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-website-scraper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-website-scraper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-website-scraper/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-website-scraper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-website-scraper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "website-scraper",
    "version": "2.3.0",
    "description": "Download website to a local directory (including all css, images, js, etc.)",
    "readmeFilename": "README.md",
    "main": "index.js",
    "scripts": {
        "test": "istanbul cover node_modules/mocha/bin/_mocha --dir ./coverage --report lcov -- -R spec --recursive --timeout 7000 ./test/unit/ ./test/functional && npm run eslint",
        "test-e2e": "node_modules/mocha/bin/_mocha --timeout 300000 ./test/e2e/*-test.js",
        "eslint": "eslint lib/** index.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/s0ph1e/node-website-scraper.git"
    },
    "keywords": [
        "scrape",
        "scraper",
        "download",
        "web",
        "url",
        "page",
        "site",
        "html",
        "css",
        "image",
        "js"
    ],
    "author": "Sophia Antipenko <sophia@antipenko.pp.ua>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/s0ph1e/node-website-scraper/issues"
    },
    "homepage": "https://github.com/s0ph1e/node-website-scraper",
    "dependencies": {
        "bluebird": "^3.0.1",
        "cheerio": "0.22.0",
        "css-url-parser": "^1.0.0",
        "debug": "^2.4.5",
        "fs-extra": "^2.0.0",
        "he": "^1.1.0",
        "lodash": "^4.11.1",
        "normalize-url": "^1.5.3",
        "request": "^2.42.0",
        "srcset": "^1.0.0"
    },
    "devDependencies": {
        "codeclimate-test-reporter": "^0.4.0",
        "coveralls": "^2.11.8",
        "eslint": "^3.9.1",
        "istanbul": "^0.4.0",
        "mocha": "^3.0.2",
        "nock": "^9.0.2",
        "proxyquire": "^1.7.3",
        "should": "^11.1.0",
        "sinon": "^2.1.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

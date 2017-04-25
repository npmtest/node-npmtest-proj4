# npmtest-proj4

#### basic test coverage for  [proj4 (v2.4.3)](https://github.com/proj4js/proj4js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-proj4.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-proj4) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-proj4.svg)](https://travis-ci.org/npmtest/node-npmtest-proj4)

#### Proj4js is a JavaScript library to transform point coordinates from one coordinate system to another, including datum transformations.

[![NPM](https://nodei.co/npm/proj4.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/proj4)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-proj4/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-proj4/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-proj4/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-proj4/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-proj4/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-proj4/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-proj4/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-proj4/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-proj4/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-proj4/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-proj4/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-proj4/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-proj4/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-proj4/build/test-report.html](https://npmtest.github.io/node-npmtest-proj4/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-proj4/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-proj4/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-proj4/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-proj4/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-proj4/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-proj4/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-proj4/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-proj4/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bugs": {
        "url": "https://github.com/proj4js/proj4js/issues"
    },
    "contributors": [
        {
            "name": "Mike Adair"
        },
        {
            "name": "Richard Greenwood"
        },
        {
            "name": "Calvin Metcalf"
        },
        {
            "name": "Richard Marsden",
            "url": "http://www.winwaed.com"
        },
        {
            "name": "T. Mittan"
        },
        {
            "name": "D. Steinwand"
        },
        {
            "name": "S. Nelson"
        }
    ],
    "dependencies": {
        "mgrs": "1.0.0",
        "wkt-parser": "^1.1.3"
    },
    "description": "Proj4js is a JavaScript library to transform point coordinates from one coordinate system to another, including datum transformations.",
    "devDependencies": {
        "chai": "~1.8.1",
        "curl": "git://github.com/cujojs/curl.git",
        "grunt": "~0.4.2",
        "grunt-cli": "~0.1.13",
        "grunt-contrib-connect": "~0.6.0",
        "grunt-contrib-jshint": "~1.1.0",
        "grunt-contrib-uglify": "~0.11.1",
        "grunt-mocha-phantomjs": "~0.4.0",
        "grunt-rollup": "^1.0.1",
        "istanbul": "~0.2.4",
        "mocha": "~1.17.1",
        "rollup": "^0.41.4",
        "rollup-plugin-json": "^2.0.1",
        "rollup-plugin-node-resolve": "^2.0.0",
        "tin": "~0.4.0"
    },
    "directories": {
        "test": "test",
        "doc": "docs"
    },
    "dist": {
        "shasum": "f3bb7e631bffc047c36a1a3cc14533a03bbe9969",
        "tarball": "https://registry.npmjs.org/proj4/-/proj4-2.4.3.tgz"
    },
    "gitHead": "e975a5462ad7abb23e33ea75281eb749e77e1510",
    "homepage": "https://github.com/proj4js/proj4js#readme",
    "license": "MIT",
    "main": "dist/proj4-src.js",
    "maintainers": [
        {
            "name": "cwmma"
        },
        {
            "name": "ahocevar"
        }
    ],
    "module": "lib/index.js",
    "name": "proj4",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/proj4js/proj4js.git"
    },
    "scripts": {
        "build": "grunt",
        "build:tmerc": "grunt build:tmerc",
        "test": "npm run build && istanbul test _mocha test/test.js"
    },
    "version": "2.4.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

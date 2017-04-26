# npmtest-generator-wordpress

#### basic test coverage for  [generator-wordpress (v2.0.2)](https://github.com/wesleytodd/YeoPress)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-wordpress.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-wordpress) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-wordpress.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-wordpress)

#### A Yeoman generator for WordPress

[![NPM](https://nodei.co/npm/generator-wordpress.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-wordpress)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-wordpress/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-wordpress/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-wordpress/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-wordpress/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-wordpress/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-generator-wordpress/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-generator-wordpress/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-wordpress/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-wordpress/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-wordpress/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-wordpress/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-wordpress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-wordpress/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-wordpress/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-wordpress/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-wordpress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-wordpress/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-wordpress/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-wordpress/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-wordpress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-wordpress/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-wordpress/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-wordpress/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Wes Todd"
    },
    "bugs": {
        "url": "https://github.com/wesleytodd/YeoPress/issues"
    },
    "dependencies": {
        "chalk": "^0.2.1",
        "mkdirp": "^0.3.5",
        "mysql": "^2.0.1",
        "simple-git": "^0.14.0",
        "wp-util": "^0.1.6",
        "wrench": "^1.4.4",
        "yeoman-generator": "^0.19.2"
    },
    "description": "A Yeoman generator for WordPress",
    "devDependencies": {
        "grunt": "~0.4.1",
        "grunt-contrib-clean": "~0.5.0",
        "grunt-contrib-connect": "~0.5.0",
        "grunt-simple-mocha": "~0.4.0",
        "istanbul": "~0.1.44",
        "mocha": "~1.13.0"
    },
    "directories": {},
    "dist": {
        "shasum": "cf4d1459da53caba8fe8a22bacadf8a15c0d78dc",
        "tarball": "https://registry.npmjs.org/generator-wordpress/-/generator-wordpress-2.0.2.tgz"
    },
    "gitHead": "03dd6adb39f69fdd0c954f98f2399f3138252fe5",
    "homepage": "https://github.com/wesleytodd/YeoPress",
    "keywords": [
        "yeoman-generator",
        "wordpress",
        "yeoman",
        "generator",
        "cli"
    ],
    "license": "BSD",
    "main": "app/index.js",
    "maintainers": [
        {
            "name": "wesleytodd"
        }
    ],
    "name": "generator-wordpress",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/wesleytodd/YeoPress.git"
    },
    "scripts": {
        "test": "node_modules/istanbul/lib/cli.js test node_modules/mocha/bin/_mocha --dir test/coverage"
    },
    "version": "2.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

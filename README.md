# npmtest-medium-editor

#### test coverage for  [medium-editor (v5.23.0)](http://yabwe.github.io/medium-editor/)  [![npm package](https://img.shields.io/npm/v/npmtest-medium-editor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-medium-editor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-medium-editor.svg)](https://travis-ci.org/npmtest/node-npmtest-medium-editor)

#### Medium.com WYSIWYG editor clone.

[![NPM](https://nodei.co/npm/medium-editor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/medium-editor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-medium-editor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-medium-editor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-medium-editor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-medium-editor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-medium-editor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-medium-editor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-medium-editor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-medium-editor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-medium-editor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-medium-editor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-medium-editor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-medium-editor/build/test-report.html](https://npmtest.github.io/node-npmtest-medium-editor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-medium-editor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-medium-editor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-medium-editor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-medium-editor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-medium-editor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-medium-editor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-medium-editor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-medium-editor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Davi Ferreira"
    },
    "bugs": {
        "url": "https://github.com/yabwe/medium-editor/issues"
    },
    "contributors": [
        {
            "name": "Nate Mielnik"
        },
        {
            "name": "Noah Chase"
        },
        {
            "name": "Jeremy Benoist"
        }
    ],
    "dependencies": {},
    "description": "Medium.com WYSIWYG editor clone.",
    "devDependencies": {
        "brfs": "1.4.2",
        "connect": "3.5.0",
        "grunt": "0.4.5",
        "grunt-autoprefixer": "3.0.3",
        "grunt-bump": "0.7.0",
        "grunt-cli": "1.2.0",
        "grunt-contrib-concat": "0.5.1",
        "grunt-contrib-connect": "0.11.2",
        "grunt-contrib-csslint": "0.5.0",
        "grunt-contrib-cssmin": "0.14.0",
        "grunt-contrib-jasmine": "1.0.3",
        "grunt-contrib-jshint": "0.11.3",
        "grunt-contrib-uglify": "0.11.0",
        "grunt-contrib-watch": "0.6.1",
        "grunt-coveralls": "1.0.0",
        "grunt-jscs": "2.6.0",
        "grunt-plato": "1.3.0",
        "grunt-sass": "1.1.0",
        "grunt-saucelabs": "8.6.2",
        "grunt-template-jasmine-istanbul": "0.4.0",
        "jshint-stylish": "2.1.0",
        "load-grunt-tasks": "3.4.0",
        "lodash": "3.10.1",
        "serve-static": "1.11.2",
        "time-grunt": "1.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7d16c15cdf152b95ced2a583bf07203e8539a3c6",
        "tarball": "https://registry.npmjs.org/medium-editor/-/medium-editor-5.23.0.tgz"
    },
    "gitHead": "de9371bad99f69f64edd5c6d5d4edc3c4f74b928",
    "homepage": "http://yabwe.github.io/medium-editor/",
    "keywords": [
        "contenteditable",
        "editor",
        "medium",
        "wysiwyg",
        "rich-text"
    ],
    "license": "MIT",
    "main": "dist/js/medium-editor.js",
    "maintainers": [
        {
            "name": "daviferreira"
        },
        {
            "name": "j0k3r"
        },
        {
            "name": "nchase"
        },
        {
            "name": "nmielnik"
        },
        {
            "name": "orthes"
        },
        {
            "name": "rishijain"
        }
    ],
    "name": "medium-editor",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "http://registry.npmjs.org/"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yabwe/medium-editor.git"
    },
    "scripts": {
        "build": "node node_modules/grunt-cli/bin/grunt",
        "start": "open ./demo/index.html",
        "test": "node node_modules/grunt-cli/bin/grunt test --verbose",
        "test:ci": "node node_modules/grunt-cli/bin/grunt travis --verbose"
    },
    "version": "5.23.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

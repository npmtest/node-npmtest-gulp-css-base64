# test coverage for  [gulp-css-base64 (v1.3.4)](http://github.com/zckrs/gulp-css-base64)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-css-base64.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-css-base64) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-css-base64.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-css-base64)
#### Gulp's task for transform all resources found in a CSS into base64-encoded data URI strings

[![NPM](https://nodei.co/npm/gulp-css-base64.png?downloads=true)](https://www.npmjs.com/package/gulp-css-base64)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-css-base64/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-css-base64/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-css-base64/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-css-base64/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-css-base64/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-css-base64/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-css-base64/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-css-base64/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-gulp-css-base64/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-css-base64/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-gulp-css-base64%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-css-base64/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-css-base64/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-gulp-css-base64%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-css-base64/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-css-base64/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-css-base64/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mehdy Dara",
        "email": "mdara@eleven-labs.com",
        "url": "http://eleven-labs.com/"
    },
    "bugs": {
        "url": "http://github.com/zckrs/gulp-css-base64/issues",
        "email": "mdara@eleven-labs.com"
    },
    "contributors": [
        {
            "name": "Mehdy Dara",
            "email": "mdara@eleven-labs.com",
            "url": "http://eleven-labs.com/"
        },
        {
            "name": "Callum Jefferies",
            "email": "callum.jefferies@gmail.com",
            "url": "http://callumj.uk/"
        }
    ],
    "dependencies": {
        "async": "^1.5.0",
        "buffers": "^0.1.1",
        "chalk": "^1.1.1",
        "gulp-util": "^3.0.3",
        "mime": "^1.3.4",
        "request": "^2.67.0",
        "through2": "^2.0.0"
    },
    "description": "Gulp's task for transform all resources found in a CSS into base64-encoded data URI strings",
    "devDependencies": {
        "coveralls": "^2.11.2",
        "eslint": "^1.10.3",
        "eslint-config-xo-space": "^0.7.0",
        "event-stream": "^3.3.2",
        "istanbul": "^0.4.1",
        "mocha": "^2.3.4",
        "mocha-lcov-reporter": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "afca45e83401045f472c67b776d1b1514e11489f",
        "tarball": "https://registry.npmjs.org/gulp-css-base64/-/gulp-css-base64-1.3.4.tgz"
    },
    "eslintConfig": {
        "extends": "xo-space",
        "env": {
            "mocha": true
        }
    },
    "files": [
        "src"
    ],
    "gitHead": "b63225ede3ed711e579fb0b7ca09ff16ddae6221",
    "homepage": "http://github.com/zckrs/gulp-css-base64",
    "keywords": [
        "gulpplugin",
        "css",
        "base64"
    ],
    "license": "MIT",
    "main": "./src/index.js",
    "maintainers": [
        {
            "name": "zckrs",
            "email": "mdara@eleven-labs.com"
        }
    ],
    "name": "gulp-css-base64",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zckrs/gulp-css-base64.git"
    },
    "scripts": {
        "cover": "istanbul cover ./node_modules/mocha/bin/_mocha --report html -- test/*.js -R spec -t 5000",
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "eslint . && mocha --reporter spec"
    },
    "version": "1.3.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

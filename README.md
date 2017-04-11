# test coverage for  [video.js (v5.19.1)](http://videojs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-video.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-video.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-video.js.svg)](https://travis-ci.org/npmtest/node-npmtest-video.js)
#### An HTML5 and Flash video player with a common API and skin for both.

[![NPM](https://nodei.co/npm/video.js.png?downloads=true)](https://www.npmjs.com/package/video.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-video.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-video.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-video.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-video.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-video.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-video.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-video.js/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-video.js/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-video.js/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-video.js/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-video.js%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-video.js/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-video.js/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-video.js%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-video.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-video.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-video.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Steve Heffernan"
    },
    "bugs": {
        "url": "https://github.com/videojs/video.js/issues"
    },
    "config": {
        "ghooks": {
            "pre-push": "npm run lint -- --errors"
        }
    },
    "copyright": "Copyright Brightcove, Inc. <https://www.brightcove.com/>",
    "dependencies": {
        "babel-runtime": "^6.9.2",
        "global": "4.3.0",
        "safe-json-parse": "4.0.0",
        "tsml": "1.0.1",
        "videojs-font": "2.0.0",
        "videojs-ie8": "1.1.2",
        "videojs-swf": "5.3.0",
        "videojs-vtt.js": "0.12.3",
        "xhr": "2.2.2"
    },
    "description": "An HTML5 and Flash video player with a common API and skin for both.",
    "devDependencies": {
        "aliasify": "^2.1.0",
        "babel-cli": "^6.11.4",
        "babel-plugin-inline-json": "^1.1.1",
        "babel-plugin-transform-es3-member-expression-literals": "^6.8.0",
        "babel-plugin-transform-es3-property-literals": "^6.8.0",
        "babel-plugin-transform-runtime": "^6.9.0",
        "babel-preset-es2015": "^6.14.0",
        "babel-register": "^6.9.0",
        "babelify": "^7.3.0",
        "blanket": "^1.1.6",
        "browserify-derequire": "^0.9.4",
        "browserify-istanbul": "^2.0.0",
        "browserify-versionify": "^1.0.4",
        "bundle-collapser": "^1.2.1",
        "chg": "^0.3.2",
        "conventional-changelog-cli": "^1.2.0",
        "conventional-changelog-videojs": "^3.0.0",
        "es5-shim": "^4.1.3",
        "es6-shim": "^0.35.1",
        "ghooks": "^1.3.2",
        "grunt": "^0.4.5",
        "grunt-accessibility": "^5.0.0",
        "grunt-babel": "^6.0.0",
        "grunt-banner": "^0.6.0",
        "grunt-browserify": "5.0.0",
        "grunt-cli": "~1.2.0",
        "grunt-concurrent": "^2.3.1",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-concat": "^1.0.1",
        "grunt-contrib-connect": "~1.0.2",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-cssmin": "~1.0.2",
        "grunt-contrib-uglify": "^2.0.0",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-coveralls": "^1.0.0",
        "grunt-fastly": "^0.1.3",
        "grunt-github-releaser": "^0.1.17",
        "grunt-karma": "^2.0.0",
        "grunt-sass": "^2.0.0",
        "grunt-shell": "^2.0.0",
        "grunt-version": "~1.1.1",
        "grunt-videojs-languages": "0.0.4",
        "grunt-zip": "0.17.1",
        "istanbul": "^0.4.5",
        "jsdoc": "^3.4.2",
        "karma": "^1.2.0",
        "karma-browserify": "^5.1.0",
        "karma-browserstack-launcher": "^1.0.1",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.1.1",
        "karma-detect-browsers": "~2.2.3",
        "karma-firefox-launcher": "^1.0.0",
        "karma-ie-launcher": "^1.0.0",
        "karma-opera-launcher": "^1.0.0",
        "karma-qunit": "^1.2.0",
        "karma-safari-launcher": "^1.0.0",
        "karma-sinon": "^1.0.5",
        "load-grunt-tasks": "^3.1.0",
        "lodash": "^4.16.6",
        "markdown-table": "^1.0.0",
        "npm-run": "^4.1.0",
        "proxyquireify": "^3.0.0",
        "qunitjs": "1.23.1",
        "remark-cli": "^2.1.0",
        "remark-lint": "^5.2.0",
        "remark-toc": "^3.1.0",
        "remark-validate-links": "^5.0.0",
        "shelljs": "^0.7.5",
        "sinon": "^1.16.1",
        "time-grunt": "^1.1.1",
        "uglify-js": "~2.7.3",
        "videojs-doc-generator": "0.0.1",
        "videojs-standard": "^6.0.1",
        "webpack": "^1.13.2"
    },
    "directories": {},
    "dist": {
        "shasum": "5d6407aebd078bf4c4f94183f840a53388c34f25",
        "tarball": "https://registry.npmjs.org/video.js/-/video.js-5.19.1.tgz"
    },
    "gitHead": "3c77005bec422cb08d5f436ae5f12ca4c7099ee3",
    "homepage": "http://videojs.com",
    "keywords": [
        "flash",
        "html5",
        "player",
        "video",
        "videojs"
    ],
    "license": "Apache-2.0",
    "main": "./es5/video.js",
    "maintainers": [
        {
            "name": "gkatsev",
            "email": "me@gkatsev.com"
        }
    ],
    "name": "video.js",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/videojs/video.js.git"
    },
    "scripts": {
        "babel": "babel src/js -d es5",
        "build": "grunt dist",
        "change": "grunt chg-add",
        "changelog": "conventional-changelog -p videojs -i CHANGELOG.md -s",
        "clean": "grunt clean",
        "docs": "npm run docs:lint && npm run docs:api",
        "docs:api": "jsdoc -r src/js -d docs/api -c .jsdoc.json",
        "docs:fix": "remark --output -- './**/*.md'",
        "docs:lint": "remark -- './**/*.md'",
        "grunt": "grunt",
        "lint": "vjsstandard",
        "start": "grunt dev",
        "test": "grunt test"
    },
    "style": "./dist/video-js.css",
    "version": "5.19.1",
    "vjsstandard": {
        "ignore": [
            "**/Gruntfile.js",
            "**/es5/**",
            "**/build/**",
            "**/dist/**",
            "**/docs/**",
            "**/lang/**",
            "**/sandbox/**",
            "**/test/api/**",
            "**/test/coverage/**",
            "**/test/karma.conf.js"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

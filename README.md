# test coverage for  [karma-jasmine (v1.1.0)](https://github.com/karma-runner/karma-jasmine#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-karma-jasmine.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-karma-jasmine) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-karma-jasmine.svg)](https://travis-ci.org/npmtest/node-npmtest-karma-jasmine)
#### A Karma plugin - adapter for Jasmine testing framework.

[![NPM](https://nodei.co/npm/karma-jasmine.png?downloads=true)](https://www.npmjs.com/package/karma-jasmine)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-karma-jasmine/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-jasmine/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-karma-jasmine/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-karma-jasmine/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-karma-jasmine/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-karma-jasmine/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-karma-jasmine/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-karma-jasmine/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-karma-jasmine/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-karma-jasmine/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-karma-jasmine%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-karma-jasmine/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-jasmine/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-karma-jasmine%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-jasmine/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-karma-jasmine/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-karma-jasmine/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vojta Jina",
        "email": "vojta.jina@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/karma-runner/karma-jasmine/issues"
    },
    "contributors": [
        {
            "name": "Maksim Ryzhikov",
            "email": "rv.maksim@gmail.com"
        },
        {
            "name": "Mark Ethan Trostler",
            "email": "mark@zzo.com"
        },
        {
            "name": "olegskl",
            "email": "sklyanchuk@gmail.com"
        },
        {
            "name": "Friedel Ziegelmayer",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "dignifiedquire",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "Cornelius Schmale",
            "email": "github@cschmale.de"
        },
        {
            "name": "Arthur Thornton",
            "email": "arthur@thestorefront.com"
        },
        {
            "name": "Friedel Ziegelmayer",
            "email": "friedel.ziegelmayer@gmail.com"
        },
        {
            "name": "Richard Park",
            "email": "objectiv@gmail.com"
        },
        {
            "name": "Sergey Tatarintsev",
            "email": "sevinf@yandex-team.ru"
        },
        {
            "name": "Stefan Dragnev",
            "email": "dragnev@telerik.com"
        },
        {
            "name": "jiverson",
            "email": "jiverson222@gmail.com"
        },
        {
            "name": "Aaron Hartwig",
            "email": "aaron.hartwig@whyhigh.com"
        },
        {
            "name": "rpark",
            "email": "objectiv@gmail.com"
        },
        {
            "name": "Alesei N",
            "email": "github.com@bzik.net"
        },
        {
            "name": "Barry Fitzgerald",
            "email": "barfitzgerald@gmail.com"
        },
        {
            "name": "Georgii Dolzhykov",
            "email": "thorn.mailbox@gmail.com"
        },
        {
            "name": "Marek Vavrecan",
            "email": "vavrecan@gmail.com"
        },
        {
            "name": "Matthew Hill",
            "email": "Matthew.Hill4@bskyb.com"
        },
        {
            "name": "Milan Lempera",
            "email": "milanlempera@gmail.com"
        },
        {
            "name": "Niels Dequeker",
            "email": "niels.dequeker@gmail.com"
        },
        {
            "name": "Robin Gloster",
            "email": "robin@loc-com.de"
        },
        {
            "name": "Sahat Yalkabov",
            "email": "sakhat@gmail.com"
        }
    ],
    "dependencies": {},
    "description": "A Karma plugin - adapter for Jasmine testing framework.",
    "devDependencies": {
        "eslint-config-standard": "^5.1.0",
        "eslint-plugin-promise": "^1.1.0",
        "eslint-plugin-standard": "^1.3.2",
        "grunt": "~1.0.1",
        "grunt-bump": "^0.8.0",
        "grunt-conventional-changelog": "^6.1.0",
        "grunt-conventional-github-releaser": "^1.0.0",
        "grunt-eslint": "^18.0.0",
        "grunt-karma": "2.x",
        "grunt-npm": "0.0.2",
        "jasmine-core": "~2.4.1",
        "karma": "1.x || ",
        "karma-chrome-launcher": "1.x || ~0.2.2",
        "karma-firefox-launcher": "1.x || ~0.1.7",
        "load-grunt-tasks": "^3.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "22e4c06bf9a182e5294d1f705e3733811b810acf",
        "tarball": "https://registry.npmjs.org/karma-jasmine/-/karma-jasmine-1.1.0.tgz"
    },
    "gitHead": "fe23ac73b9082bae25dc821ea2ddc00c8bf16db2",
    "homepage": "https://github.com/karma-runner/karma-jasmine#readme",
    "keywords": [
        "karma-plugin",
        "karma-adapter",
        "jasmine"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "vojtajina",
            "email": "vojta.jina+npm@gmail.com"
        },
        {
            "name": "maksimr",
            "email": "rv.maksim@gmail.com"
        },
        {
            "name": "zzo",
            "email": "mark@zzo.com"
        },
        {
            "name": "dignifiedquire",
            "email": "dignifiedquire@gmail.com"
        },
        {
            "name": "karmarunnerbot",
            "email": "karmarunnerbot@gmail.com"
        }
    ],
    "name": "karma-jasmine",
    "optionalDependencies": {},
    "peerDependencies": {
        "jasmine-core": "*",
        "karma": "*"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/karma-runner/karma-jasmine.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

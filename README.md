# test coverage for  [strider (v1.9.6)](https://github.com/Strider-CD/strider#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-strider.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-strider) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-strider.svg)](https://travis-ci.org/npmtest/node-npmtest-strider)
#### Brilliant continuous deployment platform

[![NPM](https://nodei.co/npm/strider.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/strider)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-strider/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-strider/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-strider/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-strider/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-strider/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-strider/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-strider/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-strider/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-strider/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-strider/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-strider/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-strider/build/test-report.html](https://npmtest.github.io/node-npmtest-strider/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-strider/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-strider/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-strider/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-strider/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-strider/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-strider/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-strider/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-strider/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "strider": "bin/strider"
    },
    "browser": {
        "bootstrap": "./vendor/bootstrap/js/bootstrap.js",
        "sortable": "./vendor/Sortable/js/Sortable.js",
        "bootbox": "./vendor/bootbox/js/bootbox.js",
        "codemirror": "./vendor/CodeMirror/js/codemirror.js",
        "codemirror-shell": "./vendor/CodeMirror/js/shell.js",
        "timeago": "./vendor/jquery-timeago/js/jquery.timeago.js",
        "ui-codemirror": "./public/libs/ui-codemirror.js",
        "ui-bootstrap": "./public/libs/ui-bootstrap.js"
    },
    "browserify": {
        "transform": [
            "browserify-shim"
        ]
    },
    "browserify-shim": "./shim.js",
    "bugs": {
        "url": "https://github.com/Strider-CD/strider/issues"
    },
    "dependencies": {
        "activedirectory": "^0.7.2",
        "ansi_up": "^1.3.0",
        "async": "^2.0.1",
        "bcryptjs": "^2.1.0",
        "bluebird": "^3.4.1",
        "body-parser": "^1.10.0",
        "chalk": "^1.1.3",
        "co-router": "^1.0.3",
        "compression": "^1.2.2",
        "connect-flash": "^0.1.1",
        "connect-mongo": "^1.3.2",
        "connect-slashes": "^1.3.1",
        "cookie-parser": "^1.3.3",
        "cors": "^2.5.2",
        "debug": "^2.2.0",
        "errorhandler": "^1.3.0",
        "everypaas": "0.0.8",
        "express": "^4.10.6",
        "express-session": "^1.9.3",
        "global-tunnel": "^1.2.0",
        "gravatar": "^1.1.0",
        "in-publish": "^2.0.0",
        "lodash": "^4.14.0",
        "md5": "^2.0.0",
        "method-override": "^2.3.0",
        "mongoose": "^4.7.6",
        "morgan-debug": "^1.0.0",
        "node-rsa": "^0.4.0",
        "passport": "^0.3.2",
        "passport-local": "^1.0.0",
        "path-to-regexp": "^1.0.2",
        "pug": "^2.0.0-beta4",
        "rc": "^1.0.3",
        "request": "^2.49.0",
        "semver": "^5.3.0",
        "serve-favicon": "^2.2.0",
        "socket.io": "^1.2.1",
        "socket.io-client": "^1.0.6",
        "sshpk": "^1.8.3",
        "step": "^0.0.6",
        "strider-bitbucket": "^1.2.0",
        "strider-build-badge": "^0",
        "strider-cli": "^2.0.0",
        "strider-custom": "^0.6.0",
        "strider-ecosystem-client": "^1.2.1",
        "strider-email-notifier": "^1.0.0",
        "strider-env": "^0.5.1",
        "strider-extension-loader": "^0.4.5",
        "strider-git": "^1.0.0",
        "strider-github": "^2.3.0",
        "strider-gitlab": "^1.2.3",
        "strider-heroku": "^0.1.1",
        "strider-mailer": "^0.2.0",
        "strider-metadata": "^0.0.3",
        "strider-node": "^1.0.0",
        "strider-python": "^0.2.1",
        "strider-ruby": "^0.0.2",
        "strider-simple-runner": "^1.0.0",
        "strider-slack": "^2.0.0",
        "strider-ssh-deploy": "^1.0.0",
        "swig": "^0.14.0",
        "thirty-two": "^1.0.1",
        "validator": "^5.5.0",
        "winston": "^2.2.0"
    },
    "description": "Brilliant continuous deployment platform",
    "devDependencies": {
        "angular": "1.5.7",
        "angular-route": "1.5.7",
        "apidoc": "^0.16.1",
        "apidoc-markdown": "github:zambonilli/node-apidoc-markdown",
        "babel-preset-es2015": "^6.9.0",
        "babelify": "^7.3.0",
        "bower-installer": "^1.2.0",
        "browserify": "^13.0.1",
        "browserify-shim": "^3.8.0",
        "chai": "^3.5.0",
        "chai-as-promised": "^5.3.0",
        "docpress": "0.7.1",
        "eslint": "^3.0.1",
        "expect.js": "^0.3.1",
        "git-update-ghpages": "^1.3.0",
        "httpcheck": "^0.3.0",
        "istanbul": "^0.4.4",
        "jquery": "^2.2.4",
        "less": "^2.2.0",
        "minifyify": "^7.3.3",
        "mkdirp": "^0.5.0",
        "mocha": "^3.0.0",
        "node-mocks-http": "^1.2.4",
        "sinon": "^1.10.3",
        "standard-version": "^4.0.0",
        "surge": "^0.18.0",
        "watchify": "^3.4.0",
        "wd": "^0.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5bb821f5d266285ff5f09f803bd71e8fdbd3c22d",
        "tarball": "https://registry.npmjs.org/strider/-/strider-1.9.6.tgz"
    },
    "engines": {
        "node": ">=4.2",
        "npm": ">=2.0.0"
    },
    "gitHead": "9bb19dc4f3e6c7f6ed12a01d8fa29bab97c5f455",
    "homepage": "https://github.com/Strider-CD/strider#readme",
    "keywords": [
        "strider",
        "continuous integration",
        "continuous deployment",
        "testing",
        "deployment"
    ],
    "license": "BSD-3-Clause",
    "main": "main.js",
    "maintainers": [
        {
            "name": "niallo"
        },
        {
            "name": "peterbraden"
        },
        {
            "name": "knownasilya"
        }
    ],
    "name": "strider",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Strider-CD/strider.git"
    },
    "scripts": {
        "api-docs": "apidoc -i lib/ -o apidocs/",
        "api-docs:md": "apidoc-markdown -p apidocs -o docs/api.md",
        "build": "npm run pre && npm run styles && browserify -d -t [babelify --presets [ es2015 ] --only client] -p [minifyify --output dist/scripts/bundle.map] -e client/app.js -o dist/scripts/app.js",
        "build-debug": "npm run pre && npm run styles-debug && browserify -d -t [babelify --presets [ es2015 ] --only client] -e client/app.js -o dist/scripts/app.js",
        "debug": "node debug bin/strider --no-cluster",
        "deploy:docs": "npm run api-docs:md && npm run docs:build && npm run docs:publish",
        "dev": "npm run build-debug && bin/strider",
        "docs:build": "docpress b",
        "docs:publish": "git-update-ghpages -b master Strider-CD/strider-cd.github.com _docpress",
        "lint": "eslint *.js bin lib client",
        "pre": "mkdirp dist/scripts dist/styles",
        "prepublish": "in-publish && npm run build || not-in-publish",
        "release": "standard-version",
        "start": "bin/strider",
        "styles": "lessc client/styles/strider.less > dist/styles/styles.css",
        "styles-debug": "lessc --source-map client/styles/strider.less dist/styles/styles.css",
        "test": "npm run build && npm run lint && npm run test-unit",
        "test-unit": "mocha --recursive test/unit",
        "unitcov": "istanbul cover ./node_modules/mocha/bin/_mocha --recursive test/unit",
        "vendor": "bower-installer",
        "watch": "npm run pre && watchify -e client/app.js -o dist/scripts/app.js"
    },
    "version": "1.9.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

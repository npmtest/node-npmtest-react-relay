# npmtest-react-relay

#### basic test coverage for  [react-relay (v0.10.0)](https://facebook.github.io/relay/)  [![npm package](https://img.shields.io/npm/v/npmtest-react-relay.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-relay) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-relay.svg)](https://travis-ci.org/npmtest/node-npmtest-react-relay)

#### A framework for building data-driven React applications.

[![NPM](https://nodei.co/npm/react-relay.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-relay)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-relay/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-relay/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-relay/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-relay/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-relay/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-relay/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-relay/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-relay/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-relay/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-relay/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-relay/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-relay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-relay/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-relay/build/test-report.html](https://npmtest.github.io/node-npmtest-react-relay/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-relay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-relay/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-relay/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-relay/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-relay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-relay/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-relay/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-relay/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/facebook/relay/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.6.1",
        "fbjs": "^0.8.1",
        "react-static-container": "^1.0.1"
    },
    "description": "A framework for building data-driven React applications.",
    "devDependencies": {
        "babel-cli": "^6.9.0",
        "babel-core": "^6.9.0",
        "babel-eslint": "^6.1.2",
        "babel-plugin-transform-runtime": "^6.9.0",
        "babel-polyfill": "^6.9.0",
        "babel-preset-fbjs": "^2.0.0",
        "del": "^2.2.0",
        "eslint": "^3.0.1",
        "eslint-config-fbjs": "^1.0.0",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-flow-vars": "^0.4.0",
        "eslint-plugin-react": "^5.2.2",
        "fbjs-scripts": "^0.7.1",
        "flow-bin": "^0.36.0",
        "graphql": "0.6.0",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-derequire": "^2.1.0",
        "gulp-flatten": "^0.3.0",
        "gulp-header": "1.8.7",
        "gulp-util": "^3.0.7",
        "jest": "^17.0.3",
        "object-assign": "^4.1.0",
        "react": "^15.1.0",
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.1.0",
        "react-test-renderer": "^15.1.0",
        "run-sequence": "^1.2.1",
        "webpack": "^1.13.1",
        "webpack-stream": "^3.2.0"
    },
    "devEngines": {
        "node": ">=4.x",
        "npm": ">=2.x"
    },
    "directories": {},
    "dist": {
        "shasum": "4b19c4450e0140b9f04fd6fe96d8f451f0804078",
        "tarball": "https://registry.npmjs.org/react-relay/-/react-relay-0.10.0.tgz"
    },
    "files": [
        "LICENSE",
        "PATENTS",
        "README.md",
        "dist/",
        "lib/"
    ],
    "gitHead": "cb23da262cc03118281c7fde12bc905e955ef321",
    "homepage": "https://facebook.github.io/relay/",
    "jest": {
        "rootDir": "",
        "setupFiles": [
            "node_modules/fbjs-scripts/jest/environment.js"
        ],
        "transform": {
            ".*": "scripts/jest/preprocessor.js"
        },
        "transformIgnorePatterns": [
            "<rootDir>/node_modules/"
        ],
        "automock": true,
        "modulePathIgnorePatterns": [
            "<rootDir>/lib/",
            "<rootDir>/src/(.*).native.js",
            "<rootDir>/node_modules/(?!(fbjs/lib/|react/lib/|fbjs-scripts/jest))"
        ],
        "testPathDirs": [
            "<rootDir>/node_modules/fbjs/lib/",
            "<rootDir>/node_modules/fbjs-scripts/jest",
            "<rootDir>/node_modules/react/lib/",
            "<rootDir>/node_modules/react-static-container/lib/",
            "<rootDir>/src/"
        ],
        "unmockedModulePathPatterns": [
            "<rootDir>/node_modules/fbjs-scripts/",
            "<rootDir>/node_modules/fbjs/node_modules/core-js/",
            "<rootDir>/node_modules/fbjs/node_modules/promise/",
            "<rootDir>/node_modules/fbjs/lib/(?!(ErrorUtils.js$|fetch.js$|fetchWithRetries.js$))",
            "<rootDir>/node_modules/object-assign/",
            "<rootDir>/node_modules/react/",
            "<rootDir>/node_modules/react-addons-test-utils/",
            "<rootDir>/node_modules/react-dom/",
            "<rootDir>/node_modules/react-static-container/"
        ]
    },
    "keywords": [
        "graphql",
        "react",
        "relay"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/Relay.js",
    "maintainers": [
        {
            "name": "fb"
        },
        {
            "name": "josephsavona"
        },
        {
            "name": "kassens"
        },
        {
            "name": "steveluscher"
        },
        {
            "name": "wincent"
        },
        {
            "name": "yungsters"
        },
        {
            "name": "yuzhi"
        },
        {
            "name": "zpao"
        }
    ],
    "name": "react-relay",
    "optionalDependencies": {},
    "peerDependencies": {
        "babel-relay-plugin": "0.10.0",
        "react": "^15.0.0 || ^0.14.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/facebook/relay.git"
    },
    "scripts": {
        "build": "gulp",
        "jest": "NODE_ENV=test jest \"$@\"",
        "lint": "eslint .",
        "prepublish": "node node_modules/fbjs-scripts/node/check-dev-engines.js package.json && npm run build",
        "test": "f() { EXIT=0; npm run typecheck || EXIT=$?; npm run jest \"$@\" || EXIT=$?; exit $EXIT; }; f",
        "typecheck": "flow check src/",
        "update-schema": "babel-node ./scripts/jest/updateSchema.js"
    },
    "version": "0.10.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

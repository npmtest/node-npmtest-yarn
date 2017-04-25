# npmtest-yarn

#### basic test coverage for  yarn (v0.23.2)  [![npm package](https://img.shields.io/npm/v/npmtest-yarn.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-yarn) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-yarn.svg)](https://travis-ci.org/npmtest/node-npmtest-yarn)

#### 📦🐈 Fast, reliable, and secure dependency management.

[![NPM](https://nodei.co/npm/yarn.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yarn)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-yarn/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-yarn/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-yarn/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-yarn/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-yarn/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-yarn/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-yarn/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-yarn/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-yarn/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-yarn/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-yarn/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-yarn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-yarn/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-yarn/build/test-report.html](https://npmtest.github.io/node-npmtest-yarn/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-yarn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-yarn/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-yarn/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yarn/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yarn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yarn/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-yarn/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-yarn/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "yarn",
    "installationMethod": "npm",
    "version": "0.23.2",
    "license": "BSD-2-Clause",
    "preferGlobal": true,
    "description": "📦🐈 Fast, reliable, and secure dependency management.",
    "dependencies": {
        "babel-runtime": "^6.0.0",
        "bytes": "^2.4.0",
        "camelcase": "^4.0.0",
        "chalk": "^1.1.1",
        "cmd-shim": "^2.0.1",
        "commander": "^2.9.0",
        "death": "^1.0.0",
        "debug": "^2.2.0",
        "detect-indent": "^5.0.0",
        "ini": "^1.3.4",
        "inquirer": "^3.0.1",
        "invariant": "^2.2.0",
        "is-builtin-module": "^1.0.0",
        "is-ci": "^1.0.10",
        "leven": "^2.0.0",
        "loud-rejection": "^1.2.0",
        "minimatch": "^3.0.3",
        "mkdirp": "^0.5.1",
        "node-emoji": "^1.0.4",
        "node-gyp": "^3.2.1",
        "object-path": "^0.11.2",
        "proper-lockfile": "^2.0.0",
        "read": "^1.0.7",
        "request": "^2.81.0",
        "request-capture-har": "^1.2.2",
        "rimraf": "^2.5.0",
        "roadrunner": "^1.1.0",
        "semver": "^5.1.0",
        "strip-bom": "^3.0.0",
        "tar-fs": "^1.15.1",
        "tar-stream": "^1.5.2",
        "v8-compile-cache": "^1.1.0",
        "validate-npm-package-license": "^3.0.1"
    },
    "devDependencies": {
        "babel-core": "^6.17.0",
        "babel-eslint": "^6.1.2",
        "babel-jest": "^19.0.0",
        "babel-loader": "^6.2.5",
        "babel-plugin-transform-es2015-typeof-symbol": "^6.8.0",
        "babel-plugin-transform-inline-imports-commonjs": "^1.0.0",
        "babel-plugin-transform-runtime": "^6.4.3",
        "babel-preset-es2015-node4": "^2.1.0",
        "babel-preset-node5": "^10.2.0",
        "babel-preset-stage-0": "^6.0.0",
        "babylon": "^6.5.0",
        "eslint": "^3.3.1",
        "eslint-config-fb-strict": "^14.1.3",
        "eslint-config-fbjs": "^1.0.0",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-flowtype": "^2.15.0",
        "eslint-plugin-no-async-without-await": "^1.0.0",
        "eslint-plugin-react": "5.2.2",
        "eslint-plugin-yarn-internal": "file:scripts/eslint-rules",
        "flow-bin": "^0.43.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.0.0",
        "gulp-if": "^2.0.1",
        "gulp-newer": "^1.0.0",
        "gulp-plumber": "^1.0.1",
        "gulp-sourcemaps": "^2.2.0",
        "gulp-util": "^3.0.7",
        "gulp-watch": "^4.3.5",
        "jest": "^19.0.2",
        "mock-stdin": "^0.3.0",
        "temp": "^0.8.3",
        "webpack": "^2.1.0-beta.25",
        "yargs": "^6.3.0"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "repository": "yarnpkg/yarn",
    "bin": {
        "yarn": "./bin/yarn.js",
        "yarnpkg": "./bin/yarn.js"
    },
    "scripts": {
        "test": "npm run lint && npm run test-only",
        "test-ci": "npm run build && npm run test-only",
        "check-lockfile": "./scripts/check-lockfile.sh",
        "build": "gulp build",
        "watch": "gulp watch",
        "test-only": "jest --coverage --verbose",
        "lint": "eslint . && flow check",
        "release-branch": "./scripts/release-branch.sh",
        "build-dist": "./scripts/build-dist.sh",
        "build-chocolatey": "powershell ./scripts/build-chocolatey.ps1",
        "build-win-installer": "scripts\\build-windows-installer.bat"
    },
    "jest": {
        "collectCoverageFrom": [
            "src/**/*.js"
        ],
        "timers": "fake",
        "testEnvironment": "node",
        "modulePathIgnorePatterns": [
            "__tests__/fixtures/"
        ],
        "testPathIgnorePatterns": [
            "__tests__/(fixtures|__mocks__)/",
            "updates/",
            "/_(temp|mock|install|init|helpers).js$"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

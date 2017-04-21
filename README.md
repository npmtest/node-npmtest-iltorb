# npmtest-iltorb

#### basic test coverage for  [iltorb (v1.2.1)](https://github.com/MayhemYDG/iltorb)  [![npm package](https://img.shields.io/npm/v/npmtest-iltorb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-iltorb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-iltorb.svg)](https://travis-ci.org/npmtest/node-npmtest-iltorb)

#### Brotli compression/decompression with native bindings

[![NPM](https://nodei.co/npm/iltorb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/iltorb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-iltorb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-iltorb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-iltorb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-iltorb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-iltorb/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-iltorb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-iltorb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-iltorb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-iltorb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-iltorb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-iltorb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-iltorb/build/test-report.html](https://npmtest.github.io/node-npmtest-iltorb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-iltorb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-iltorb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-iltorb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-iltorb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-iltorb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-iltorb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-iltorb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-iltorb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "binary": {
        "module_name": "encode",
        "module_path": "./build/bindings",
        "remote_path": "./{name}/v{version}/{toolset}/",
        "package_name": "{node_abi}-{platform}-{arch}.tar.gz",
        "host": "https://node-iltorb.s3.amazonaws.com"
    },
    "bugs": {
        "url": "https://github.com/MayhemYDG/iltorb/issues"
    },
    "bundleDependencies": [
        "node-pre-gyp"
    ],
    "contributors": [
        {
            "name": "Nicolas Stepien"
        },
        {
            "name": "Hung Tran"
        }
    ],
    "dependencies": {
        "nan": "^2.6.1",
        "node-pre-gyp": "^0.6.34"
    },
    "description": "Brotli compression/decompression with native bindings",
    "devDependencies": {
        "aws-sdk": "^2.39.0",
        "chai": "^3.5.0",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "86a7c9245f06c51a8bf782f46194d8fb260c2e71",
        "tarball": "https://registry.npmjs.org/iltorb/-/iltorb-1.2.1.tgz"
    },
    "files": [
        "brotli/common",
        "brotli/dec",
        "brotli/enc",
        "src",
        "binding.gyp",
        "index.js"
    ],
    "gitHead": "d5d1a2ae90f24ae2e66c0d789ba3167b4332cde5",
    "homepage": "https://github.com/MayhemYDG/iltorb",
    "keywords": [
        "brotli",
        "compression",
        "decompression"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mayhem"
        },
        {
            "name": "oohnoitz"
        }
    ],
    "name": "iltorb",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mayhemydg/iltorb.git"
    },
    "scripts": {
        "build": "npm install --build-from-source",
        "install": "node-pre-gyp install --fallback-to-build",
        "prepublish": "npm ls",
        "test": "mocha"
    },
    "version": "1.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

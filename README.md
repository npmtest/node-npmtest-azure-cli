# npmtest-azure-cli

#### test coverage for  [azure-cli (v0.10.12)](https://github.com/Azure/azure-xplat-cli)  [![npm package](https://img.shields.io/npm/v/npmtest-azure-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-azure-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-azure-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-azure-cli)

#### Microsoft Azure Cross Platform Command Line tool

[![NPM](https://nodei.co/npm/azure-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/azure-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-azure-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-azure-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-azure-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-azure-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-azure-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-azure-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-azure-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-azure-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-azure-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-azure-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-azure-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-azure-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-azure-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-azure-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-azure-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-azure-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-azure-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-azure-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-azure-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-azure-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-azure-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Microsoft Corporation"
    },
    "bin": {
        "azure": "./bin/azure"
    },
    "bugs": {
        "url": "https://github.com/Azure/azure-xplat-cli/issues"
    },
    "contributors": [
        {
            "name": "Block, Glenn"
        },
        {
            "name": "Cowlishaw, Mark"
        },
        {
            "name": "Dejardin, Louis"
        },
        {
            "name": "Georgiev, Yavor"
        },
        {
            "name": "Janczuk, Tomasz"
        },
        {
            "name": "Rodrigues, Andre"
        },
        {
            "name": "Tavares, Chris"
        },
        {
            "name": "Zavery, Amar"
        },
        {
            "name": "Wang, Yugang"
        },
        {
            "name": "Chen, Hao"
        },
        {
            "name": "Krishnan, Balaji"
        }
    ],
    "dependencies": {
        "adal-node": "0.1.21",
        "applicationinsights": "0.16.0",
        "async": "1.4.2",
        "azure-arm-authorization": "2.0.0",
        "azure-arm-batch": "0.3.0",
        "azure-arm-cdn": "1.0.3",
        "azure-arm-commerce": "0.2.0",
        "azure-arm-compute": "0.20.0",
        "azure-arm-datalake-analytics": "1.0.1-preview",
        "azure-arm-datalake-store": "1.0.1-preview",
        "azure-arm-devtestlabs": "0.1.0",
        "azure-arm-dns": "0.11.1",
        "azure-arm-hdinsight": "0.2.2",
        "azure-arm-hdinsight-jobs": "0.1.0",
        "azure-arm-insights": "0.11.3",
        "azure-arm-iothub": "0.1.4",
        "azure-arm-network": "0.18.0",
        "azure-arm-powerbiembedded": "0.1.0",
        "azure-arm-rediscache": "0.2.3",
        "azure-arm-resource": "1.6.1-preview",
        "azure-arm-servermanagement": "0.1.2",
        "azure-arm-storage": "0.15.0-preview",
        "azure-arm-trafficmanager": "0.12.0",
        "azure-arm-website": "0.11.4",
        "azure-asm-compute": "0.18.0",
        "azure-asm-hdinsight": "0.10.2",
        "azure-asm-mgmt": "0.10.1",
        "azure-asm-network": "0.13.0",
        "azure-asm-sb": "0.10.1",
        "azure-asm-sql": "0.10.1",
        "azure-asm-storage": "0.12.0",
        "azure-asm-subscription": "0.10.1",
        "azure-asm-trafficmanager": "0.10.3",
        "azure-asm-website": "0.10.4",
        "azure-batch": "0.5.2",
        "azure-common": "0.9.18",
        "azure-gallery": "2.0.0-pre.18",
        "azure-graph": "1.1.1",
        "azure-keyvault": "0.11.0",
        "azure-monitoring": "0.10.2",
        "azure-servicefabric": "0.1.5",
        "azure-storage": "2.1.0",
        "caller-id": "0.1.x",
        "colors": "1.1.2",
        "commander": "1.0.4",
        "date-utils": "1.2.21",
        "easy-table": "0.0.1",
        "event-stream": "3.1.5",
        "eyes": "0.x.x",
        "fast-json-patch": "0.5.6",
        "github": "0.1.6",
        "js2xmlparser": "1.0.0",
        "jsonlint": "1.6.2",
        "jsonminify": "^0.4.1",
        "jsrsasign": "4.8.2 ",
        "jwt-decode": "^2.1.0",
        "kuduscript": "1.0.13",
        "moment": "^2.8.0",
        "ms-rest": "^1.15.7",
        "ms-rest-azure": "^1.15.7",
        "node-forge": "0.6.23",
        "omelette": "0.3.2",
        "openssl-wrapper": "0.2.1",
        "progress": "^1.1.8",
        "prompt": "0.2.14",
        "read": "^1.0.7",
        "readable-stream": "~1.0.0",
        "request": "2.74.0",
        "ssh-key-to-pem": "0.11.0",
        "streamline": "0.10.17",
        "streamline-streams": "0.1.5",
        "sync-request": "3.0.0",
        "through": "2.3.4",
        "tunnel": "0.0.2",
        "underscore": "1.4.x",
        "user-home": "^2.0.0",
        "uuid": "^3.0.0",
        "validator": "5.2.0",
        "winston": "2.1.1",
        "wordwrap": "0.0.2",
        "xml2js": "0.1.x",
        "xmlbuilder": "0.4.x"
    },
    "description": "Microsoft Azure Cross Platform Command Line tool",
    "devDependencies": {
        "istanbul": "0.3.19",
        "jshint": "<= 2.6.0",
        "mocha": "1.16.0",
        "nock": "0.16",
        "should": "3.3.2",
        "sinon": "^2.1.0",
        "winston-memory": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "4446af5df8dda6c755a0bf7dfec2468a9f63f26d",
        "tarball": "https://registry.npmjs.org/azure-cli/-/azure-cli-0.10.12.tgz"
    },
    "gitHead": "2cfb089012f42834e6d90727d1bba7b975add167",
    "homepage": "https://github.com/Azure/azure-xplat-cli",
    "keywords": [
        "node",
        "azure",
        "cli",
        "cloud hosting",
        "deployment"
    ],
    "license": "Apache-2.0",
    "main": "./lib/cli.js",
    "maintainers": [
        {
            "name": "windowsazure"
        }
    ],
    "name": "azure-cli",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/Azure/azure-xplat-cli.git"
    },
    "scripts": {
        "ci": "node scripts/unit.js testlist.txt -xunit",
        "cover": "istanbul cover ./node_modules/mocha/bin/_mocha -- test/util/profile test/util/authentication -R spec -t 5000",
        "extract-labels": "node scripts/extract-labels",
        "jshint": "jshint lib --jslint-reporter --extra-ext ._js",
        "preci": "jshint lib --reporter=checkstyle --extra-ext ._js > checkstyle-result.xml",
        "test": "npm -s run-script jshint && npm -s run-script unit-arm && npm -s run-script unit",
        "unit": "node scripts/unit.js testlist.txt",
        "unit-arm": "node scripts/unit.js testlist-arm.txt",
        "unit-arm-availset": "node scripts/unit.js testlist-arm-availset.txt",
        "unit-arm-container": "node scripts/unit.js testlist-arm-container.txt",
        "unit-arm-diskvm": "node scripts/unit.js testlist-arm-diskvm.txt",
        "unit-arm-keyvault-live": "node scripts/unit.js testlist-arm-keyvault-live.txt",
        "unit-arm-vm": "node scripts/unit.js testlist-arm-vm.txt",
        "unit-arm-vm-disk": "node scripts/unit.js testlist-arm-vm-disk.txt",
        "unit-arm-vm-extension-live": "node scripts/unit.js testlist-arm-vm-extension-live.txt",
        "unit-arm-vm-live": "node scripts/unit.js testlist-arm-vm-live.txt",
        "unit-arm-vm-ping": "node scripts/unit.js testlist-arm-vm-ping.txt",
        "unit-arm-vm-snapshot": "node scripts/unit.js testlist-arm-vm-snapshot.txt",
        "unit-arm-vmss": "node scripts/unit.js testlist-arm-vmss.txt",
        "unit-vm": "node scripts/unit.js testlist-vm.txt",
        "unit-vm-live": "node scripts/unit.js testlist-vm-live.txt"
    },
    "tags": [
        "azure",
        "cli"
    ],
    "version": "0.10.12"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

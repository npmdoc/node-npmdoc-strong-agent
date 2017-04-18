# npmdoc-strong-agent

#### api documentation for  [strong-agent (v2.1.2)](http://strongloop.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-strong-agent.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-strong-agent) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-strong-agent.svg)](https://travis-ci.org/npmdoc/node-npmdoc-strong-agent)

#### StrongOps Application Performance Monitoring Agent

[![NPM](https://nodei.co/npm/strong-agent.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/strong-agent)

- [https://npmdoc.github.io/node-npmdoc-strong-agent/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-strong-agent/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-strong-agent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-strong-agent/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-strong-agent/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-strong-agent/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "StrongLoop"
    },
    "bugs": {
        "url": "https://github.com/strongloop/strong-agent/issues"
    },
    "contributors": [],
    "dependencies": {
        "debug": "^2.0.0",
        "promise-polyfill": "^5.2.1",
        "semver": "~2.2.1",
        "strong-license": "^1.2.0"
    },
    "description": "StrongOps Application Performance Monitoring Agent",
    "devDependencies": {
        "async": "~0.9.0",
        "bluebird": "^2.10.0",
        "express": "~3.3.5",
        "loopback": "^2.21.0",
        "loopback-connector-postgresql": "^2.3.0",
        "loopback-datasource-juggler": "^2.36.0",
        "memcache": "latest",
        "memcached": "latest",
        "mongodb": "latest",
        "mysql": "^2.7.0",
        "optional-dev-dependency": "1.3.0",
        "pg": "latest",
        "redis": "^2",
        "strong-express-metrics": "^1.0.1",
        "tap": "^0.4.13"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "48b0e67536836ecd0b2fd51ccfc84d2bd870a242",
        "tarball": "https://registry.npmjs.org/strong-agent/-/strong-agent-2.1.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "4b9dde08b79bd4c5a99fb9a00ade93c280981f41",
    "homepage": "http://strongloop.com",
    "keywords": [
        "apm",
        "monitoring",
        "performance",
        "profiling",
        "heap",
        "event loop",
        "analytics",
        "metrics",
        "alerts",
        "profiler",
        "response",
        "time",
        "memory",
        "slowest functions"
    ],
    "license": "SEE LICENSE IN LICENSE.md",
    "main": "lib/main",
    "maintainers": [
        {
            "name": "bajtos"
        },
        {
            "name": "bnoordhuis"
        },
        {
            "name": "chandadharap"
        },
        {
            "name": "ibmcloud-admin"
        },
        {
            "name": "kraman"
        },
        {
            "name": "nodefly"
        },
        {
            "name": "octet"
        },
        {
            "name": "rfeng"
        },
        {
            "name": "ritch"
        },
        {
            "name": "rmg"
        },
        {
            "name": "setogit"
        },
        {
            "name": "strongloop"
        },
        {
            "name": "superkhau"
        }
    ],
    "name": "strong-agent",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/strongloop/strong-agent.git"
    },
    "scripts": {
        "clang-format": "make clang-format",
        "install": "node-gyp rebuild || exit 0",
        "lint": "make -C src lint",
        "pretest": "optional-dev-dependency oracledb strong-oracle",
        "tap": "tap --tap --gc --stderr --timeout 30 test/test-*.js",
        "test": "npm run-script tap"
    },
    "version": "2.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

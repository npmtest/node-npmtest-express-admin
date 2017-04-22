# npmtest-express-admin

#### basic test coverage for  [express-admin (v1.3.0)](https://github.com/simov/express-admin)  [![npm package](https://img.shields.io/npm/v/npmtest-express-admin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-admin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-admin.svg)](https://travis-ci.org/npmtest/node-npmtest-express-admin)

#### MySql, MariaDB, SQLite and PostgreSQL database admin built with Express and Bootstrap

[![NPM](https://nodei.co/npm/express-admin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-admin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-admin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-admin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-admin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-admin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-admin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-admin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-admin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-admin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-admin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-admin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-admin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-admin/build/test-report.html](https://npmtest.github.io/node-npmtest-express-admin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-admin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-admin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-admin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-admin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-admin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-admin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-admin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-admin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "express-admin",
    "version": "1.3.0",
    "description": "MySql, MariaDB, SQLite and PostgreSQL database admin built with Express and Bootstrap",
    "keywords": [
        "mysql",
        "mariadb",
        "sqlite",
        "postgresql",
        "database",
        "admin",
        "express",
        "bootstrap"
    ],
    "license": "MIT",
    "homepage": "https://github.com/simov/express-admin",
    "author": "Simeon Velichkov <simeonvelichkov@gmail.com> (http://simov.github.io)",
    "repository": {
        "type": "git",
        "url": "https://github.com/simov/express-admin.git"
    },
    "dependencies": {
        "express": "4.4.4",
        "morgan": "1.1.1",
        "body-parser": "1.4.3",
        "connect-multiparty": "1.1.0",
        "cookie-parser": "1.3.1",
        "express-session": "1.5.1",
        "csurf": "1.2.2",
        "method-override": "2.0.2",
        "serve-static": "1.2.3",
        "consolidate": "0.9.1",
        "hogan.js": "3.0.2",
        "mysql": "2.2.0",
        "mysql-validator": "0.1.6",
        "async": "0.9.0",
        "pwd": "0.0.3",
        "commander": "1.3.2",
        "colors": "0.6.1",
        "slugify": "0.1.0",
        "sr-pagination": "1.0.1",
        "deep-copy": "1.0.0",
        "xsql": "1.0.1",
        "moment": "2.8.3",
        "express-admin-static": "2.2.2"
    },
    "devDependencies": {
        "mocha": "1.20.1",
        "should": "4.0.4",
        "supertest": "0.15.0",
        "recursive-fs": "*"
    },
    "main": "./app",
    "bin": {
        "admin": "./bin/admin"
    },
    "scripts": {
        "test": "make test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

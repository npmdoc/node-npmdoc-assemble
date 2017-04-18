# npmdoc-assemble

#### api documentation for  [assemble (v0.23.0)](https://github.com/assemble/assemble)  [![npm package](https://img.shields.io/npm/v/npmdoc-assemble.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-assemble) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-assemble.svg)](https://travis-ci.org/npmdoc/node-npmdoc-assemble)

#### Get the rocks out of your socks! Assemble makes you fast at creating web projects. Assemble is used by thousands of projects for rapid prototyping, creating themes, scaffolds, boilerplates, e-books, UI components, API documentation, blogs, building websit

[![NPM](https://nodei.co/npm/assemble.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/assemble)

- [https://npmdoc.github.io/node-npmdoc-assemble/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-assemble/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-assemble/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-assemble/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-assemble/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-assemble/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jon Schlinkert",
        "url": "https://github.com/jonschlinkert"
    },
    "authors": [
        "Brian Woodward (https://github.com/doowb)",
        "Jon Schlinkert (https://github.com/jonschlinkert)"
    ],
    "bin": {
        "assemble": "bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/assemble/assemble/issues"
    },
    "dependencies": {
        "assemble-core": "^0.31.0",
        "assemble-loader": "^1.0.3",
        "base-argv": "^0.5.0",
        "base-cli-process": "^0.1.18",
        "base-config": "^0.5.2",
        "base-questions": "^0.9.1",
        "base-runtimes": "^0.2.0",
        "cross-spawn": "^5.0.1",
        "engine-handlebars": "^0.8.0",
        "export-files": "^2.1.1",
        "fs-exists-sync": "^0.1.0",
        "global-modules": "^0.2.3",
        "is-valid-app": "^0.2.1",
        "lazy-cache": "^2.0.2",
        "log-utils": "^0.2.1",
        "parser-front-matter": "^1.6.2",
        "resolve-dir": "^1.0.0",
        "yargs-parser": "^4.2.1"
    },
    "description": "Get the rocks out of your socks! Assemble makes you fast at creating web projects. Assemble is used by thousands of projects for rapid prototyping, creating themes, scaffolds, boilerplates, e-books, UI components, API documentation, blogs, building websit",
    "devDependencies": {
        "base-store": "^0.4.4",
        "base-test-runner": "^0.2.0",
        "base-test-suite": "^0.4.2",
        "gulp": "^3.9.1",
        "gulp-eslint": "^3.0.1",
        "gulp-format-md": "^0.1.11",
        "gulp-istanbul": "^1.1.1",
        "gulp-mocha": "^3.0.1",
        "gulp-unused": "^0.2.1",
        "helper-changelog": "^0.3.0",
        "mocha": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "930081aa775321904dee55fd4c0ec79218ecf676",
        "tarball": "https://registry.npmjs.org/assemble/-/assemble-0.23.0.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "files": [
        "bin",
        "index.js",
        "lib"
    ],
    "gitHead": "f5e484c476311b58683836d5608cd4a1e725622f",
    "homepage": "https://github.com/assemble/assemble",
    "keywords": [
        "assemble",
        "async-helper",
        "base",
        "blog",
        "boilerplate",
        "boilerplates",
        "bootstrap",
        "build",
        "builder",
        "collection",
        "compile",
        "component",
        "content",
        "docs",
        "document",
        "documentation",
        "engines",
        "generate",
        "generator",
        "handlebars",
        "helper",
        "helpers",
        "html",
        "inflections",
        "jekyll",
        "layout",
        "lodash",
        "markdown",
        "md",
        "page",
        "partial",
        "post",
        "pug",
        "render",
        "scaffold",
        "scaffolder",
        "scaffolding",
        "site",
        "smith",
        "static",
        "static-site",
        "symlink",
        "task",
        "tasks",
        "template",
        "templates",
        "templating",
        "view",
        "views",
        "website",
        "yaml"
    ],
    "license": "MIT",
    "lintDeps": {
        "files": {
            "ignore": [
                "docs",
                "examples",
                "support"
            ]
        }
    },
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonschlinkert"
        }
    ],
    "name": "assemble",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/assemble/assemble.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "verb": {
        "run": true,
        "toc": true,
        "layout": "nil",
        "tasks": [
            "readme"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "helpers": [
            "helper-changelog"
        ],
        "related": {
            "list": [
                "boilerplate",
                "generate",
                "scaffold",
                "update",
                "verb"
            ]
        },
        "reflinks": [
            "assemble-core",
            "assemble-handle",
            "assemble-loader",
            "assemble-permalinks",
            "base",
            "base-data",
            "base-watch",
            "composer",
            "consolidate",
            "expand-object",
            "generate",
            "generate-assemble",
            "gulp",
            "gulp-assemble",
            "helper-changelog",
            "parser-front-matter",
            "templates",
            "update",
            "verb",
            "views",
            "vinyl",
            "vinyl-fs"
        ],
        "lint": {
            "reflinks": true
        }
    },
    "version": "0.23.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

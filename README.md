# api documentation for  [assemble (v0.23.0)](https://github.com/assemble/assemble)  [![npm package](https://img.shields.io/npm/v/npmdoc-assemble.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-assemble) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-assemble.svg)](https://travis-ci.org/npmdoc/node-npmdoc-assemble)
#### Get the rocks out of your socks! Assemble makes you fast at creating web projects. Assemble is used by thousands of projects for rapid prototyping, creating themes, scaffolds, boilerplates, e-books, UI components, API documentation, blogs, building websit

[![NPM](https://nodei.co/npm/assemble.png?downloads=true)](https://www.npmjs.com/package/assemble)

[![apidoc](https://npmdoc.github.io/node-npmdoc-assemble/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-assemble_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-assemble/build/apidoc.html)

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
            "name": "jonschlinkert",
            "email": "github@sellside.com"
        }
    ],
    "name": "assemble",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module assemble](#apidoc.module.assemble)
1.  [function <span class="apidocSignatureSpan">assemble.</span>initAssemble (app)](#apidoc.element.assemble.initAssemble)
1.  [function <span class="apidocSignatureSpan">assemble.</span>initDefaults (app)](#apidoc.element.assemble.initDefaults)
1.  [function <span class="apidocSignatureSpan">assemble.</span>initViews (app)](#apidoc.element.assemble.initViews)
1.  [function <span class="apidocSignatureSpan">assemble.</span>plugins (name, alias)](#apidoc.element.assemble.plugins)
1.  [function <span class="apidocSignatureSpan">assemble.</span>utils (name, alias)](#apidoc.element.assemble.utils)

#### [module assemble.plugins](#apidoc.module.assemble.plugins)
1.  [function <span class="apidocSignatureSpan">assemble.</span>plugins (name, alias)](#apidoc.element.assemble.plugins.plugins)
1.  [function <span class="apidocSignatureSpan">assemble.plugins.</span>argv (config)](#apidoc.element.assemble.plugins.argv)
1.  [function <span class="apidocSignatureSpan">assemble.plugins.</span>cli (config)](#apidoc.element.assemble.plugins.cli)
1.  [function <span class="apidocSignatureSpan">assemble.plugins.</span>config ()](#apidoc.element.assemble.plugins.config)
1.  [function <span class="apidocSignatureSpan">assemble.plugins.</span>loader (patterns, config)](#apidoc.element.assemble.plugins.loader)
1.  [function <span class="apidocSignatureSpan">assemble.plugins.</span>logger (options)](#apidoc.element.assemble.plugins.logger)
1.  [function <span class="apidocSignatureSpan">assemble.plugins.</span>runtimes (config)](#apidoc.element.assemble.plugins.runtimes)

#### [module assemble.utils](#apidoc.module.assemble.utils)
1.  [function <span class="apidocSignatureSpan">assemble.</span>utils (name, alias)](#apidoc.element.assemble.utils.utils)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>arrayify (val)](#apidoc.element.assemble.utils.arrayify)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>colors (name, alias)](#apidoc.element.assemble.utils.colors)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>exists (filepath)](#apidoc.element.assemble.utils.exists)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>extRegex (exts)](#apidoc.element.assemble.utils.extRegex)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>formatDir (cwd)](#apidoc.element.assemble.utils.formatDir)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>homeRelative (fp)](#apidoc.element.assemble.utils.homeRelative)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>isValid (app, name, types)](#apidoc.element.assemble.utils.isValid)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>log (name, alias)](#apidoc.element.assemble.utils.log)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>parse (args, opts)](#apidoc.element.assemble.utils.parse)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>parseArgs (argv)](#apidoc.element.assemble.utils.parseArgs)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>questions (config, fn)](#apidoc.element.assemble.utils.questions)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>resolveDir (dir)](#apidoc.element.assemble.utils.resolveDir)
1.  [function <span class="apidocSignatureSpan">assemble.utils.</span>spawn (command, args, options)](#apidoc.element.assemble.utils.spawn)
1.  object <span class="apidocSignatureSpan">assemble.utils.</span>matter
1.  object <span class="apidocSignatureSpan">assemble.utils.</span>opts
1.  string <span class="apidocSignatureSpan">assemble.utils.</span>gm



# <a name="apidoc.module.assemble"></a>[module assemble](#apidoc.module.assemble)

#### <a name="apidoc.element.assemble.initAssemble"></a>[function <span class="apidocSignatureSpan">assemble.</span>initAssemble (app)](#apidoc.element.assemble.initAssemble)
- description and source-code
```javascript
initAssemble = function (app) {
  Assemble.initDefaults(app);
  Assemble.initPlugins(app);
  Assemble.initViews(app);
}
```
- example usage
```shell
...

function Assemble(options) {
  if (!(this instanceof Assemble)) {
    return new Assemble(options);
  }
  Core.call(this, options);
  this.is('assemble');
  this.initAssemble();
}

/**
 * Inherit 'Core'
 */

Core.extend(Assemble);
...
```

#### <a name="apidoc.element.assemble.initDefaults"></a>[function <span class="apidocSignatureSpan">assemble.</span>initDefaults (app)](#apidoc.element.assemble.initDefaults)
- description and source-code
```javascript
initDefaults = function (app) {
  var exts = app.options.exts || ['md', 'hbs', 'html'];

<span class="apidocCodeCommentSpan">  /**
   * Default engine
   */
</span>
  app.engine(exts, require('engine-handlebars'));

  /**
   * Middleware for parsing front matter
   */

  app.onLoad(utils.extRegex(exts), function(view, next) {
    // check options inside the middleware to account for options defined after init
    if (view.options.frontMatter === false) {
      next();
      return;
    }
    if (app.options.frontMatter === false) {
      next();
      return;
    }
    utils.matter.parse(view, next);
  });
}
```
- example usage
```shell
...
};

/**
* Initialize Assemble defaults, plugins and views
*/

Assemble.initAssemble = function(app) {
 Assemble.initDefaults(app);
 Assemble.initPlugins(app);
 Assemble.initViews(app);
};

/**
* Initialize defaults
*/
...
```

#### <a name="apidoc.element.assemble.initViews"></a>[function <span class="apidocSignatureSpan">assemble.</span>initViews (app)](#apidoc.element.assemble.initViews)
- description and source-code
```javascript
initViews = function (app) {
  if (app.isFalse('collections')) return;

  app.create('partials', {
    engine: app.options.engine || 'hbs',
    viewType: 'partial',
    renameKey: function(fp) {
      return path.basename(fp, path.extname(fp));
    }
  });

  app.create('layouts', {
    engine: app.options.engine || 'hbs',
    viewType: 'layout',
    renameKey: function(fp) {
      return path.basename(fp, path.extname(fp));
    }
  });

  app.create('pages', {
    engine: app.options.engine || 'hbs'
  });
}
```
- example usage
```shell
...
/**
 * Initialize Assemble defaults, plugins and views
 */

Assemble.initAssemble = function(app) {
  Assemble.initDefaults(app);
  Assemble.initPlugins(app);
  Assemble.initViews(app);
};

/**
 * Initialize defaults
 */

Assemble.initDefaults = function(app) {
...
```

#### <a name="apidoc.element.assemble.plugins"></a>[function <span class="apidocSignatureSpan">assemble.</span>plugins (name, alias)](#apidoc.element.assemble.plugins)
- description and source-code
```javascript
function proxy(name, alias) {
  var key = alias;

  // camel-case the module 'name' if 'alias' is not defined
  if (typeof key !== 'string') {
    key = camelcase(name);
  }

  // create a getter to lazily invoke the module the first time it's called
  function getter() {
    return cache[key] || (cache[key] = requireFn(name));
  }

  // trip the getter if 'process.env.UNLAZY' is defined
  if (unlazy(process.env)) {
    getter();
  }

  set(proxy, key, getter);
  return getter;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.utils"></a>[function <span class="apidocSignatureSpan">assemble.</span>utils (name, alias)](#apidoc.element.assemble.utils)
- description and source-code
```javascript
function proxy(name, alias) {
  var key = alias;

  // camel-case the module 'name' if 'alias' is not defined
  if (typeof key !== 'string') {
    key = camelcase(name);
  }

  // create a getter to lazily invoke the module the first time it's called
  function getter() {
    return cache[key] || (cache[key] = requireFn(name));
  }

  // trip the getter if 'process.env.UNLAZY' is defined
  if (unlazy(process.env)) {
    getter();
  }

  set(proxy, key, getter);
  return getter;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.assemble.plugins"></a>[module assemble.plugins](#apidoc.module.assemble.plugins)

#### <a name="apidoc.element.assemble.plugins.plugins"></a>[function <span class="apidocSignatureSpan">assemble.</span>plugins (name, alias)](#apidoc.element.assemble.plugins.plugins)
- description and source-code
```javascript
function proxy(name, alias) {
  var key = alias;

  // camel-case the module 'name' if 'alias' is not defined
  if (typeof key !== 'string') {
    key = camelcase(name);
  }

  // create a getter to lazily invoke the module the first time it's called
  function getter() {
    return cache[key] || (cache[key] = requireFn(name));
  }

  // trip the getter if 'process.env.UNLAZY' is defined
  if (unlazy(process.env)) {
    getter();
  }

  set(proxy, key, getter);
  return getter;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.plugins.argv"></a>[function <span class="apidocSignatureSpan">assemble.plugins.</span>argv (config)](#apidoc.element.assemble.plugins.argv)
- description and source-code
```javascript
argv = function (config) {
  return function() {
    if (!utils.isValid(this)) return;
    debug('initializing <%s>, called from <%s>', __filename, module.parent.id);

<span class="apidocCodeCommentSpan">    /**
     * Process and normalize command line arguments.
     *
     * @param {Object} 'argv'
     * @param {Object} 'options'
     * @return {Object}
     * @api public
     */
</span>
    this.define('argv', function(argv, options) {
      if (argv.processed === true) {
        return argv;
      }

      debug('processing argv object', argv);

      var orig = Array.isArray(argv) ? argv.slice() : utils.extend({}, argv);
      var opts = utils.extend({}, config, this.options, options, argv);
      var args = processArgv(this, argv, opts);
      if (args.expand === 'false' || opts.expand === false) {
        delete args.expand;
        return args;
      }

      utils.define(args, 'orig', orig);
      utils.define(args, 'processed', true);

      this.emit('argv', args);
      return args;
    });
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.plugins.cli"></a>[function <span class="apidocSignatureSpan">assemble.plugins.</span>cli (config)](#apidoc.element.assemble.plugins.cli)
- description and source-code
```javascript
cli = function (config) {
  config = config || {};

  return function(app, base) {
    if (!utils.isValid(app, 'base-cli-process')) return;
    debug('initializing <%s>, called from <%s>', __filename, module.parent.id);

    app.use(assertPlugin);
    var options = createOpts(app, config);
    var schema;

    initPlugins(this, options);

    Object.defineProperty(this.cli, 'schema', {
      cliurable: true,
      enumerable: true,
      set: function(val) {
        schema = val;
      },
      get: function() {
        return schema || utils.schema(app, createOpts(app, config));
      }
    });

    // add commands
    for (var key in fields) {
      debug('mapping field "%s"', key);
      app.cli.map(key, fields[key](app, base, options));
    }

    var fn = this.cli.process;

    this.cli.process = function(val, cb) {
      debug('normalizing argv object', val);

      var defaults = {sortArrays: false, omitEmpty: true};
      var keys = ['get', 'set', 'toc', 'layout', 'options', 'data', 'plugins', 'related', 'reflinks', 'init', 'run', 'tasks'];

      var opts = createOpts(app, config, defaults);
      var obj = sortObject(this.schema.normalize(val, opts), keys);

      debug('processing normalized argv', obj);
      fn.call(this, obj, function(err) {
        if (err) return cb(err);
        cb(null, obj);
      });
    };
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.plugins.config"></a>[function <span class="apidocSignatureSpan">assemble.plugins.</span>config ()](#apidoc.element.assemble.plugins.config)
- description and source-code
```javascript
config = function () {
  return create('config');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.plugins.loader"></a>[function <span class="apidocSignatureSpan">assemble.plugins.</span>loader (patterns, config)](#apidoc.element.assemble.plugins.loader)
- description and source-code
```javascript
function loader(patterns, config) {
  if (utils.isObject(patterns)) {
    config = patterns;
    patterns = undefined;
  }

  return function plugin(app) {
    if (utils.isRegistered(this, 'assemble-loader')) return;

    // register the plugin on an "app"
    if (utils.isValidInstance(this)) {
      appLoader(this, config);

      // if patterns are passed to the plugin, load them now
      if (utils.isValidGlob(patterns)) {
        this.load(patterns);
      }
    }

    // register the plugin on a "collection"
    if (utils.isValidInstance(this, ['collection'])) {
      collectionLoader(this, config);

      // if patterns are passed to the plugin, load them now
      if (utils.isValidGlob(patterns)) {
        this.load(patterns);
      }
    }

    return plugin;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.plugins.logger"></a>[function <span class="apidocSignatureSpan">assemble.plugins.</span>logger (options)](#apidoc.element.assemble.plugins.logger)
- description and source-code
```javascript
logger = function (options) {
  return function() {
    if (!utils.isValid(this, 'assemble-logger')) return;
    function logger(prop, color) {
      color = color || 'dim';
      return function(msg) {
        var rest = [].slice.call(arguments, 1);
        return console.log
          .bind(console, utils.log.timestamp + (prop ? (' ' + utils.log[prop]) : ''))
          .apply(console, [utils.log[color](msg)].concat(rest));
      };
    };

    Object.defineProperty(this, 'log', {
      configurable: true,
      get: function() {
        function log() {
          return console.log.apply(console, arguments);
        }
        log.path = function(msg) {
          return logger(null, 'dim').apply(null, arguments);
        };
        log.time = function(msg) {
          return logger(null, 'dim').apply(null, arguments);
        };
        log.warn = function(msg) {
          return logger('warning', 'yellow').apply(null, arguments);
        };
        log.success = function() {
          return logger('success', 'green').apply(null, arguments);
        };

        log.info = function() {
          return logger('info', 'cyan').apply(null, arguments);
        };

        log.error = function() {
          return logger('error', 'red').apply(null, arguments);
        };
        log.__proto__ = utils.log;
        return log;
      }
    });
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.plugins.runtimes"></a>[function <span class="apidocSignatureSpan">assemble.plugins.</span>runtimes (config)](#apidoc.element.assemble.plugins.runtimes)
- description and source-code
```javascript
runtimes = function (config) {
  config = config || {};

  return function baseRuntimes(app) {
    if (!utils.isValid(app, 'base-runtimes')) return;
    var time = new utils.Time();
    var log = utils.log;

    this.on('starting', function(build) {
      // create build context
      var ctx = {app: build};
      ctx.key = toKey(namespace(build));
      ctx.event = 'starting';
      time.start(ctx.key);
      ctx.time = '';
      ctx.isBuild = true;
      ctx.isSilent = silent(app, build, null);

      if (app.hasListeners('build')) {
        app.emit('build', ctx.event, ctx);
      } else if (app.base.hasListeners('build')) {
        app.base.emit('build', ctx.event, ctx);
      } else if (!ctx.isSilent) {
        console.error(log.timestamp, ctx.event, ctx.key, log.red(ctx.time));
      }
    });

    this.on('finished', function(build, run) {
      // create build context
      var ctx = {app: build};
      ctx.key = toKey(namespace(build));
      ctx.time = time.end(ctx.key);
      ctx.event = 'finished';
      ctx.isBuild = true;
      ctx.isSilent = silent(app, build, null);

      if (app.hasListeners('build')) {
        app.emit('build', ctx.event, ctx);
      } else if (app.base.hasListeners('build')) {
        app.base.emit('build', ctx.event, ctx);
      } else if (!ctx.isSilent) {
        console.error(log.timestamp, ctx.event, ctx.key, log.red(ctx.time));
      }
    });

    this.on('task:starting', function(task) {
      task.key = toKey(namespace(app), name(task) + ' task');
      time.start('task:' + task.key);
      task.event = 'starting';
      task.time = '';
      task.isTask = true;
      task.isSilent = silent(app, null, task);

      if (app.hasListeners('task')) {
        app.emit('task', task.event, task);
      } else if (app.base.hasListeners('task')) {
        app.base.emit('task', task.event, task);
      } else if (!task.isSilent) {
        console.error(log.timestamp, task.event, task.key, log.red(task.time));
      }
    });

    this.on('task:finished', function(task) {
      task.key = toKey(namespace(app), name(task) + ' task');
      task.time = time.end('task:' + task.key);
      task.event = 'finished';
      task.isTask = true;
      task.isSilent = silent(app, null, task);

      if (app.hasListeners('task')) {
        app.emit('task', task.event, task);
      } else if (app.base.hasListeners('task')) {
        app.base.emit('task', task.event, task);
      } else if (!task.isSilent) {
        console.error(log.timestamp, task.event, task.key, log.red(task.time));
      }
    });

<span class="apidocCodeCommentSpan">    /**
     * Handle toggling of verbose and silent modes
     */
</span>
    function silent(app, build, task) {
      var opts = utils.extend({}, app.base.options, app.options);

      if (build && build.options) {
        opts = utils.extend({}, opts, build.options);
      }
      if (task && task.options) {
        opts = utils.extend({}, opts, task.options);
      }

      var verbose = opts.verbose;
      var silent = opts.silent;

      // handle 'verbose' first
      if (typeof verbose === 'function') {
        return verbose(app, build, task);
      }
      if (verbose === true) {
        return false;
      }
      if (task && verbose === 'tasks') {
        return false;
      }
      if (build && verbose === 'build') {
        return false;
      }

      // if not 'verbose', handle 'silent'
      if (typeof silent === 'function') {
        return silent(app, build, task);
      }
      if (typeof silent === 'string') {
        silent = [silent];
      }

      if (build && Array.isArray(silent) && isMatch(silent, build.alias)) {
        return true;
      }
      if (task && Array.isArray(silent) && isMatch(silent, task.name)) {
        return true;
      }
      if (silent === true) {
        return true;
      }
    }

    function name(task) {
      return task.name || '';
    }

    function namespace(build) {
      return build.env ? build.env.namespace : (build.namespace || build._name);
    }

    function toKey(namespace, name) {
      var res = '';
      if (namespace) {
        namespace = formatN ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.assemble.utils"></a>[module assemble.utils](#apidoc.module.assemble.utils)

#### <a name="apidoc.element.assemble.utils.utils"></a>[function <span class="apidocSignatureSpan">assemble.</span>utils (name, alias)](#apidoc.element.assemble.utils.utils)
- description and source-code
```javascript
function proxy(name, alias) {
  var key = alias;

  // camel-case the module 'name' if 'alias' is not defined
  if (typeof key !== 'string') {
    key = camelcase(name);
  }

  // create a getter to lazily invoke the module the first time it's called
  function getter() {
    return cache[key] || (cache[key] = requireFn(name));
  }

  // trip the getter if 'process.env.UNLAZY' is defined
  if (unlazy(process.env)) {
    getter();
  }

  set(proxy, key, getter);
  return getter;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.utils.arrayify"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>arrayify (val)](#apidoc.element.assemble.utils.arrayify)
- description and source-code
```javascript
arrayify = function (val) {
  return [].concat(val || []);
}
```
- example usage
```shell
...
};

/**
 * Create a regex for matching file extensions
 */

utils.extRegex = function(exts) {
  return new RegExp('\\.(' + utils.arrayify(exts).join('|') + ')$');
};

/**
 * Get a home-relative filepath
 */

utils.homeRelative = function(fp) {
...
```

#### <a name="apidoc.element.assemble.utils.colors"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>colors (name, alias)](#apidoc.element.assemble.utils.colors)
- description and source-code
```javascript
function proxy(name, alias) {
  var key = alias;

  // camel-case the module 'name' if 'alias' is not defined
  if (typeof key !== 'string') {
    key = camelcase(name);
  }

  // create a getter to lazily invoke the module the first time it's called
  function getter() {
    return cache[key] || (cache[key] = requireFn(name));
  }

  // trip the getter if 'process.env.UNLAZY' is defined
  if (unlazy(process.env)) {
    getter();
  }

  set(proxy, key, getter);
  return getter;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.utils.exists"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>exists (filepath)](#apidoc.element.assemble.utils.exists)
- description and source-code
```javascript
exists = function (filepath) {
  try {
    (fs.accessSync || fs.statSync)(filepath);
    return true;
  } catch (err) {}
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.utils.extRegex"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>extRegex (exts)](#apidoc.element.assemble.utils.extRegex)
- description and source-code
```javascript
extRegex = function (exts) {
  return new RegExp('\\.(' + utils.arrayify(exts).join('|') + ')$');
}
```
- example usage
```shell
...

app.engine(exts, require('engine-handlebars'));

/**
 * Middleware for parsing front matter
 */

app.onLoad(utils.extRegex(exts), function(view, next) {
  // check options inside the middleware to account for options defined after init
  if (view.options.frontMatter === false) {
    next();
    return;
  }
  if (app.options.frontMatter === false) {
    next();
...
```

#### <a name="apidoc.element.assemble.utils.formatDir"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>formatDir (cwd)](#apidoc.element.assemble.utils.formatDir)
- description and source-code
```javascript
formatDir = function (cwd) {
  return utils.colors.yellow('~/' + utils.homeRelative(cwd));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.utils.homeRelative"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>homeRelative (fp)](#apidoc.element.assemble.utils.homeRelative)
- description and source-code
```javascript
homeRelative = function (fp) {
  var dir = path.resolve(utils.resolveDir(fp));
  var home = path.resolve(utils.resolveDir('~/'));
  fp = path.relative(home, dir);
  if (fp.charAt(0) === '/') {
    fp = fp.slice(1);
  }
  return fp;
}
```
- example usage
```shell
...
};

/**
 * Get formatted cwd path
 */

utils.formatDir = function(cwd) {
  return utils.colors.yellow('~/' + utils.homeRelative(cwd));
};
...
```

#### <a name="apidoc.element.assemble.utils.isValid"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>isValid (app, name, types)](#apidoc.element.assemble.utils.isValid)
- description and source-code
```javascript
isValid = function (app, name, types) {
  if (typeof name !== 'string') {
    throw new TypeError('expected plugin name to be a string');
  }

  // if 'app' is not a valid instance of 'Base', or if 'app' is a valid
  // instance of Base by not one of the given 'types' return false
  if (!utils.isValid(app, types)) {
    return false;
  }

  // if the 'name' has already been registered as a plugin, return false
  if (utils.isRegistered(app, name)) {
    return false;
  }

  var debug = utils.debug('base:generate:' + name);
  debug('initializing from <%s>', (module.parent && module.parent.id) || __dirname);
  return true;
}
```
- example usage
```shell
...

/**
 * Add logging methods
 */

plugins.logger = function(options) {
return function() {
  if (!utils.isValid(this, 'assemble-logger')) return;
  function logger(prop, color) {
    color = color || 'dim';
    return function(msg) {
      var rest = [].slice.call(arguments, 1);
      return console.log
        .bind(console, utils.log.timestamp + (prop ? (' ' + utils.log[prop]) : ''))
        .apply(console, [utils.log[color](msg)].concat(rest));
...
```

#### <a name="apidoc.element.assemble.utils.log"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>log (name, alias)](#apidoc.element.assemble.utils.log)
- description and source-code
```javascript
function proxy(name, alias) {
  var key = alias;

  // camel-case the module 'name' if 'alias' is not defined
  if (typeof key !== 'string') {
    key = camelcase(name);
  }

  // create a getter to lazily invoke the module the first time it's called
  function getter() {
    return cache[key] || (cache[key] = requireFn(name));
  }

  // trip the getter if 'process.env.UNLAZY' is defined
  if (unlazy(process.env)) {
    getter();
  }

  set(proxy, key, getter);
  return getter;
}
```
- example usage
```shell
...
* 'cb' **{Function}**: callback function that exposes 'err'

**Example**

'''js
app.build(['foo', 'bar'], function(err) {
  if (err) throw err;
  console.log('done!');
});
'''

#### .watch

Watch files, run one or more tasks when a watched file changes.
...
```

#### <a name="apidoc.element.assemble.utils.parse"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>parse (args, opts)](#apidoc.element.assemble.utils.parse)
- description and source-code
```javascript
function Parser(args, opts) {
  var result = parse(args.slice(), opts)

  return result.argv
}
```
- example usage
```shell
...
     next();
     return;
   }
   if (app.options.frontMatter === false) {
     next();
     return;
   }
   utils.matter.parse(view, next);
 });
};

/**
* Load default plugins. Built-in plugins can be disabled
* on the 'assemble' options.
*
...
```

#### <a name="apidoc.element.assemble.utils.parseArgs"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>parseArgs (argv)](#apidoc.element.assemble.utils.parseArgs)
- description and source-code
```javascript
parseArgs = function (argv) {
  var obj = utils.parse(argv, utils.opts);
  if (obj.init) {
    obj._.push('init');
    delete obj.init;
  }
  if (obj.help) {
    obj._.push('help');
    delete obj.help;
  }
  return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.assemble.utils.questions"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>questions (config, fn)](#apidoc.element.assemble.utils.questions)
- description and source-code
```javascript
questions = function (config, fn) {
  return function plugin(app) {
    if (!utils.isValid(app, 'base-questions')) return;
    debug('initializing from <%s>', __filename);

    this.define('Questions', this.options.questions || utils.Questions);
    app.cache.answers = app.cache.answers || {};

<span class="apidocCodeCommentSpan">    /**
     * Events
     */
</span>
    this.on('ask', function(val, key, question, answers) {
      var data = utils.merge({}, answers, app.store.data, app.cache.answers, app.cache.data);
      if (app.option('common-config') !== false) {
        data = utils.merge({}, app.questions.common.data, data);
      }
      var answer = utils.get(data, key);
      if (answer) {
        utils.set(answers, key, answer);
      }
    });

    this.on('answer', function(val, key, question, answers) {
      app.base.data(key, val);
      app.data(key, val);
    });

    /**
     * Decorate the 'questions' instance onto 'app' and lazily
     * invoke the 'question-store' lib when a questions related
     * method is called.
     */

    utils.sync(this, 'questions', function fn() {
      if (typeof app.store === 'undefined') {
        this.use(utils.store());
      }

      // return cached instance
      if (fn._questions) return fn._questions;

      var cwd = app.cwd || process.cwd();
      var opts = utils.merge({}, app.options, config);
      opts.data = app.cache.data || {};
      opts.cwd = cwd;

      var Questions = app.Questions;
      var questions = new Questions(opts);
      fn._questions = questions;
      questions.cwd = cwd;

      var data = questions.data;
      questions.on('ask', app.emit.bind(app, 'ask'));
      questions.on('answer', app.emit.bind(app, 'answer'));
      questions.on('error', function(err) {
        err.reason = 'base-questions error';
        app.emit('error', err);
      });

      Object.defineProperty(questions, 'data', {
        set: function(val) {
          data = val;
        },
        get: function() {
          data = utils.merge({}, data, opts.data);
          return utils.clone(data);
        }
      });

      return questions;
    });

    /**
     * Create a 'confirm' question.
     *
     * '''js
     * app.confirm('file', 'Want to generate a file?');
     *
     * // equivalent to
     * app.question({
     *   name: 'file',
     *   message: 'Want to generate a file?',
     *   type: 'confirm'
     * });
     * '''
     * @name .confirm
     * @param {String} 'name' Question name
     * @param {String} 'msg' Question message
     * @param {String|Array} 'queue' Name or array of question names.
     * @param {Object|Function} 'options' Question options or callback function
     * @param {Function} 'callback' callback function
     * @api public
     */

    this.define('confirm', function() {
      this.questions.confirm.apply(this.questions, arguments);
      return this.questions;
    });

    /**
     * Create a "choices" question from an array.
     *
     * '''js
     * app.choices('color', 'Favorite color?', ['blue', 'orange', 'green']);
     *
     * // or
     * app.choices('color', {
     *   message: 'Favorite color?',
     *   choices: ['blue', 'orange', 'green']
     * });
     *
     * // or
     * app.choices({
     *   name: 'color',
     *   message: 'Favorite color?',
     *   choices: ['blue', 'orange', 'green']
     * });
     * '''
     * @name .choices
     * @param {String} 'name' Question name
     * @param {String} 'msg' Question message
     * @param {Array} 'choices' Choice items
     * @param {String|Array} 'queue' Name or array of question names.
     * @param {Object|Function} 'options' Question options or callback function
     * @param {Function} 'callback' callback function
     * @api public
     */

    this.define('choices', function() {
      this.questions.choices.apply(this.questions, arguments);
      return this.questions;
    });

    /**
     * Add a question to be asked by the '.ask' method.
     *
     * '''js
     * app.question('beverage', 'What is your favorite beverage?');
     *
     * // or
     * app.question('beverage', {
     *   type: 'input',
     * ...
```
- example usage
```shell
...
'use strict';

var utils = require('./utils');

module.exports = function(app) {

// use 'base-questions' plugin for user prompts
app.use(utils.questions());

/**
 * Listend for 'done' event
 */

app.on('done', function() {
  app.log.success('done');
...
```

#### <a name="apidoc.element.assemble.utils.resolveDir"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>resolveDir (dir)](#apidoc.element.assemble.utils.resolveDir)
- description and source-code
```javascript
function resolveDir(dir) {
  if (dir.charAt(0) === '~') {
    dir = expand(dir);
  }
  if (dir.charAt(0) === '@') {
    dir = path.join(gm, dir.slice(1));
  }
  return dir;
}
```
- example usage
```shell
...
};

/**
 * Get a home-relative filepath
 */

utils.homeRelative = function(fp) {
  var dir = path.resolve(utils.resolveDir(fp));
  var home = path.resolve(utils.resolveDir('~/'));
  fp = path.relative(home, dir);
  if (fp.charAt(0) === '/') {
    fp = fp.slice(1);
  }
  return fp;
};
...
```

#### <a name="apidoc.element.assemble.utils.spawn"></a>[function <span class="apidocSignatureSpan">assemble.utils.</span>spawn (command, args, options)](#apidoc.element.assemble.utils.spawn)
- description and source-code
```javascript
function spawn(command, args, options) {
    var parsed;
    var spawned;

    // Parse the arguments
    parsed = parse(command, args, options);

    // Spawn the child process
    spawned = cp.spawn(parsed.command, parsed.args, parsed.options);

    // Hook into child process "exit" event to emit an error if the command
    // does not exists, see: https://github.com/IndigoUnited/node-cross-spawn/issues/16
    enoent.hookChildProcess(spawned, parsed);

    return spawned;
}
```
- example usage
```shell
...

/**
 * Install devDependencies
 */

function install(args, cb) {
  args = ['install', '--save-dev'].concat(args);
  utils.spawn('npm', args, {stdio: 'inherit'})
    .on('error', cb)
    .on('close', function(code, err) {
      cb(err, code);
    });
}
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

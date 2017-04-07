# api documentation for  [stylus-loader (v3.0.1)](https://github.com/shama/stylus-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-stylus-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-stylus-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-stylus-loader.svg)](https://travis-ci.org/npmdoc/node-npmdoc-stylus-loader)
#### Stylus loader for webpack

[![NPM](https://nodei.co/npm/stylus-loader.png?downloads=true)](https://www.npmjs.com/package/stylus-loader)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-stylus-loader_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Robinson Young",
        "email": "kyle@dontkry.com",
        "url": "http://dontkry.com"
    },
    "bugs": {
        "url": "https://github.com/shama/stylus-loader/issues"
    },
    "dependencies": {
        "loader-utils": "^1.0.2",
        "lodash.clonedeep": "^4.5.0",
        "when": "~3.6.x"
    },
    "description": "Stylus loader for webpack",
    "devDependencies": {
        "benchmark": "^1.0.0",
        "css-loader": "^0.14.0",
        "mocha": "~2.1.0",
        "mocha-loader": "^1.0.0",
        "nib": "^1.0.4",
        "node-libs-browser": "^0.5.2",
        "raw-loader": "~0.5.1",
        "should": "~4.6.1",
        "style-loader": "^0.12.2",
        "stylus": ">=0.52.4",
        "testem": "^0.8.3",
        "webpack": "^2.2.0",
        "webpack-dev-server": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "77f4b34fd030d25b2617bcf5513db5b0730c4089",
        "tarball": "https://registry.npmjs.org/stylus-loader/-/stylus-loader-3.0.1.tgz"
    },
    "files": [
        "index.js",
        "lib/"
    ],
    "gitHead": "a2725db3827f7f41d350a079ffe215005a71b159",
    "homepage": "https://github.com/shama/stylus-loader#readme",
    "keywords": [
        "webpack",
        "loader",
        "stylus"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "shama",
            "email": "kyle@dontkry.com"
        },
        {
            "name": "mzgoddard",
            "email": "mzgoddard@gmail.com"
        }
    ],
    "name": "stylus-loader",
    "optionalDependencies": {},
    "peerDependencies": {
        "stylus": ">=0.52.4"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/shama/stylus-loader.git"
    },
    "scripts": {
        "test": "testem ci",
        "test-build": "webpack --config test/webpack.config.js --output-path=test/tmp --output-filename=bundle.js",
        "test-dev": "testem -l firefox",
        "test-one": "testem ci -l firefox"
    },
    "version": "3.0.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module stylus-loader](#apidoc.module.stylus-loader)
1.  [function <span class="apidocSignatureSpan">stylus-loader.</span>evaluator (root, options)](#apidoc.element.stylus-loader.evaluator)
1.  [function <span class="apidocSignatureSpan">stylus-loader.</span>pathcache (contexts, sources, imports)](#apidoc.element.stylus-loader.pathcache)
1.  object <span class="apidocSignatureSpan">stylus-loader.</span>evaluator.prototype
1.  object <span class="apidocSignatureSpan">stylus-loader.</span>pathcache.prototype

#### [module stylus-loader.evaluator](#apidoc.module.stylus-loader.evaluator)
1.  [function <span class="apidocSignatureSpan">stylus-loader.</span>evaluator (root, options)](#apidoc.element.stylus-loader.evaluator.evaluator)

#### [module stylus-loader.evaluator.prototype](#apidoc.module.stylus-loader.evaluator.prototype)
1.  [function <span class="apidocSignatureSpan">stylus-loader.evaluator.prototype.</span>constructor (root, options)](#apidoc.element.stylus-loader.evaluator.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">stylus-loader.evaluator.prototype.</span>visitImport (imported)](#apidoc.element.stylus-loader.evaluator.prototype.visitImport)

#### [module stylus-loader.pathcache](#apidoc.module.stylus-loader.pathcache)
1.  [function <span class="apidocSignatureSpan">stylus-loader.</span>pathcache (contexts, sources, imports)](#apidoc.element.stylus-loader.pathcache.pathcache)
1.  [function <span class="apidocSignatureSpan">stylus-loader.pathcache.</span>create (contexts, sources, imports)](#apidoc.element.stylus-loader.pathcache.create)
1.  [function <span class="apidocSignatureSpan">stylus-loader.pathcache.</span>createFromFile (helpers, parentCache, source, fullPath)](#apidoc.element.stylus-loader.pathcache.createFromFile)
1.  [function <span class="apidocSignatureSpan">stylus-loader.pathcache.</span>resolvers (options, webpackResolver)](#apidoc.element.stylus-loader.pathcache.resolvers)

#### [module stylus-loader.pathcache.prototype](#apidoc.module.stylus-loader.pathcache.prototype)
1.  [function <span class="apidocSignatureSpan">stylus-loader.pathcache.prototype.</span>allDeps ()](#apidoc.element.stylus-loader.pathcache.prototype.allDeps)
1.  [function <span class="apidocSignatureSpan">stylus-loader.pathcache.prototype.</span>find (path, dirname)](#apidoc.element.stylus-loader.pathcache.prototype.find)
1.  [function <span class="apidocSignatureSpan">stylus-loader.pathcache.prototype.</span>isIndex (path, dirname)](#apidoc.element.stylus-loader.pathcache.prototype.isIndex)



# <a name="apidoc.module.stylus-loader"></a>[module stylus-loader](#apidoc.module.stylus-loader)

#### <a name="apidoc.element.stylus-loader.evaluator"></a>[function <span class="apidocSignatureSpan">stylus-loader.</span>evaluator (root, options)](#apidoc.element.stylus-loader.evaluator)
- description and source-code
```javascript
function CachedPathEvaluator(root, options) {
  Evaluator.apply(this, arguments);

  this.cache = options.cache;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylus-loader.pathcache"></a>[function <span class="apidocSignatureSpan">stylus-loader.</span>pathcache (contexts, sources, imports)](#apidoc.element.stylus-loader.pathcache)
- description and source-code
```javascript
function PathCache(contexts, sources, imports) {
  this.contexts = contexts;
  this.sources = sources;
  this.imports = imports;

  // Non relative paths are simpler and looked up in this as a fallback
  // to this.context.
  this.simpleContext = {};
  for (var dirname in this.contexts) {
    for (var path in this.contexts[dirname]) {
      this.simpleContext[path] = this.contexts[dirname][path];
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stylus-loader.evaluator"></a>[module stylus-loader.evaluator](#apidoc.module.stylus-loader.evaluator)

#### <a name="apidoc.element.stylus-loader.evaluator.evaluator"></a>[function <span class="apidocSignatureSpan">stylus-loader.</span>evaluator (root, options)](#apidoc.element.stylus-loader.evaluator.evaluator)
- description and source-code
```javascript
function CachedPathEvaluator(root, options) {
  Evaluator.apply(this, arguments);

  this.cache = options.cache;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stylus-loader.evaluator.prototype"></a>[module stylus-loader.evaluator.prototype](#apidoc.module.stylus-loader.evaluator.prototype)

#### <a name="apidoc.element.stylus-loader.evaluator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">stylus-loader.evaluator.prototype.</span>constructor (root, options)](#apidoc.element.stylus-loader.evaluator.prototype.constructor)
- description and source-code
```javascript
function CachedPathEvaluator(root, options) {
  Evaluator.apply(this, arguments);

  this.cache = options.cache;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylus-loader.evaluator.prototype.visitImport"></a>[function <span class="apidocSignatureSpan">stylus-loader.evaluator.prototype.</span>visitImport (imported)](#apidoc.element.stylus-loader.evaluator.prototype.visitImport)
- description and source-code
```javascript
visitImport = function (imported) {
  this.return++;

  var path = this.visit(imported.path).first
    , nodeName = imported.once ? 'require' : 'import'
    , found
    , literal
    , index;

  this.return--;
  // debug('import %s', path);

  // url() passed
  if ('url' == path.name) {
    if (imported.once) throw new Error('You cannot @require a url');

    return imported;
  }

  // Ensure string
  if (!path.string) throw new Error('@' + nodeName + ' string expected');

  var name = path = path.string;

  // Absolute URL
  if (/url\s*\(\s*['"]?(?:https?:)?\/\//i.test(path)) {
    if (imported.once) throw new Error('You cannot @require a url');
    return imported;
  }

  // Literal
  if (/\.css(?:"|$)/.test(path)) {
    literal = true;
    if (!imported.once && !this.includeCSS) {
      return imported;
    }
  }

  // support optional .styl
  if (!literal && !/\.styl$/i.test(path)) path += '.styl';

<span class="apidocCodeCommentSpan">  /*****************************************************************************
  * THIS IS THE ONLY BLOCK THAT DIFFERS FROM THE ACTUAL STYLUS IMPLEMENTATION. *
  *****************************************************************************/
</span>  // Lookup
  var dirname = this.paths[this.paths.length - 1];
  found = this.cache.find(path, dirname);
  index = this.cache.isIndex(path, dirname);
  if (!found) {
    found = utils.find(path, this.paths, this.filename);
    if (!found) {
      found = utils.lookupIndex(name, this.paths, this.filename);
      index = true;
    }
  }

  // Throw if import failed
  if (!found) throw new Error('failed to locate @' + nodeName + ' file ' + path);

  var block = new nodes.Block;

  for (var i = 0, len = found.length; i < len; ++i) {
    block.push(importFile.call(this, imported, found[i], literal, index));
  }

  return block;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stylus-loader.pathcache"></a>[module stylus-loader.pathcache](#apidoc.module.stylus-loader.pathcache)

#### <a name="apidoc.element.stylus-loader.pathcache.pathcache"></a>[function <span class="apidocSignatureSpan">stylus-loader.</span>pathcache (contexts, sources, imports)](#apidoc.element.stylus-loader.pathcache.pathcache)
- description and source-code
```javascript
function PathCache(contexts, sources, imports) {
  this.contexts = contexts;
  this.sources = sources;
  this.imports = imports;

  // Non relative paths are simpler and looked up in this as a fallback
  // to this.context.
  this.simpleContext = {};
  for (var dirname in this.contexts) {
    for (var path in this.contexts[dirname]) {
      this.simpleContext[path] = this.contexts[dirname][path];
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylus-loader.pathcache.create"></a>[function <span class="apidocSignatureSpan">stylus-loader.pathcache.</span>create (contexts, sources, imports)](#apidoc.element.stylus-loader.pathcache.create)
- description and source-code
```javascript
create = function (contexts, sources, imports) {
  return when(new PathCache(contexts, sources, imports));
}
```
- example usage
```shell
...

function CachedPathEvaluator(root, options) {
Evaluator.apply(this, arguments);

this.cache = options.cache;
}

CachedPathEvaluator.prototype = Object.create(Evaluator.prototype);
CachedPathEvaluator.prototype.constructor = CachedPathEvaluator;

CachedPathEvaluator.prototype.visitImport = function(imported) {
this.return++;

var path = this.visit(imported.path).first
  , nodeName = imported.once ? 'require' : 'import'
...
```

#### <a name="apidoc.element.stylus-loader.pathcache.createFromFile"></a>[function <span class="apidocSignatureSpan">stylus-loader.pathcache.</span>createFromFile (helpers, parentCache, source, fullPath)](#apidoc.element.stylus-loader.pathcache.createFromFile)
- description and source-code
```javascript
function resolveFileDeep(helpers, parentCache, source, fullPath) {
  var resolvers = helpers.resolvers;
  var readFile = helpers.readFile;

  var contexts = parentCache.contexts;
  var sources = parentCache.sources;

  contexts = contexts || {};
  var nestResolve = resolveFileDeep.bind(null, helpers, parentCache, null);
  var context = path.dirname(fullPath);
  readFile = whenNodefn.lift(readFile);

  return when
    .resolve(source || sources[fullPath] || readFile(fullPath))
    // Cast the buffer from the cached input file system to a string.
    .then(String)
    // Store the source so that the evaluator doesn't need to touch the
    // file system.
    .then(function(_source) {
      sources[fullPath] = _source;
      return _source;
    })
    // Make sure the stylus functions/index.styl source is stored.
    .then(partial(ensureFunctionsSource, sources))
    // List imports and use its cache. The source file is translated into a
    // list of imports. Where the source file came from isn't important for the
    // list. The where is added by resolveMany with the context and resolvers.
    .then(partialRight(listImports, { cache: parentCache.imports }))
    .then(resolveMany.bind(null, resolvers, context))
    .then(function(newPaths) {
      // Contexts are the full path since multiple could be in the same folder
      // but different deps.
      contexts[context] = merge(contexts[context] || {}, newPaths);
      return when.map(Object.keys(newPaths), function(key) {
        var found = newPaths[key] && newPaths[key].path;
        if (found) {
          return when.map(found, nestResolve);
        }
      });
    })
    .then(function() {
      return PathCache.create(contexts, sources, parentCache.imports);
    });
}
```
- example usage
```shell
...
paths.forEach(styl.import.bind(styl));
paths.forEach(self.addDependency);

var readFile = whenNodefn.lift(pathCacheHelpers.readFile);
return when.reduce(paths, function(cache, filepath) {
  return readFile(filepath)
    .then(function(source) {
      return PathCache.createFromFile(
        pathCacheHelpers, cache, source.toString(), filepath
      );
    });
}, {
  contexts: {},
  sources: {},
  imports: importsCache,
...
```

#### <a name="apidoc.element.stylus-loader.pathcache.resolvers"></a>[function <span class="apidocSignatureSpan">stylus-loader.pathcache.</span>resolvers (options, webpackResolver)](#apidoc.element.stylus-loader.pathcache.resolvers)
- description and source-code
```javascript
function resolvers(options, webpackResolver) {
  var evaluator = new Evaluator(nodes.null, options);
  var whenWebpackResolver = whenNodefn.lift(webpackResolver);

  // Stylus's normal resolver for single files.
  var stylusFile = function(context, path) {
    // Stylus adds .styl to paths for normal "paths" lookup if it isn't there.
    if (!/.styl$/.test(path)) {
      path += '.styl';
    }

    var paths = options.paths.concat(context);
    var found = utils.find(path, paths, options.filename)
    if (found) {
      return normalizePaths(found);
    }
  };

  // Stylus's normal resolver for node_modules packages. Cannot locate paths
  // inside a package.
  var stylusIndex = function(context, path) {
    // Stylus calls the argument name. If it exists it should match the name
    // of a module in node_modules.
    if (!path) {
      return null;
    }

    var paths = options.paths.concat(context);
    var found = utils.lookupIndex(path, paths, options.filename);
    if (found) {
      return {path: normalizePaths(found), index: true};
    }
  };

  // Fallback to resolving with webpack's configured resovler.
  var webpackResolve = function(context, path) {
    // Follow the webpack stylesheet idiom of '~path' meaning a path in a
    // modules folder and a unprefixed 'path' meaning a relative path like
    // './path'.
    path = loaderUtils.urlToRequest(path, options.root);
    // First try with a '.styl' extension.
    return whenWebpackResolver(context, path + '.styl')
      // If the user adds ".styl" to resolve.extensions, webpack can find
      // index files like stylus but it uses all of webpack's configuration,
      // by default for example the module could be web_modules.
      .catch(function() { return whenWebpackResolver(context, path); })
      .catch(function() { return null; })
      .then(function(result) {
        return Array.isArray(result) && result[1] && result[1].path || result
      });
  };

  if (options.preferPathResolver === 'webpack') {
    return [
      webpackResolve,
      stylusFile,
      stylusIndex
    ];
  }
  else {
    return [
      stylusFile,
      stylusIndex,
      webpackResolve
    ];
  }
}
```
- example usage
```shell
...
try {
  var inputFileSystem = this._compiler.inputFileSystem;
  readFile = inputFileSystem.readFile.bind(inputFileSystem);
} catch (error) {
  readFile = fs.readFile;
}

var boundResolvers = PathCache.resolvers(options, this.resolve);
var pathCacheHelpers = {
  resolvers: boundResolvers,
  readFile: readFile,
};

// Use plugins here so that resolve related side effects can be used while we resolve imports.
(Array.isArray(use) ? use : [use]).forEach(styl.use, styl);
...
```



# <a name="apidoc.module.stylus-loader.pathcache.prototype"></a>[module stylus-loader.pathcache.prototype](#apidoc.module.stylus-loader.pathcache.prototype)

#### <a name="apidoc.element.stylus-loader.pathcache.prototype.allDeps"></a>[function <span class="apidocSignatureSpan">stylus-loader.pathcache.prototype.</span>allDeps ()](#apidoc.element.stylus-loader.pathcache.prototype.allDeps)
- description and source-code
```javascript
allDeps = function () {
  var deps = [];
  for (var dirname in this.contexts) {
    for (var path in this.contexts[dirname]) {
      if (this.contexts[dirname][path]) {
        deps = deps.concat(this.contexts[dirname][path].path);
      }
    }
  }
  return deps;
}
```
- example usage
```shell
...
    .then(function(cache) {
return PathCache
  .createFromFile(pathCacheHelpers, cache, source, options.filename);
    })
    .then(function(importPathCache) {
// CachedPathEvaluator will use this PathCache to find its dependencies.
options.cache = importPathCache;
importPathCache.allDeps().forEach(function(f) {
  self.addDependency(path.normalize(f));
});

// var paths = importPathCache.origins;

styl.render(function(err, css) {
  if (err) {
...
```

#### <a name="apidoc.element.stylus-loader.pathcache.prototype.find"></a>[function <span class="apidocSignatureSpan">stylus-loader.pathcache.prototype.</span>find (path, dirname)](#apidoc.element.stylus-loader.pathcache.prototype.find)
- description and source-code
```javascript
find = function (path, dirname) {
  if (this.contexts[dirname] && this.contexts[dirname][path]) {
    return this.contexts[dirname][path].path;
  } else if (this.simpleContext[path]) {
    return this.simpleContext[path].path;
  } else if (/.styl$/.test(path)) {
    // A user can specify @import 'something.styl' but if they specify
    // @import 'something' stylus adds .styl, we drop that here to see if we
    // looked for it without .styl.
    return this.find(path.replace(/.styl$/, ''), dirname);
  } else {
    return undefined;
  }
}
```
- example usage
```shell
...
if (!literal && !/\.styl$/i.test(path)) path += '.styl';

/*****************************************************************************
* THIS IS THE ONLY BLOCK THAT DIFFERS FROM THE ACTUAL STYLUS IMPLEMENTATION. *
*****************************************************************************/
// Lookup
var dirname = this.paths[this.paths.length - 1];
found = this.cache.find(path, dirname);
index = this.cache.isIndex(path, dirname);
if (!found) {
  found = utils.find(path, this.paths, this.filename);
  if (!found) {
    found = utils.lookupIndex(name, this.paths, this.filename);
    index = true;
  }
...
```

#### <a name="apidoc.element.stylus-loader.pathcache.prototype.isIndex"></a>[function <span class="apidocSignatureSpan">stylus-loader.pathcache.prototype.</span>isIndex (path, dirname)](#apidoc.element.stylus-loader.pathcache.prototype.isIndex)
- description and source-code
```javascript
isIndex = function (path, dirname) {
  if (this.contexts[dirname] && this.contexts[dirname][path]) {
    return this.contexts[dirname][path].index;
  } else {
    return undefined;
  }
}
```
- example usage
```shell
...

/*****************************************************************************
* THIS IS THE ONLY BLOCK THAT DIFFERS FROM THE ACTUAL STYLUS IMPLEMENTATION. *
*****************************************************************************/
// Lookup
var dirname = this.paths[this.paths.length - 1];
found = this.cache.find(path, dirname);
index = this.cache.isIndex(path, dirname);
if (!found) {
  found = utils.find(path, this.paths, this.filename);
  if (!found) {
    found = utils.lookupIndex(name, this.paths, this.filename);
    index = true;
  }
}
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# api documentation for  [leaflet (v1.0.3)](https://github.com/Leaflet/Leaflet#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-leaflet.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-leaflet) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-leaflet.svg)](https://travis-ci.org/npmdoc/node-npmdoc-leaflet)
#### JavaScript library for mobile-friendly interactive maps

[![NPM](https://nodei.co/npm/leaflet.png?downloads=true)](https://www.npmjs.com/package/leaflet)

[![apidoc](https://npmdoc.github.io/node-npmdoc-leaflet/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-leaflet_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-leaflet/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-leaflet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-leaflet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/Leaflet/Leaflet/issues"
    },
    "dependencies": {},
    "description": "JavaScript library for mobile-friendly interactive maps",
    "devDependencies": {
        "eslint": "^3.5.0 <3.6.0",
        "eslint-config-mourner": "^2.0.1",
        "git-rev": "^0.2.1",
        "happen": "~0.3.1",
        "jake": "~8.0.12",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "~1.1.1",
        "karma-firefox-launcher": "~1.0.0",
        "karma-mocha": "^1.2.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "karma-safari-launcher": "~1.0.0",
        "leafdoc": "^1.4.1",
        "mocha": "^3.1.0",
        "phantomjs-prebuilt": "^2.1.12",
        "prosthetic-hand": "^1.3.1",
        "source-map": "^0.5.6",
        "uglify-js": "~2.7.3"
    },
    "directories": {},
    "dist": {
        "shasum": "1f401b98b45c8192134c6c8d69686253805007c8",
        "tarball": "https://registry.npmjs.org/leaflet/-/leaflet-1.0.3.tgz"
    },
    "eslintConfig": {
        "root": true,
        "globals": {
            "L": true
        },
        "env": {
            "commonjs": true,
            "amd": true,
            "node": false
        },
        "extends": "mourner",
        "rules": {
            "no-mixed-spaces-and-tabs": [
                2,
                "smart-tabs"
            ],
            "indent": [
                2,
                "tab",
                {
                    "VariableDeclarator": 0
                }
            ],
            "curly": 2,
            "spaced-comment": 2,
            "strict": 0,
            "wrap-iife": 0,
            "key-spacing": 0,
            "consistent-return": 0
        }
    },
    "gitHead": "ed36a04aefd12cb92c78074fe63a8e460db1d464",
    "homepage": "https://github.com/Leaflet/Leaflet#readme",
    "keywords": [
        "gis",
        "map"
    ],
    "license": "BSD-2-Clause",
    "main": "dist/leaflet-src.js",
    "maintainers": [
        {
            "name": "ivansanchez",
            "email": "ivan@sanchezortega.es"
        },
        {
            "name": "liedman",
            "email": "per@liedman.net"
        },
        {
            "name": "mourner",
            "email": "agafonkin@gmail.com"
        },
        {
            "name": "ybon",
            "email": "yb@enix.org"
        }
    ],
    "name": "leaflet",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/Leaflet/Leaflet.git"
    },
    "scripts": {
        "build": "jake build",
        "release": "./build/publish.sh",
        "test": "jake test"
    },
    "style": "dist/leaflet.css",
    "version": "1.0.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module leaflet](#apidoc.module.leaflet)
1.  [function <span class="apidocSignatureSpan">leaflet.</span>expect (obj)](#apidoc.element.leaflet.expect)

#### [module leaflet.expect](#apidoc.module.leaflet.expect)
1.  [function <span class="apidocSignatureSpan">leaflet.</span>expect (obj)](#apidoc.element.leaflet.expect.expect)
1.  [function <span class="apidocSignatureSpan">leaflet.expect.</span>Assertion (obj, flag, parent)](#apidoc.element.leaflet.expect.Assertion)
1.  [function <span class="apidocSignatureSpan">leaflet.expect.</span>eql (actual, expected)](#apidoc.element.leaflet.expect.eql)
1.  string <span class="apidocSignatureSpan">leaflet.expect.</span>version



# <a name="apidoc.module.leaflet"></a>[module leaflet](#apidoc.module.leaflet)

#### <a name="apidoc.element.leaflet.expect"></a>[function <span class="apidocSignatureSpan">leaflet.</span>expect (obj)](#apidoc.element.leaflet.expect)
- description and source-code
```javascript
function expect(obj) {
  return new Assertion(obj);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.leaflet.expect"></a>[module leaflet.expect](#apidoc.module.leaflet.expect)

#### <a name="apidoc.element.leaflet.expect.expect"></a>[function <span class="apidocSignatureSpan">leaflet.</span>expect (obj)](#apidoc.element.leaflet.expect.expect)
- description and source-code
```javascript
function expect(obj) {
  return new Assertion(obj);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leaflet.expect.Assertion"></a>[function <span class="apidocSignatureSpan">leaflet.expect.</span>Assertion (obj, flag, parent)](#apidoc.element.leaflet.expect.Assertion)
- description and source-code
```javascript
function Assertion(obj, flag, parent) {
  this.obj = obj;
  this.flags = {};

  if (undefined != parent) {
    this.flags[flag] = true;

    for (var i in parent.flags) {
      if (parent.flags.hasOwnProperty(i)) {
        this.flags[i] = true;
      }
    }
  }

  var $flags = flag ? flags[flag] : keys(flags)
    , self = this

  if ($flags) {
    for (var i = 0, l = $flags.length; i < l; i++) {
      // avoid recursion
      if (this.flags[$flags[i]]) continue;

      var name = $flags[i]
        , assertion = new Assertion(this.obj, name, this)

      if ('function' == typeof Assertion.prototype[name]) {
        // clone the function, make sure we dont touch the prot reference
        var old = this[name];
        this[name] = function () {
          return old.apply(self, arguments);
        }

        for (var fn in Assertion.prototype) {
          if (Assertion.prototype.hasOwnProperty(fn) && fn != name) {
            this[name][fn] = bind(assertion[fn], assertion);
          }
        }
      } else {
        this[name] = assertion;
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leaflet.expect.eql"></a>[function <span class="apidocSignatureSpan">leaflet.expect.</span>eql (actual, expected)](#apidoc.element.leaflet.expect.eql)
- description and source-code
```javascript
function eql(actual, expected) {
  // 7.1. All identical values are equivalent, as determined by ===.
  if (actual === expected) {
    return true;
  } else if ('undefined' != typeof Buffer
      && Buffer.isBuffer(actual) && Buffer.isBuffer(expected)) {
    if (actual.length != expected.length) return false;

    for (var i = 0; i < actual.length; i++) {
      if (actual[i] !== expected[i]) return false;
    }

    return true;

  // 7.2. If the expected value is a Date object, the actual value is
  // equivalent if it is also a Date object that refers to the same time.
  } else if (actual instanceof Date && expected instanceof Date) {
    return actual.getTime() === expected.getTime();

  // 7.3. Other pairs that do not both pass typeof value == "object",
  // equivalence is determined by ==.
  } else if (typeof actual != 'object' && typeof expected != 'object') {
    return actual == expected;

  // 7.4. For all other Object pairs, including Array objects, equivalence is
  // determined by having the same number of owned properties (as verified
  // with Object.prototype.hasOwnProperty.call), the same set of keys
  // (although not necessarily the same order), equivalent values for every
  // corresponding key, and an identical "prototype" property. Note: this
  // accounts for both named and indexed properties on Arrays.
  } else {
    return objEquiv(actual, expected);
  }
}
```
- example usage
```shell
...
 * Checks if the obj sortof equals another.
 *
 * @api public
 */

Assertion.prototype.eql = function (obj) {
  this.assert(
      expect.eql(obj, this.obj)
    , function(){ return 'expected ' + i(this.obj) + ' to sort of equal ' + i(obj) }
    , function(){ return 'expected ' + i(this.obj) + ' to sort of not equal ' + i(obj) });
  return this;
};

/**
 * Assert within start to finish (inclusive).
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmdoc-leaflet

#### basic api documentation for  [leaflet (v1.0.3)](https://github.com/Leaflet/Leaflet#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-leaflet.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-leaflet) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-leaflet.svg)](https://travis-ci.org/npmdoc/node-npmdoc-leaflet)

#### JavaScript library for mobile-friendly interactive maps

[![NPM](https://nodei.co/npm/leaflet.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/leaflet)

- [https://npmdoc.github.io/node-npmdoc-leaflet/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-leaflet/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-leaflet/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-leaflet/build/apidoc.html)

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
            "name": "ivansanchez"
        },
        {
            "name": "liedman"
        },
        {
            "name": "mourner"
        },
        {
            "name": "ybon"
        }
    ],
    "name": "leaflet",
    "optionalDependencies": {},
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
    "version": "1.0.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

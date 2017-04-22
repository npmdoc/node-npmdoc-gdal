# npmdoc-gdal

#### api documentation for  [gdal (v0.9.4)](https://github.com/naturalatlas/node-gdal#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gdal.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gdal) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gdal.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gdal)

#### Bindings to GDAL (Geospatial Data Abstraction Library)

[![NPM](https://nodei.co/npm/gdal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gdal)

- [https://npmdoc.github.io/node-npmdoc-gdal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gdal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gdal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gdal/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gdal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gdal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brandon Reavis",
        "url": "https://github.com/brandonreavis"
    },
    "binary": {
        "module_name": "gdal",
        "module_path": "./lib/binding/{node_abi}-{platform}-{arch}",
        "remote_path": "./{module_name}/v{version}/{toolset}/",
        "host": "https://mapbox-node-binary.s3.amazonaws.com",
        "package_name": "{node_abi}-{platform}-{arch}.tar.gz"
    },
    "bugs": {
        "url": "https://github.com/naturalatlas/node-gdal/issues"
    },
    "contributors": [
        {
            "name": "Anand Thakker"
        },
        {
            "name": "Brandon Reavis"
        },
        {
            "name": "Brandon Reavis"
        },
        {
            "name": "Brian Reavis"
        },
        {
            "name": "Dane Springmeyer"
        },
        {
            "name": "David Tudury"
        },
        {
            "name": "Jon Woyame"
        },
        {
            "name": "Jérôme Desboeufs"
        },
        {
            "name": "Ryan Clark"
        },
        {
            "name": "Sean Gillies"
        },
        {
            "name": "Seth Fitzsimmons"
        },
        {
            "name": "Tim Schaub"
        },
        {
            "name": "Tom Hughes"
        },
        {
            "name": "Wilhelm Berg"
        },
        {
            "name": "Wilhelm Berg"
        },
        {
            "name": "Young Hahn"
        },
        {
            "name": "Zac McCormick"
        },
        {
            "name": "bergwerkgis"
        },
        {
            "name": "gretacb"
        },
        {
            "name": "Zac McCormick"
        }
    ],
    "dependencies": {
        "nan": "~2.5.0",
        "node-pre-gyp": "~0.6.27"
    },
    "description": "Bindings to GDAL (Geospatial Data Abstraction Library)",
    "devDependencies": {
        "aws-sdk": "~2.0.25",
        "chai": "^3.4.1",
        "eslint": "^1.10.1",
        "eslint-config-naturalatlas": "latest",
        "gh-pages": "~0.2.0",
        "mocha": "^2.3.4",
        "yuidoc-lucid-theme": "~0.1.1",
        "yuidocjs": "~0.3.50"
    },
    "directories": {},
    "dist": {
        "shasum": "6dad4abb8ffb3e0d51150fb7935ad7c622c81818",
        "tarball": "https://registry.npmjs.org/gdal/-/gdal-0.9.4.tgz"
    },
    "engineStrict": true,
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "5c894cc6fda3f2c08fbe95fe2efc5e03d9bf6e46",
    "homepage": "https://github.com/naturalatlas/node-gdal#readme",
    "keywords": [
        "gdal",
        "libgdal",
        "gis",
        "geo",
        "geos",
        "geography",
        "geospatial",
        "raster",
        "vector",
        "gtiff",
        "geojson",
        "mapping"
    ],
    "license": "Apache-2.0",
    "main": "./lib/gdal.js",
    "maintainers": [
        {
            "name": "brandonreavis"
        },
        {
            "name": "brianreavis"
        },
        {
            "name": "springmeyer"
        },
        {
            "name": "bergwerkgis"
        }
    ],
    "name": "gdal",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/naturalatlas/node-gdal.git"
    },
    "scripts": {
        "install": "node-pre-gyp install --fallback-to-build",
        "postpublish": "npm run publish-yuidoc",
        "preinstall": "npm install node-pre-gyp",
        "publish-yuidoc": "npm run yuidoc && node ./scripts/publish-docs.js",
        "test": "mocha test -R tap --timeout 600000 --no-colors -gc --require ./test/_common.js",
        "test-syntax": "eslint lib test --fix",
        "yuidoc": "yuidoc --extension .js,.cpp,.hpp"
    },
    "url": "http://github.com/naturalatlas/node-gdal",
    "version": "0.9.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

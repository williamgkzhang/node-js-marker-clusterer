Node Marker Clusterer
==============

A Google Maps JavaScript API v3 library to create and manage per-zoom-level clusters for large amounts of markers.

Converted to [commonJS](http://www.commonjs.org/) format to be used with [browserify](http://browserify.org/) and added additional unit test to ensure the constructor gets instantiated and contains the original public methods.

## Install
```npm install node-js-marker-clusterer```

## Usage
```var MarkerClusterer = require('node-js-marker-clusterer');```

```var mc = new MarkerClusterer(map, markers);```

### Run test
Requires mocha and then dependecies from package.json to be installed, then:

```npm test```

## Docs
The logic of the module it's unchanged and it's forked from it's original author from [js-marker-clusterer](https://github.com/googlemaps/js-marker-clusterer)

## License
Apache 2.0

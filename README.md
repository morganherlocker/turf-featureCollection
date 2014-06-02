turf-featureCollection
======================
[![Build Status](https://travis-ci.org/Turfjs/turf-featureCollection.svg)](https://travis-ci.org/Turfjs/turf-featureCollection)

Creates a geojson FeatureCollection based on an array of features.

```js
var featurecollection = require('turf-featurecollection')
var point = require('turf-point')

var pt1 = point(-75.343, 39.984, {name: 'Location A'})
var pt2 = point(-75.833, 39.284, {name: 'Location B'})
var pt3 = point(-75.534, 39.123, {name: 'Location C'})

var fc = featurecollection([pt1, pt2, pt3])
console.log(fc)
```
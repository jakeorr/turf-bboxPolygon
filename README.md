turf-bboxPolygon
================

Takes a bbox and returns the equivalent polygon feature.

```javascript
var t = require('turf')
var bbox = [0,0,10,10]

t.bboxPolygon(bbox, function(err, poly){
  if(err) throw err
  console.log(poly)
})
```
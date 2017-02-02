# jQuery Geocoder

Easily get information about the browser.

### Geocode

```js
var address = '124 Apple St New Haven, CT'

$.geo.geocode(address, {
    success: function(data) {
        console.log(data);
    },
    error: function() {
        //
    }
});
```

### Reverse Geocode
```js
var point = {
    lat: 41.310726,
    lng: -72.929916
};

$.geo.reverseGeocode(point, {
    success: function(data) {
        console.log(data);
    },
    error: function() {
        //
    }
});
```
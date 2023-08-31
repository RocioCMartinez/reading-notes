# Location

## [Location Resource](https://developer.android.com/training/location/retrieve-current)

What are the benefits and downfalls of using the ‘getLastLocation()’ method to get your device’s location?

This method will get a locaton estimate much quicker, and minimizes battery usage. The downfall is that the location could be out of date based on the last point a location was tracked(saved).

What about the ‘getCurrentLocation()’ method?

This method is more accurate and consistent, this is the recommended method for location access. The downfall can be causing active location computation to run on the device.

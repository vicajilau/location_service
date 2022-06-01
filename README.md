This lightweight package allows in a very simple and optimized way to obtain details about the platform on which it is running. It's multi-platform, and supports mobile, desktop,
and the browser.

## Using

[LocationService][] is a module that wraps the Flutter http package to integrate it into other projects.

This returns an encapsulated object for the location called [LocationModel][].

```dart
import 'package:location_service/location_service.dart';

LocationService location = LocationService();
LocationModel userLocation = await location.localizeUserPosition();
```

[LocationService]: https://github.com/vicajilau/location_service/blob/master/lib/src/location_service.dart
[LocationModel]: https://github.com/vicajilau/location_service/blob/master/lib/src/model/location_model.dart

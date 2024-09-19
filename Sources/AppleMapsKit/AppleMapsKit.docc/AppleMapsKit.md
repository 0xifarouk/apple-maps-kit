# ``AppleMapsKit``

🗺️ Integrate the Apple Maps Server API into Swift server applications

## Overview

### Getting Started

Use the SPM string to easily include the dependendency in your `Package.swift` file

```swift
.package(url: "https://github.com/fpseverino/apple-maps-kit.git", from: "0.1.0")
```

and add it to your target's dependencies:

```swift
.product(name: "AppleMapsKit", package: "apple-maps-kit")
```

## Topics

### Essentials

- ``AppleMapsClient``
- ``MapRegion``
- ``Location``
- ``StructuredAddress``

### Geocoding

- <doc:Geocode>
- <doc:ReverseGeocode>
- ``Place``

### Searching

- <doc:Search>
- <doc:SearchAutoComplete>
- ``SearchResponse``
- ``AutocompleteResult``
- ``PoiCategory``
- ``SearchResultType``
- ``SearchRegionPriority``
- ``AddressCategory``

### Directions

- <doc:GettingDirections>
- ``DirectionsResponse``
- ``DirectionsTransportType``
- ``DirectionsAvoid``

### ETAs

- <doc:GettingETAs>
- ``Eta``
- ``EtaTransportType``

### Errors

- ``ErrorResponse``
- ``AppleMapsKitError``

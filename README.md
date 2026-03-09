# SuperAwesome iOS SDK

Swift Package Manager distribution for the SuperAwesome iOS SDK.

## Installation

Add the package to your project in Xcode:

1. Go to **File → Add Package Dependencies...**
2. Enter the repository URL for this package
3. Select the version you want to use

Or add it to your `Package.swift`:

```swift
dependencies: [
    .package(url: "https://github.com/superawesome-org/sa-mobile-sdk-ios-spm", from: "10.0.0")
]
```

### Available Libraries

| Library | Description |
|---------|-------------|
| `SuperAwesome` | Core SDK for displaying ads |
| `SuperAwesomeAdMob` | AdMob mediation adapter |

## Requirements

- iOS 10.0+
- Swift 5.7+
- Xcode 14+

## Documentation

For integration guides and API reference, visit the [SuperAwesome documentation](https://sdks.superawesome.com/).

## License

Copyright SuperAwesome. All rights reserved.

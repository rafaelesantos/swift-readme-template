# Product Name
> Short blurb about what your product does.

[![Swift Version][swift-image]][swift-url]
[![License][license-image]][license-url]

One to two paragraph statement about your product and what it does.

![](header.png)

## Installation

Add this project on your `Package.swift`

```swift
import PackageDescription

let package = Package(
    dependencies: [
        .Package(url: "https://github.com/user/project.git", majorVersion: 0, minor: 0)
    ]
)
```

## Usage example


```swift
import Project
let proj = Class(param: String?)
proj.run()
```

[swift-image]:https://img.shields.io/badge/swift-5-orange.svg
[swift-url]: https://swift.org/
[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-url]: LICENSE

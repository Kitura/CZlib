# CZlib

Swift module maps for [zlib](https://www.zlib.net/), which allow you to use the zlib C library in your Swift project.

## Usage

#### Add dependencies

Add the `CZlib` package to the dependencies within your application’s `Package.swift` file. Substitute `"x.x.x"` with the latest `CZlib` [release](https://github.com/IBM-Swift/CZlib/releases).

```swift
.package(url: "https://github.com/IBM-Swift/CZlib.git", from: "x.x.x")
```

Add `CZlib` to your target's dependencies:

```swift
.target(name: "example", dependencies: ["CZlib"]),
```

#### Import package

```swift
import CZlib
```

## Community

We love to talk server-side Swift, and Kitura. Join our [Slack](http://swift-at-ibm-slack.mybluemix.net/) to meet the team!

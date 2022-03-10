# UIPilot

[![Swift](https://img.shields.io/badge/Swift-5.5-orange?style=flat-square)](https://img.shields.io/badge/Swift-5.5-Orange?style=flat-square)
[![Platforms](https://img.shields.io/badge/Platforms-macOS_iOS_tvOS_watchOS-yellowgreen?style=flat-square)](https://img.shields.io/badge/Platforms-macOS_iOS_tvOS_watchOS-Green?style=flat-square)
[![Swift Package Manager](https://img.shields.io/badge/Swift_Package_Manager-compatible-orange?style=flat-square)](https://img.shields.io/badge/Swift_Package_Manager-compatible-orange?style=flat-square)

<img src="https://github.com/canopas/UIPilot/blob/main/docs/assets/intro-image.jpg?raw=true" height="350" />

## Why another SwiftUI navigation library?
- UIPilot is not a replacement of the SwiftUI's `NavigationView`, it's rather a wrapper around it that you would have likely written. Thus all standard `NavigationView` features like title, swipe gesture, topbar etc. are available by default.
- APIs are inspired by the android, flutter and web based routers - Very simple and easy to use.
- Typesafe navigation - Routing to wrong path will fail at compile time rather than runtime.
- Typesafe parameters - Routing with wrong parameters will fail at compile time rather than runtime.
- Very tiny library - it's barely 100 lines of code.

## Documentation
Visit [the website](https://canopas.github.io/UIPilot/) for documentation and examples.

## Complex use cases
The library is designed to meet simples use cases as well as complex ones. You can also have nested `UIPilot` as many as you like!

For example,. It's very easy to acheive split screen like behavior.

<img src="https://github.com/canopas/UIPilot/blob/main/docs/assets/complex-routing.gif?raw=true" height="500" />

Please have a look at the [article](https://blog.canopas.com/swiftui-complex-navigation-made-easier-with-uipilot-5b33279f3476) for more information of the implementation.

## Installation

### Swift Package Manager

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for automating the distribution of Swift code and is integrated into the `swift` compiler. 

Once you have your Swift package set up, adding UIPilot as a dependency is as easy as adding it to the `dependencies` value of your `Package.swift`.

```swift
dependencies: [
    .package(url: "https://github.com/canopas/UIPilot.git", .upToNextMajor(from: "1.1.5"))
]
```

### CocoaPods

[CocoaPods][] is a dependency manager for Cocoa projects. For usage and installation instructions, visit their website. To integrate UIPilot into your Xcode project using CocoaPods, specify it in your Podfile:

    target 'YourAppTargetName' do
        pod 'UIPilot', '~> 1.1.5'
    end

[CocoaPods]: https://cocoapods.org

# Bugs and Feedback
For bugs, questions and discussions please use the [Github Issues](https://github.com/canopas/UIPilot/issues).

# Credits

UIPilot is owned and maintained by the [Canopas](https://canopas.com/) team. You can follow them on Twitter at [@canopassoftware](https://twitter.com/canopassoftware) for project updates and releases.

# Licence

```
Copyright 2022 Canopas Software LLP

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

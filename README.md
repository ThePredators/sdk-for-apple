# Appwrite Apple SDK

![Swift Package Manager](https://img.shields.io/github/v/release/appwrite/sdk-for-apple.svg?color=green&style=flat-square)
![License](https://img.shields.io/github/license/appwrite/sdk-for-apple.svg?style=flat-square)
![Version](https://img.shields.io/badge/api%20version-0.13.0-blue.svg?style=flat-square)
[![Build Status](https://img.shields.io/travis/com/appwrite/sdk-generator?style=flat-square)](https://travis-ci.com/appwrite/sdk-generator)
[![Twitter Account](https://img.shields.io/twitter/follow/appwrite?color=00acee&label=twitter&style=flat-square)](https://twitter.com/appwrite)
[![Discord](https://img.shields.io/discord/564160730845151244?label=discord&style=flat-square)](https://appwrite.io/discord)

**This SDK is compatible with Appwrite server version 0.13.x. For older versions, please check [previous releases](https://github.com/appwrite/sdk-for-apple/releases).**

Appwrite is an open-source backend as a service server that abstract and simplify complex and repetitive development tasks behind a very simple to use REST API. Appwrite aims to help you develop your apps faster and in a more secure way. Use the Apple SDK to integrate your app with the Appwrite server to easily start interacting with all of Appwrite backend APIs and tools. For full API documentation and tutorials go to [https://appwrite.io/docs](https://appwrite.io/docs)

![Appwrite](https://appwrite.io/images/github.png)

## Installation

### Xcode with Swift Package Manager

The Appwrite Swift SDK is available via Swift Package Manager. In order to use the Appwrite Swift SDK from Xcode, select File > **Add Packages**

In the dialog that appears, enter the Appwrite Swift SDK [package URL](git@github.com:appwrite/sdk-for-apple.git) in the search field. Once found, select `sdk-for-apple`.

On the right, select your version rules and ensure your desired target is selected in the **Add to Project** field.

Now click add package and you're done!

### Swift Package Manager

Add the package to your `Package.swift` dependencies:

```swift
    dependencies: [
        .package(url: "git@github.com:appwrite/sdk-for-apple.git", from: "0.3.0"),
    ],
```

Then add it to your target:

```swift
    targets: [
        .target(
            name: "YourAppTarget",
            dependencies: [
                .product(name: "", package: "sdk-for-apple")
            ]
        ),
```


## Contribution

This library is auto-generated by Appwrite custom [SDK Generator](https://github.com/appwrite/sdk-generator). To learn more about how you can help us improve this SDK, please check the [contribution guide](https://github.com/appwrite/sdk-generator/blob/master/CONTRIBUTING.md) before sending a pull-request.

## License

Please see the [BSD-3-Clause license](https://raw.githubusercontent.com/appwrite/appwrite/master/LICENSE) file for more information.
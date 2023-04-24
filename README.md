
<p align="center">
<img src="logo.png" width="150" max-width="50%" alt="Fox Labs" />
</p>

<p align="center">
<a href="https://github.com/Nickelfox">Fox Labs</a>
|
<a href="https://github.com/Nickelfox/AnyErrorKit">AnyErrorKit</a>
</p>

`AnyErrorKit` is a Swift library that provides a convenient way to handle and manage errors in iOS applications. It offers a set of tools and utilities for handling errors in a type-safe and flexible manner, allowing developers to write more robust and reliable error handling code. It works as a wrapper around `Error` protocol for even more better usability.

## Installation
#### <i class="icon-file"></i>**CocoaPods**
[CocoaPods](https://cocoapods.org) is the dependency manager for Cocoa Libraries. You can install Cocoapods using the following command:

> `$ sudo gem install cocoapods`

If you wish to integrate `AnyErrorKit` in your project, then make following changes in your `Podfile`:

```  
platform :ios, '10.0'
use_frameworks!
target 'YourAppName' do
pod 'AnyErrorKit'
end
```

After saving `Podfile`. Run the following command:

> `$ pod install`


#### <i class="icon-pencil"></I>**Install using Swift Package Manager**

The [Swift Package Manager](https://swift.org/package-manager) is a tool for automating the distribution of Swift code and is integrated into the swift compiler.

Once you have your Swift package set up, adding AnyErrorKit as a dependency is as easy as adding it to the ```dependencies``` value of your ```Package.swift```.

```
dependencies: [
    .package(url: "https://github.com/Nickelfox/AnyErrorKit", .branch("develop"))
]
```

#### <i class="icon-pencil"></I>**Manually**
If you don't want to use any dependency manager in your project, you can install this library manually too.
Just download and add the `Source` folder to your project.

## Features

AnyErrorKit library offers the following features:

- Error Handling: AnyErrorKit provides a powerful error handling mechanism that allows developers to define custom error types conforming to the Error protocol, and easily handle and manage errors in a type-safe way.
- Error Wrapping: AnyErrorKit allows developers to wrap any error type, including system errors, third-party library errors, or custom application-specific errors, into a unified error type called AnyError. This makes it easy to handle different types of errors using a single error type.
- Error Recovery: AnyErrorKit provides a set of utility functions that allow developers to easily recover from errors and provide fallback values or alternative error handling paths, making it easier to handle errors gracefully and provide a better user experience.
- Error Transformation: AnyErrorKit enables developers to transform errors into other error types, providing a way to map or convert errors from one type to another. This can be useful when adapting errors from different sources or when dealing with errors in a consistent manner across different parts of an application.
- Error Logging: AnyErrorKit includes built-in logging capabilities that allow developers to log errors with customizable logging levels, helping with debugging and troubleshooting during development and production.





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

- Type-erased error handling: AnyError allows you to work with any error type, making it flexible and convenient to handle errors in Swift applications.
- Error representation: AnyError provides a way to represent errors as values, making it easier to pass around and manipulate errors in Swift code.
- Error conversion: AnyError provides utility methods to convert between different error types, allowing you to convert errors from one type to another.
- Error chaining: AnyError allows you to chain multiple errors together, making it easier to represent complex error scenarios in Swift applications.




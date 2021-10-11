
<p align="center">
<img src="logo.png" width="150" max-width="50%" alt="Fox Labs" />
</p>

<p align="center">
<a href="https://github.com/Nickelfox">Fox Labs</a>
|
<a href="https://github.com/Nickelfox/AnyErrorKit">AnyErrorKit</a>
</p>

`AnyErrorKit` is a wrapper around `Error` protocol for even more better usability.

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

Install using Swift Package Manager:

The [Swift Package Manager](https://swift.org/package-manager) is a tool for automating the distribution of Swift code and is integrated into the swift compiler.

Once you have your Swift package set up, adding FLUtilities as a dependency is as easy as adding it to the ```dependencies``` value of your ```Package.swift```.

```
dependencies: [
    .package(url: "https://github.com/Nickelfox/FLUtilities", .branch("develop"))
]
```

#### <i class="icon-pencil"></I>**Manually**
If you don't want to use any dependency manager in your project, you can install this library manually too.
Just download and add the `Source` folder to your project.






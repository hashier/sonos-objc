sonos-objc
==========

An Objective-C API for controlling Sonos Devices

The aim of this library is to create a simple to use, yet useful API to control Sonos Devices via SOAP. It depends on AFNetworking (iOS and OS X), CocoaAsyncSocket (iOS and OS X) and XMLReader.h/m (iOS and OS X)

# Installation with CocoaPods

CocoaPods is a dependency manager for Objective-C, which automates and simplifies the process of using 3rd-party libraries like sonos-objc in your projects. See the [Cocoapods Website for more information](http://cocoapods.org/).

**Podfile**

```rb
pod 'Sonos', :git => 'https://github.com/getsenic/sonos-objc.git', :branch => 'master'
```

# Usage

Use `SonosDiscover` to discover all sonos controllers.

See `SonosController.h` for usage on how to control speakers.

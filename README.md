# BandSensorSwift
Swift version of the Microsoft Band Kit sample app BandSensor

This is a port of the BandSensor example from the Microsoft Band Kit SDK for iOS samples. The SDK can be found at http://developer.microsoftband.com/

## Dependencies

Uses the Microsoft Band Kit (MSB) for iOS (included). You can get the latest version from: http://developer.microsoftband.com/
Demonstrates use of MSB with Swift. Written with Swift 1.2 and Xcode 6.3 Beta.

Requires a Microsoft Band paired with your iPhone (there is no simulator, you need a physical band).

##Using

Download, build and run.

## Authors

Mark Thistle, http://droolfactory.blogspot.com

## About the Code

This is a straight port. The only real difference is the use of a dispatch_async with block instead of using performSelector to handle the sensor unsubscribe after 60 seconds.

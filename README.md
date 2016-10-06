# Swift Development

## Swift Style Guide
- [Swift - Apple Developer] (https://developer.apple.com/library/prerelease/content/documentation/Swift/Conceptual/Swift_Programming_Language/TheBasics.html#//apple_ref/doc/uid/TP40014097-CH5-ID309)
- [raywenderlich.com Swift Style Guide] (https://github.com/raywenderlich/swift-style-guide/blob/master/README.markdown)
- [iOS Good Practices] (https://github.com/futurice/ios-good-practices/blob/master/README.md)

## Swift 3.0 Changes

### presentViewController → present
------
```
present(imagePicker, animated: true, completion: nil)
```

### popViewControllerAnimated → popViewController
------
```
_ = self.navigationController?.popViewController(animated: true)
```

### dismissViewControllerAnimated → dismiss
------
```
dismiss(animated: true, completion: nil)
```

### NSDateFormatter → DateFormatter
------
```
let myDateFormatter: DateFormatter = DateFormatter()
```
 
### CGRectMake → CGRect
------
```
let rect = CGRect(x: 0, y: 0, width: 100, height: 100)
let size = CGSize(width: 100, height: 100)
let point = CGPoint(x: 0, y: 0)
```

### NSUserDefaults → UserDefaults
------

### NSNotificationCenter → NotificationCenter
------

### NSTimeZone → TimeZone
------

### NSDateComponentsFormatter → DateComponentsFormatter
------

## Info.plist Keys and Value List
- [About Info.plist Keys and Values] (https://developer.apple.com/library/content/documentation/General/Reference/InfoPlistKeyReference/Introduction/Introduction.html)

- [Cocoa Keys] (https://developer.apple.com/library/content/documentation/General/Reference/InfoPlistKeyReference/Articles/CocoaKeys.html)

```
Apple Music:
<key>NSAppleMusicUsageDescription</key>
<string>My description about why I need this capability</string>
Bluetooth:
<key>NSBluetoothPeripheralUsageDescription</key>  
<string>My description about why I need this capability</string>
Calendar:
<key>NSCalendarsUsageDescription</key>
<string>My description about why I need this capability</string>
Camera:
<key>NSCameraUsageDescription</key>
<string>My description about why I need this capability</string>
Contacts:
<key>NSContactsUsageDescription</key>
<string>My description about why I need this capability</string>
Health Share:
<key>NSHealthShareUsageDescription</key>
<string>My description about why I need this capability</string>
Health Update:
<key>NSHealthUpdateUsageDescription</key>
<string>My description about why I need this capability</string>
Home Kit:
<key>NSHomeKitUsageDescription</key>
<string>My description about why I need this capability</string>
Location:
<key>NSLocationUsageDescription</key>
<string>My description about why I need this capability</string>
Location (Always):
<key>NSLocationAlwaysUsageDescription</key>
<string>My description about why I need this capability</string>
Location (When in use):
<key>NSLocationWhenInUseUsageDescription</key>
<string>My description about why I need this capability</string>
Microphone:
<key>NSMicrophoneUsageDescription</key>
<string>My description about why I need this capability</string>
Motion (Accelerometer):
<key>NSMotionUsageDescription</key>
<string>My description about why I need this capability</string>
Photo Library:
<key>NSPhotoLibraryUsageDescription</key>
<string>My description about why I need this capability</string>
Reminders:
<key>NSRemindersUsageDescription</key>
<string>My description about why I need this capability</string>
Siri:
<key>NSSiriUsageDescription</key>
<string>My description about why I need this capability</string>
Speech Recognition:
<key>NSSpeechRecognitionUsageDescription</key>
<string>My description about why I need this capability</string>
```

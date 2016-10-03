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

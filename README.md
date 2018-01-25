# cordova-plugin-ios-permissions
This plugin prevents crashes in iOS apps due to missing entries in the plist file.

# Why?
File inputs suddenly didn't work in iOS applications created using PhoneGap Build. When clicking on a file input and trying to select an image, the application crashes. This plugin adds NSCameraUsageDescription and NSPhotoLibraryUsageDescription in ***English*** (also used as fallback) and ***German*** to our application.

# Usage
Include this plugin in your config.xml:
```
<plugin name="cordova-plugin-ios-permissions" spec="https://github.com/MBuchalik/cordova-plugin-ios-permissions.git#v1.1.1" source="git" />
```

# Note
Maybe, this bug has already been fixed on PGB (or the platform you are using). Only add this plugin if you experience crashes after clicking on the file input like described above.

**Please note that this plugin is experimental.**

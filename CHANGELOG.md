## 1.2.0+2
- Add documentation for UUID uppercasing behavior. https://github.com/voximplant/flutter_callkit/issues/7
- Fix README examples with .sharedInstance access to iOS FlutterCallkitPlugin. https://github.com/voximplant/flutter_callkit/issues/6

## 1.2.0+1
- Code formatted according to dartfmt

## 1.2.0
It is now possible to integrate a Flutter application with the iOS CallDirectory App Extension,
to block and identify incoming calls!
- `FCXCallDirectoryManager` API added
- `FCXPlugin_CallDirectoryExtension` CallDirectory helper API added along 
  with the `FCXCallDirectoryPhoneNumber` and `FCXIdentifiablePhoneNumber`
- `FlutterCallkitPlugin.sharedInstance` API added (iOS native code)
- `FlutterCallkitPlugin.hasCallWithUUID` API changed to be an instance method
- `FlutterCallkitPlugin.reportNewIncomingCallWithUUID` API changed to be an instance method
- Example app improved with Cupertino widgets
- Example app integrated with iOS CallDirectory App Extension
- CallDirectory App Extension integration guide added

## 1.1.2
- Fix for a bug that might cause `CXStartCallAction` report to fail with unknown error
- README.md improvements

## 1.1.1
- README.md improvements (thank you [VictorUvarov](https://github.com/voximplant/flutter_callkit/pull/5))
- `FCXStartCallAction.contactIdentifier` and `FCXStartCallAction.video` parameters no longer ignored in native iOS code

## 1.1.0+3
- LICENSE warning fix
- Code formatted according to dartfmt
- uuid dependency upgrade

## 1.1.0+2
- Xcode 11.4+ support [added](https://flutter.dev/docs/development/ios-project-migration)
- Code formatted according to dartfmt
- Version of Flutter rise to >=1.20.0

## 1.1.0+1
- Nullability annotations added in native plugin API, to correctly work with Swift
- Handling push notifications example on Swift added

## 1.1.0
`FlutterCallkitPlugin.hasCallWithUUID:` API added in iOS code

## 1.0.0
Release
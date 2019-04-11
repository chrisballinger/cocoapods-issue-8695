# CocoaPods 1.7.0 Regression

This is a sample project to demonstrate a modulemap regression when using static linking in CocoaPods 1.7.0 beta.

* https://github.com/CocoaPods/CocoaPods/issues/8695

```
<unknown>:0: error: module map file '/Pods/Headers/Public/Lottie/lottie-ios.modulemap' not found
<unknown>:0: error: underlying Objective-C module 'Lottie' not found
```

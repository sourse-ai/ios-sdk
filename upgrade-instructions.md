---
title: Incoming iOS PVN SDK - Upgrade instructions
layout: default 
---

v1.8- - September 2014
---------------------
- No breaking API change introduced in this version. Just remove the old Incoming-PVN.{bundle,framework} from your project, and add the new ones. If upgrading directly from v1.2, have a look at the 1.3 and 1.4 upgrade instructions below. If upgrading from 1.3 take a look at the 1.4 upgrade instructions below. 



v1.6-39 - 21st August 2015
--------------------------
- No breaking API change introduced in this version. Just remove the old Incoming-PVN.{bundle,framework} from your project, and add the new ones. If upgrading directly from v1.2, have a look at the 1.3 and 1.4 upgrade instructions below. If upgrading from 1.3 take a look at the 1.4 upgrade instructions below. 


v1.4-17 - 8th July 2015
------------------------

- No breaking API change introduced in this version. Just remove the old Incoming-PVN.{bundle,framework} from your project, and add the new ones. If upgrading directly from v1.2, have a look at the 1.3 upgrade instructions below. 
- The today widget is now distributed in binary form. It is packaged as a framework and bundle, making integration far easier. The widget / SDK API however hasn't changed, so you can either keep your existing widget code, or upgrade to the binary distribution and benefit from the new features (in-widget video experience mostly). Please contact your Incoming re-presentative to access widget source code, and/or for customisation options. 



v1.3-148 - 16th June 2015
-------------------------

- No breaking API change introduced in this version

- SDK is now bundled as a .framework and .bundle for convenience. To upgrade, discard the old `libincoming-ios-sdk.a`,  `incoming-ios-sdk-resources.bundle` and `include/ISDKDelegateHelper.h` from your project in XCode (make sure to keep your `incoming-ios-sdk.plist` config file which remains unchanged). Then import the content of the SDK distribution. You should have a .bundle and a .framework files added to your main application target. 

- The widget code has been refactored to more closely follow Apple's guidelines. Drag and drop the widget code onto your widget target, make sure to set the widget main storyboard as described in the [widget integration](./widget-integration.html) section.

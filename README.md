Android iBeacon Demo
======================

A simple code based tutorial enabling you to create your first Android iBeacon app!

# App configuration

Ok cowboy...before we actually start coding, make sure you prepare your project to support Bluetooth Low Energy scans, so open up your Androidmanifest.xml and add the following permissions:

```xml
<uses-permission android:name="android.permission.BLUETOOTH" />
<uses-permission android:name="android.permission.BLUETOOTH_ADMIN" />
```

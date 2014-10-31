SBK for  Android
=======================

SBK, the full name is Sensoro Beacon Kit, which is a part of Sensoro SDK. The SBK for Android is a library that allows interaction with [Yunzi](http://www.sensoro.com/). 

## Installation

### 1. Import *sensorobeaconkit.jar*

Copy  *sensorobeaconkit.jar* to your **libs** directory. If your project does not exist **libs** folder, touch it in root directory. Right click on your project, choose **New**, and click **Folder**, you can create a new directory.

### 2. Declar in *AndroidManifest.xml*

You should add following permissions and services declaration to your *AndroidManifest.xml*:

```
<manifest
    ...
    <uses-permission android:name="android.permission.BLUETOOTH" />
    <uses-permission android:name="android.permission.BLUETOOTH_ADMIN" />
    ...
    <application
        ...
        <service android:name="com.sensoro.beacon.kit.BeaconProcessService"></service>
        <service android:name="com.sensoro.beacon.kit.BeaconService"></service>
        ...
    </application>
    ...
</manifest>

```

## Docs

- [Current JavaDoc Documentation](http://static.sensoro.com/documents/SBK/Android/index.html)
- [Community Portal of Sensoro](https://sensoro.zendesk.com/hc/communities/public/questions?locale=en-us)
- [User Guide](http://www.sensoro.com/docs/)

## Changelog

- 1.0
    - Initial version.
# React Native Camera [![Backers on Open Collective](https://opencollective.com/react-native-infy-camera/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/react-native-infy-camera/sponsors/badge.svg)](#sponsors) [![npm version](https://badge.fury.io/js/react-native-infy-camera.svg)](http://badge.fury.io/js/react-native-infy-camera) [![npm downloads](https://img.shields.io/npm/dm/react-native-infy-camera.svg)](https://www.npmjs.com/package/react-native-infy-camera)

## Docs

React Native infy camera module for React Native.

Supports:

- photographs.
- videos
- face detection (Android & iOS only)
- barcode scanning
- text recognition

### Example import

```jsx
import { RNCamera, FaceDetector } from 'react-native-infy-camera';
```

### To install and start react-native-infy-qrcode-scanner:

1. `npm i react-native-infy-camera`

##### Permissions

To use the camera,

1) On Android you should ask for camera permission:

```java
  <uses-permission android:name="android.permission.CAMERA" />
```

To enable `video recording` feature,  you must have to add the following code in `AndroidManifest.xml`:

```java
  <uses-permission android:name="android.permission.RECORD_AUDIO"/>
  <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
  <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
```

![5j2jduk](https://cloud.githubusercontent.com/assets/2302315/22190752/6bc6ccd0-e0da-11e6-8e2f-6f22a3567a57.gif)

2) On iOS, you should update Info.plist with a usage description for camera

```xml
...
<key>NSCameraUsageDescription</key>
<string>Your own description of the purpose</string>
...
	
```
For more information on installation, please refer to [installation requirements](./docs/installation.md#requirements).

For general introduction, please take a look into this [RNCamera](./docs/RNCamera.md).


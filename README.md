# Installation

### 1. Clone repo, install modules
```
git clone https://github.com/finalem/react-native-intercom-example.git
cd react-native-intercom-example
yarn
```
### 2. Manual install intercom framework 
https://github.com/intercom/intercom-ios#manual-installation

### 3. Insert your api data
ios/RNIntercomExample/AppDelegate.m
```
[Intercom setApiKey:@"ios_sdk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx" forAppId:@"xxxxxxxx"];
```

android/app/src/main/java/com/rnintercomexample/MainApplication.java
```
Intercom.initialize(this, "android_sdk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx", "xxxxxxxx");
```

### 4. Run app
```
react-native run-ios
react-native run-android
```
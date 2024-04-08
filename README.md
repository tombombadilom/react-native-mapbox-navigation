# react-native-mapbox-navigation

A React Native wrapper for MapBox Navigation upgraded to version 0.59.9  

=> updated react-native-geolocation-service by @react-native-community/geolocation

=> updated android.support.annotation by andoidx.annotation

=> installed jetifier

=> working on android but needs ios debug because i don't have a Mac

=> updated App.js to start at gps current position

## Installing the app

### Installing the node dependencies

```sh
$ npm install
```

### Installing the iOS dependencies

#### Installing Pods if not installed

```sh
$ sudo gem install cocoapods
```

#### Installing the dependencies

```sh
$ cd ios && pod install
```

#### Adding your Mapbox Token

Android replace {MAP_BOX_TOKEN} by your token in:
`react-native-mapbox-navigation/android/app/src/main/res/values/strings.xml`

iOS replace {MAP_BOX_TOKEN} by your token in:
`react-native-mapbox-navigation/ios/RNMapboxNavigation/Info.plist`

## Running the app

#### iOS from the Terminal

Run one of the command listed below

```sh
$ react-native run-ios
```

#### Android from the Terminal

Run one of the command listed below

```sh
$ react-native run-android
```

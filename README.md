# Study with Ionic
Study for self development to be an Ionic developer.


### Command List
[Capacitor commands link](https://capacitorjs.com/docs/getting-started/with-ionic)

### Plugins (Recent work)
- [Barcode-scanner](https://github.com/capacitor-community/barcode-scanner)
- [Capacitor resources add](https://github.com/ionic-team/capacitor-assets#adaptive-icons)
- 

### Projects (Recent)
- [Feedchat](https://play.google.com/store/apps/developer?id=Feedchat)
- [BD comapany apps](https://play.google.com/store/apps/developer?id=My+Global+App+Pty+Ltd)

### Best works
- [My School Bag](https://play.google.com/store/apps/details?id=com.myglobalapp.msb)
- [My health record](https://play.google.com/store/apps/details?id=com.health.mhr)
- [MHR Doctor BD](https://play.google.com/store/apps/details?id=com.myglobalapp.mhr.doctor)

### Ionic **Live reload and Deploy in Phone** with Capacitor by [Native Run](https://capacitorjs.com/docs/guides/live-reload)
 - Native plugin install `npm install -g @ionic/cli native-run`
 - Connect with USB/Wify(Same wify with pc and mobile) to PC
 - Mobile `Developer mode` on all required options
 - Get to see available list of AVD, Run `adb devices` or `ionic capacitor run android --list`
 - Copy the `Target ID`
 - Run `ionic cap run android/ios -l --external`
 - Deploy in Android phone `ionic capacitor run android --target e1f86a91`

### Ionic build
All command list `ionic build --help`

### iOS deployment

### Android deployment
- [Google play console(Registration, login)](https://developer.android.com/distribute/console)
- Step by step [link here](https://support.google.com/googleplay/android-developer/answer/9859152)

### Others Work

### Issue & Solution
Issue | Solution | Description
------------ | ------------- | -------------
HTTP not workin in Android | [Android api issue of 'http'](https://stackoverflow.com/questions/45940861/android-8-cleartext-http-traffic-not-permitted) | Android updated SDK not allow HTTP requrest for API cause of security purposes its defalut is `false` so you may config as per your need.
Ionic capacitor (Android) Package name not update | [Changing the Package ID](https://capacitorjs.com/docs/v4/android/configuration) | You need to use a different package name because 'io.ionic.starter' already exists in Google Play.
Ionic capacitor Resources(Icon & Splash Screen) | [Stackoverflow solution](https://stackoverflow.com/questions/66026629/error-occurred-while-copying-resources-android-icon-mdpi-foreground-png) | [Github discussion](https://github.com/ionic-team/capacitor-assets/issues/137)
Ionic capacitor Update versionCode on Android build | [Stackoverflow solution](https://stackoverflow.com/questions/72987043/ionic-6-capacitor-cannot-change-the-app-version-on-android) | - In this NativeProject file `android/app/build.gradle`,<br> - Update `versionCode` number and `versionName` that is string for each build.

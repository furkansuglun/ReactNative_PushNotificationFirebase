# ReactNative - PushNotification with Firebase

react-native-firebase now can do what react-native-fcm can so it is a waste of effort to build the same thing in parallel.

Since I'm getting busier these days and start feeling challenging to maintain this repo every day while react-native-firebase has a larger team/company backing it, existing users may consider migrating to react-native-firebase.

I've created an example project using react-native-firebase as a migration reference

react-native-fcm will still take PRs and bug fixes, but possibly no new feature developement any more.


# Installation

Run npm install react-native-fcm --save
Link libraries Note: the auto link doesn't work with xcworkspace so CocoaPods user needs to do manual linking
You many need this package for huawei phone

# Configure Firebase Console

In firebase console, you can:

for Android: download google-services.json file and place it in android/app directory.
for iOS: download GoogleService-Info.plist file and place it in /ios/your-project-name directory (next to your Info.plist)
Make sure you have certificates setup by following https://firebase.google.com/docs/cloud-messaging/ios/certs
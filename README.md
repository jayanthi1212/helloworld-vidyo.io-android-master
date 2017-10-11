# helloworld-vidyo.io-android
Simple video chat application using Vidyo.io on Android

> For an instructional video detailing how to build this app, take a look at this [Blog Post](https://vidyo.io/how-to/build-mobile-video-chat-app-android-minutes).

## Clone Repository
git clone https://github.com/Vidyo/helloworld-vidyo.io-android.git

## Acquire .jar and .so Files
1. Download the latest Vidyo.io Android SDK package: https://static.vidyo.io/latest/package/VidyoClient-AndroidSDK.zip
2. Copy all files located at VidyoClient-AndroidSDK/lib/android to the VidyoIODemo/app/libs directory.

## Build and Run Application
1. In Android Studio, use Import project to open and import the Android project for the app: VidyoIODemo
2. Open the source file VidyoIODemo/app/src/main/java/com/example/pfuternik/vidyoiodemo/MainActivity.java and update the token value "InsertValidTokenHere" with a valid generated token. See the Token section of the Documentation at https://vidyo.io for more info on generating tokens.
3. Connect an Android device to your computer via USB.
4. In Android Studio, run the app. Android Studio builds, loads, and runs the app on an Android device.


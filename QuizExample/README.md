# QuizExample Toy App!

This is the QuizExample Toy app that students build during the [Developing Android Apps](https://www.udacity.com/course/new-android-fundamentals--ud851) course at Udacity.

A bit more tricky to install with the requirements. This version works on my device (Galaxy Note 8)

1. You must first install an apk for their DroidTermsExample app. Available [here](https://github.com/udacity/DroidTermsExample-APK/raw/master/droidtermsexample-release.apk) You MUST install and run this app on your device (or emulator) BEFORE attempting to run this toy app!

2. Thanks to the ridiculous rate of depreciation and updates in the Android ecosphere, the gradle dependencies will be a nightmare to get correct. I have the correct gradle dependencies in here for SDK 28 with a minimum of 16. If you want to tackle the issue, remember that you must replace "compile" with implementation and "testCompile" with testImplementation. Also, "compile project" becomes implementation project.

## Thanks for visiting!
# UiAutomator Jetifier Bug

This project attempts to reproduce an issue with the Jetifier for AndroidX and UiAutomator, as reported here: https://issuetracker.google.com/issues/123060356

To reproduce, download the project and run `./gradlew assembleAndroidTest`.

The relevant configuration is in [build.gradle](https://github.com/Sloy/uiautomator-jetifier-bug/blob/master/app/build.gradle#L31)
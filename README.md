## OneTrust Kit Integration

[See here for more information](https://github.com/mParticle/mparticle-android-sdk/wiki/Kit-Development) on how to use this example to write a new kit.

This repository contains the [OneTrust](https://www.onetrust.com) integration for the [mParticle Android SDK](https://github.com/mParticle/mparticle-android-sdk).

### Adding the integration

1. Add the kit dependency to your app's build.gradle:

    ```groovy
    dependencies {
        implementation 'com.mparticle:android-onetrust-kit:5+'
    }
    ```
2. Follow the mParticle Android SDK [quick-start](https://github.com/mParticle/mparticle-android-sdk), then rebuild and launch your app, and verify that you see `"<REPLACE ME> detected"` in the output of `adb logcat`.
3. Reference mParticle's integration docs below to enable the integration.

### Documentation

[OneTrust integration](https://docs.mparticle.com/integrations/onetrust/event/)

### License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)

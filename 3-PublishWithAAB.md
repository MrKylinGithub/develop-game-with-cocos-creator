# Publish your game with the Android App Bundle in Cocos Creator

## What is Android App Bundle (AAB)

An Android App Bundle is a publishing format that includes all your app’s compiled code and resources, and defers APK generation and signing to Google Play.

Google Play uses your app bundle to generate and serve optimized APKs for each device configuration, so only the code and resources that are needed for a specific device are downloaded to run your app. You no longer have to build, sign, and manage multiple APKs to optimize support for different devices, and users get smaller, more-optimized downloads.

## How to publish your game with AAB format

In Cocos Creator, just check the **Generate App Bundle(Google Play)** option in the Android Build panel. Your game will then be published with the ABB format.

![](https://files.mdnice.com/user/21366/1d8c4266-9d17-4261-8dbc-98a7db417f6f.png)

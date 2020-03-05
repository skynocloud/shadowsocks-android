---
Title: README
Date: 2020-03-05
Author: skynocloud
---


Change and modify the following and put them into `$HOME/.gradle/gradle.properties`

    MYAPP_RELEASE_STORE_FILE=/path/to/androidkey.js
    MYAPP_RELEASE_KEY_ALIAS=***
    MYAPP_RELEASE_STORE_PASSWORD=***
    MYAPP_RELEASE_KEY_PASSWORD=***

To compile, use

    ./gradlew assembleRelease

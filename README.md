# espresso-gradle-example
Example setup for using TestObject Gradle Plugin with Espresso

    ANDROID_HOME=<path to your android sdk>
    USERNAME=<username>
    PASSWORD=<password>
    APP="basic-espresso-sample"
    TEST_SUITE=11

    To Execute:
    $ ./gradlew testobjectUpload

Prerequisites:

1. Login to the test object dashboard and upload an Android application to create the app profile. This can be a placehoder application initially. 

2. Once the app is uploaded click on "Espresso" under the automated testing tab and upload an espresso test .apk file. This can be a placeholder apk file initially. Select a device and run the tests. This will create the Suite ID. 

3. Configure the build.gradle file within the app folder of this project. 

IMPORTANT:  

"username" is what you use for login into testobject, not your email. If you are a member of a team, the "team" field must be present in order to access the storage API. 

"password" must be associated with the correct username

See https://github.com/testobject/testobject-gradle-plugin for more configuration options.

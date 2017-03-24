# espresso-gradle-example
Example setup for using TestObject Gradle Plugin with Espresso

    ANDROID_HOME=<path to your android sdk>
    TESTOBJECT_USERNAME=<username>
    TESTOBJECT_PASSWORD=<password>
    TESTOBJECT_APP="basic-espresso-sample"
    TESTOBJECT_TEST_SUITE=11
    ./gradlew testobjectUpload`

Prerequisites:

1. Login to the test object dashboard and upload an Android application to create the app profile. This can be a placehoder application initially. 

2. Once the app is uploaded click on "Espresso" under the automated testing tab and upload an espresso test .apk file. This can be a placeholder apk file initially. Select a device and run the tests. This will create the Suite ID. 

3. Configure the build.gradle file within the app folder of this project. 

IMPORTANT:  

"username" is what you use for login into testobject, not your email. If you are a member of a team, the root account username is needed to access the storage API. 

"password" must be associated with the correct username

See https://github.com/testobject/testobject-gradle-plugin for more configuration options.
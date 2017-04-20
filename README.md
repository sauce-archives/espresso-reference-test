# espresso-gradle-example

Example setup for using TestObject Gradle Plugin with Espresso. To build the app and test .apk files, run:

	./gradlew assemble
	./gradlew assembleAndroidTest
	
The .apk files app-debug.apk and app-debug-androidTest-unaligned.apk will be located in `app/build/outputs/apk/`.

Tests can be run on the TestObject platform [using the UI](https://wiki.saucelabs.com/display/DOCS/Automated+Testing+on+Real+Devices) or [using Continous Integration](https://wiki.saucelabs.com/display/DOCS/Continuous+Integration+for+Espresso).

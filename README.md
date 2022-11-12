# BDD_AppiumFramework
This is the demo project to show how to Automate Android and iOS Apps using Appium and Cucumber BDD.

1. Install Android Studio with AVD and Pixel 3 Emulator
2. Run the AVD Device and make sure its working and connected to Internet
3. Install NodeJS latest version
4. Install Appium using "npm install -g appium"
5. Configure "ANDROID_HOME" variable in PATH to SDK location "C:\Users\<User ID>\AppData\Local\Android\Sdk\"
6. Clone the project, Launch in IntelliJ and Let the Maven download all dependencies
7. mvn clean
8. mvn test

NOTE: For running in iOS device you need to change the AppiumDriver code. As of now it is only configured to run in Windows OS.

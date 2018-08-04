# Front-end-testing

## Get Started
###  Preconditions to use Appium:
- JDK:  
http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html  
- Android Studio  
https://developer.android.com/studio/index.html  
- Appium desktop  
https://github.com/appium/appium-desktop/releases  
- XCode from App Store (should be Xcode 8+)   
- XCode Command line developer tools  
`$ xcode-select --install`  
- Carthage   
`$ brew install carthage`  
- For communication with iOS devices natively
`$ brew install libimobiledevice --HEAD`  
`$ npm install -g ios-deploy`  

## Appium
1. Install Appium  
`$ npm install -g appium`
  
2. Install appium doctor  
`$ npm install -g appium-doctor`  
  
3. Run appium doctor to verify that all of the dependencies are set up correctly  
`$ appium-doctor`  
`$ appium-doctor --ios`  
`$ appium-doctor --android`  


This directory contains webRTC sdk library.

Example of building & using the app:

- Build Android AppRTCMobile and AppRTCMobile unit test:

- use the library:
   * with jar archive you should run  to build the jar file and copy the webrtc_sdk.jar to your libs
   directory.
   * with dependence in your android Module build.gradle
   ```gradle
   dependencies {
       // ...
       compile project(':webrtc_sdk')
   }
   ```

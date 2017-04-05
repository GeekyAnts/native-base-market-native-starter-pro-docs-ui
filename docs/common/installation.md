
###System Requirements

* Globally installed [node](https://nodejs.org/en/) >= 4.0
* Globally installed [npm](https://www.npmjs.com/) >= 3.0
* Globally installed [react-native CLI](https://facebook.github.io/react-native/docs/getting-started.html)

### Full Version

Run the following commands on your terminal to setup the App on your system.


### Installation

* **Opt #1. Download ZIP**

Not familiar with Git?
Download the Full Version of the theme.
Extract the contents of ZIP file after downloading.
Downloading ZIP file does not help you to sync with further updates of the App.

* **Opt #2. Clone using GitStrap Web Client**

To setup the Full Version for the App on your system, with **gitstrap** tools to sync your app with constant updates, clone the repo.

* Install packages for Full Version
```
cd App
npm install
react-native link
```

* To simulate for iOS
  * **Method One:**
    * Open the project in XCode from ``` ios/App.xcodeproj```.
    * Hit Build button to simulate.
  * **Method Two:**
    * Type ``` react-native run-ios ``` in your terminal.

* To simulate for Android
  * Make sure you have an ``` Android emulator ``` installed and running.
  * Type ``` react-native run-android ``` in your terminal.

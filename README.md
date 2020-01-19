# React Native [Web] + Monorepo
## 100% code sharing between Web, iOS and Android

### How to run

_Requirements: [React Native](https://facebook.github.io/react-native/docs/getting-started.html#native) (last tested on react-native@0.61)_

  - `$ git clone git@github.com:brunolemos/react-native-web-monorepo.git`
  - `$ cd react-native-web-monorepo`
  - `$ yarn`
  - `$ cd packages/mobile/ios`
  - `$ pod install`
  - `$ cd -`
  - `$ yarn workspace web start`
  - `$ yarn workspace mobile start`
  - Run the project
    - [iOS] Via Xcode
      - `yarn xcode` (open the project on Xcode)
      - Press the Run button
    - [Android] Via Android Studio
      - `yarn studio` (open the project on Android Studio)
      - Press the Run button
    - Via CLI
      - _You may need to launch your device emulator before the next command_
      - `$ yarn android` or  `$ yarn ios`

<p align="center">
  <img alt="DevHub Mobile - Notifications" height="620" src="https://github.com/devhubapp/devhub/raw/master/landing/static/screenshots/iphone-notifications-dark.jpg" />
  <img alt="DevHub Mobile - Notification Filters" height="620" src="https://github.com/devhubapp/devhub/raw/master/landing/static/screenshots/iphone-notifications-filters-dark.jpg" />
  <img alt="DevHub Mobile - Events" height="620" src="https://github.com/devhubapp/devhub/raw/master/landing/static/screenshots/iphone-events-dark.jpg" />
</p>

<br/>

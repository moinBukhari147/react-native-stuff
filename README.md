# react-native-stuff
Contains the reusable command and stuff of reactnative

## Expo react-native:
- To build the ios and android project locally and to reflect the changes in app.json
```bash
  npx expo prebuild
```
  the local change made directly in the android and ios folder will over written after running this command.

- To build and reflect the changes by removing previous cache:
```bash
  npx expo prebuild --clean
```
  
- To run the command specifically for Android:
```bash
  npx expo prebuild --platform android
```

- To run the command specifically for ios:
```bash
  npx expo prebuild --platform ios
```

- To run app on ios device:
```bash
  npx expo run:ios
  npm expo run:ios --device
```

- To run app on android device:
```bash
  npx expo run:android
  npm expo run:android --device
```
  
## Expo EAS:
- To install the eas cli globally:
```bash
  npm install -g eas-cli
```

- To check who is login or whose expo dev account is in use:
```bash
  eas whoami
```

- To login with expo dev account for eas:
```bash
  eas login
```

- Initialize new eas project:
```bash
  eas init
```

- To condigure different flows and setting for ios, android or all:
```bash
  eas configure
```
  eas json is created after running this command.

- To create the development build with eas for ios:
```bash
  eas build --profile development --platform ios
```

- To create the development build with eas for android:
```bash
  eas build --profile development --platform android
```

- To create the development build with eas for ios locally on pc:
```bash
  eas build --profile development --platform ios --local
```

- To create the development build with eas for android locally on pc:
```bash
  eas build --profile development --platform android --local
```


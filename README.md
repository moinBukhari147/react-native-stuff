# react-native-stuff
Contains the reusable command and stuff of reactnative

## Build expo react-native app locally:
- To build the ios and android project locally and to reflect the changes in app.json
```bash
  npm expo prebuild
```
  the local change made directly in the android and ios folder will over written after running this command.

- To build and reflect the changes by removing previous cache:
  ```bash
  npm expo prebuild --clean
  ```
  
- To run the command specifically for Android:
  ```bash
  px expo prebuild --platform android
  ```

- To run the command specifically for ios:
  ```bash
  npx expo prebuild --platform ios
  ```
  

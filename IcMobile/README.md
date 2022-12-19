# Ic Mobile

## 개발환경

- React Native 0.70.6
- React 18
- Node 16

## 개발시작

```shell
npx react-native init IcMobile --template react-native-template-typescript
```

### Running Application

- start metro server

    ```shell
    npx react-native start
    ```

- start ios /adnroid

    ```shell
    npx react-native run-ios
    npx react-native run-android
    ```

- install splash screen

    ```shell
    yarn add react-native-splash-screen
    react-native link react-native-splash-screen
    ```

- splash image make

    ```shell
    react-native set-splash --path ./src/Assets/images/splash.jpg --resize center --background "#FFFFFF"
    ```

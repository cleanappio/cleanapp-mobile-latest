# CleanApp

This README contains a brief app status.

## Current status

The app is running on Android & iOS simulators but fails at the initialization.

### What was done

I created a new CleanApp application with the following command:
```
npx react-native@latest init CleanApp
```
Then copied a current cleanapp-mobile content into a new app with merging package.json and a couple of other configs.

After that I fixed a couple of failures at the app start by fixing dependencies.

### What to do

*  Make both Android apps built and run on both Android and iOS

## Pre-requisites

XCode: ```Version 14.3 (14E222b)```

Node: ```v18.17.1```

iOS Simulator: ```iPhone 12 iOS 16.4```

Android details: come later

Please review the following doc for checking the setup: https://reactnative.dev/docs/environment-setup

## Commands to run

Installing modules
```
yarn
```

Running iOS simulator
```
npm run ios
```

Running Android simulator
```
npm run android
```
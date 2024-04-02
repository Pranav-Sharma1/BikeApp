# Expo-Leaflet + OpenStreetMap using CyclOSM

Cyclosm on Mobile

To Configure Project:

- Download Expo
- npx expo start

Common issues:

Version of expo should be 49/50
Upgrade expo: Use npm install/yarn add expo@49
Upgrade dependecies of expo: npx expo install --fix

Try the above before the below, as one below can give lots of installlation errors at times

Migrating from old expo cli to new expo cli:
npx install-expo-modules@latest

Error: Module AppRegistry is not a registered callable module (calling runApplication):

An error in your code is preventing the JavaScript bundle from being executed on startup.
Try running npx expo start --no-dev --minify

Error: npm ERR! - use yarn add instead of npm.


Reference:

- https://www.npmjs.com/package/expo-leaflet
- https://github.com/Dean177/expo-leaflet
- https://github.com/Dean177/expo-leaflet/tree/master/demo
- https://www.openstreetmap.org

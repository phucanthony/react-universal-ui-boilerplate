# React Wings Boilerplate

[react-native-url]: https://facebook.github.io/react-native/
[react-native-web-url]: https://github.com/necolas/react-native-web
[react-universal-ui-url]: https://npmjs.org/package/react-universal-ui

## Overview
By extending [React Native][react-native-url]'s initial structure using [react-native-web][react-native-web-url] and UI components form [react-universal-ui][react-universal-ui-url].

## Usage
```
git clone https://github.com/cloudle/react-wings-boilerplate.git
cd react-wings-boilerplate
npm install
npm run web-vendor
npm run web
```

**`web-vendor`** builds webpack's shared-dll which massively increase rebuild time for hot-reloading our code.

*Under **200ms** in my machine, which is quite close to React Native's rebuild.*

## Run modes
```
npm run [web | web-vendor | ios | android]
```

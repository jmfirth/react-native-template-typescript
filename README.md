# React Native with TypeScript

## Usage

1. Create a new project:

```sh
react-native init AwesomeTSProject --template typescript --skip-jest
```

2. Change the name of the registered component in `index.ios.js` and `index.android.js` to match your project name.

```ts
AppRegistry.registerComponent('AwesomeTSProject', () => App);
```

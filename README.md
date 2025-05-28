# List of commands for creating the boilerplate expo structure

```bash
npx create-expo-app --template expo-template-blank-typescript
npm i --save react-native@0.78.2
npm install --save react-native-windows
npx react-native init-windows
npm install --save react-dom@19.0.0
npm i --save-dev @react-native/metro-config
npm i --save-dev @expo/metro-runtime@~5.0.4
npm i --save react-native-web@^0.20.0 --force
```

# Command for testing on windows

```bash
npx @react-native-community/cli run-windows
```
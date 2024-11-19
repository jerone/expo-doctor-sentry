# npx expo-doctor giving plugin error

See https://github.com/expo/expo/issues/33054

## Minimal reproducible example

### Predefined example

1. Git clone https://github.com/jerone/expo-doctor-sentry
2. `cd expo-doctor-sentry`
3. `npx expo-doctor` (install latest if asked)
4. See error

### Self reproducible

You'll need an account for Sentry.

1. `npx create-expo-app@latest`
2. `npx @sentry/wizard@latest -i reactNative` and follow all default instructions
3. `npx expo-doctor` (install latest if asked)
4. See error

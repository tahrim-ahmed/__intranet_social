# A intranet social web (intranet_social)

Intranet Social Application with referral

## React Native requires Java SE Development Kit (JDK)
```bash
choco install -y nodejs.install openjdk8
```

### Download and install Android Studio. While on Android Studio installation wizard, make sure the boxes next to all of the following items are checked:
```bash
Android SDK
Android SDK Platform
Android Virtual Device
```

### Android Studio installs the latest Android SDK by default. Building a React Native app with native code, however, requires the Android 10 (Q) SDK in particular. Additional Android SDKs can be installed through the SDK Manager in Android Studio.Select the "SDK Platforms" tab from within the SDK Manager, then check the box next to "Show Package Details" in the bottom right corner. Look for and expand the Android 10 (Q) entry, then make sure the following items are checked:
```bash
Android SDK Platform 29
Intel x86 Atom_64 System Image or Google APIs Intel x86 Atom System Image
```

### Build the app for development
```bash
npx react-native start
```

### Build the app for production
```bash
npx react-native run-android
```

### Customize the configuration
See [Configuring react-native](https://reactnative.dev/docs/environment-setup).

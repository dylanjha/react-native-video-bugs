# React Native Video bugs

This is a demo app to reproduce bugs I ran into with react-native-video

# Prerequisites

You should already have XCode and the iOS simulators installed. You should also already have Android Studio and an Android emulator installed

# Installation

Clone:

```
git clone git@github.com:dylanjha/react-native-video-bugs.git
cd react-native-video-bugs
```

Install dependencies:

```
yarn install
```

Start react-native

```
yarn start
```

----

Open a new terminal window

open in iOS simulator:

```
yarn ios
```

open in android emulator:

```
yarn android
```

# Bugs

## onProgress callback not firing (#1979)

Issue: https://github.com/react-native-community/react-native-video/issues/1979

This happens on Android when video starts off `paused`.

See recording: https://www.loom.com/share/0a903fc33c644ca9a7cb7c9747587997

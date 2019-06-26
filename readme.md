# Stitch Mobile Example - Todo App

## Facebook OAuth Branch
Please keep in mind you will most likely need to test this on a physical device.
The Facebook app is required as part of the OAuth process, in order to grant
permissions.

## Requirements

- Swift >= 5
- Cocoapods >= 1.6.1

Please note, some users have had issues installing the Pods using the
desktop client for Cocoapods. We recommend using
[Homebrew](https://brew.sh/) to install this dependency.

```
brew install cocoapods
pod install --repo-update
```

This sample app is intended to be used by following the
[Todo tutorial](https://docs.mongodb.com/stitch/tutorials/todo-overview/) in the
Stitch docs. It demonstrates the process of building an
iOS app that connects to the Stitch backend and uses Atlas for data storage.

We also have [Android](https://github.com/mongodb-university/stitch-tutorial-todo-android)
and [Web (React)](https://github.com/mongodb-university/stitch-tutorial-todo-web)
versions.

An example of Google OAuth is including in the
[google-oauth](https://github.com/mongodb-university/stitch-tutorial-todo-ios/tree/google-oauth)
branch.

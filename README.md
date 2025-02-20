# React Native Silent State Mutation Bug

This repository demonstrates a common but subtle bug in React Native functional components: incorrectly modifying state variables without using the `useState` hook's setter function.  This leads to unexpected behavior where the UI doesn't update even though the state variable appears to change.

The `bug.js` file shows the erroneous code, while `bugSolution.js` provides the corrected implementation.  The bug manifests as a lack of UI updates despite state variable changes.

## Setup

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npx react-native run-android` (or `npx react-native run-ios`) to run the app.
# React Native useState: Direct Object/Array Mutation Issue

This repository demonstrates a common error in React Native when using the `useState` hook with objects or arrays.  Directly modifying the state object or array within the component does not trigger a re-render because React only detects changes when a new object/array reference is assigned.

The `bug.js` file shows the incorrect implementation, while `bugSolution.js` provides the correct approach.

## How to Reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `npm install` or `yarn install`.
4. Run the app using your preferred React Native method (e.g., `npx react-native run-android` or `npx react-native run-ios`).
5. Observe the incorrect behavior in `bug.js` and the correct behavior in `bugSolution.js`.
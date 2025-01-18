# Unhandled JS Exception: TypeError: Cannot read properties of undefined (reading 'property')

This repository demonstrates a common error in React Native applications and how to resolve it. The error, `TypeError: Cannot read properties of undefined (reading 'property')`, arises when attempting to access a property of an object that is currently null or undefined. This often occurs during asynchronous operations or when neglecting null checks before property access.

## Reproducing the Bug

The `bug.js` file contains code that intentionally triggers this error. Running this code will showcase the issue.

## Solution

The `bugSolution.js` file provides a corrected implementation. It addresses the problem by incorporating proper null checks before accessing properties, effectively preventing the error.

## How to Run

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npx react-native run-android` or `npx react-native run-ios`.
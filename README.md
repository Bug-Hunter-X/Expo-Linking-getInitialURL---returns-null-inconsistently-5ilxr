# Expo Linking.getInitialURL() Inconsistent null Return

This repository demonstrates a bug in Expo's `Linking.getInitialURL()` API where the function inconsistently returns `null`, even when a deep link is successfully opened. This makes deep linking unreliable in the application.

The `bug.js` file shows the problematic code that uses `Linking.getInitialURL()`, illustrating the inconsistent behavior. The `bugSolution.js` file presents a potential workaround which involves checking for `null` and retrying multiple times to retrieve the initial URL.
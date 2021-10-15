Start with `yarn start` in one terminal and `yarn ios` in another. Then press the `Go` button in the app.

When the button is pushed I get the following warning in the console:

```
Require cycle: node_modules/react-native/Libraries/Network/fetch.js -> node_modules/whatwg-fetch/dist/fetch.umd.js -> node_modules/react-native/Libraries/Network/fetch.js

Require cycles are allowed, but can result in uninitialized values. Consider refactoring to remove the need for a cycle.
```
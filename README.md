# React Native Dimensions API Error: Cannot read properties of undefined (reading 'window')

This repository demonstrates a common error encountered when using the `Dimensions` API in React Native to obtain screen dimensions. The error, "Cannot read properties of undefined (reading 'window')", typically occurs when accessing dimensions prematurely, before the component has fully mounted. This usually happens when attempting to access dimensions in the component's constructor or before the `useEffect` hook's first execution.

The `bug.js` file shows the erroneous code, while `bugSolution.js` offers a corrected version.
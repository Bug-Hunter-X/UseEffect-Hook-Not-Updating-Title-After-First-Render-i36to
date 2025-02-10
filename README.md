# React useEffect Hook Bug

This repository demonstrates a common bug in React's `useEffect` hook where the dependency array is not correctly specified, leading to unexpected behavior.

## Bug Description
The component `MyComponent` uses `useEffect` to update the document title with the current count. However, due to an error in the dependency array, the title only updates when the count is initially 0. Subsequent changes to the count do not update the title.

## Solution
The solution involves correcting the dependency array in the `useEffect` hook.  By removing the conditional logic and always updating the title, the issue is resolved.

## How to Reproduce
1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe that the document title only updates once, when the count is 0.

## How to Fix
1. Refer to `bugSolution.js` for the corrected code.
2. Replace `bug.js` with the corrected code.
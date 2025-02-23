# React useState Direct Mutation Bug

This repository demonstrates a common mistake when using the `useState` hook in React: directly mutating the state variable instead of using the setter function.  This leads to unexpected behavior and will not trigger re-renders.

## Bug Description
The `bug.js` file contains a component that attempts to increment the `count` state variable directly.  This approach does not update the UI correctly.

## Solution
The `bugSolution.js` file shows the correct approach; using the `setCount` function to update the state.  This ensures that React correctly re-renders the component and updates the UI.  The solution illustrates the correct way to use the `useState` hook.
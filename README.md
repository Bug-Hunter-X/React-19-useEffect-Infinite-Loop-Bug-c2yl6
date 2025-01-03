# React 19 useEffect Infinite Loop Bug

This repository demonstrates a common error in React 19 involving the `useEffect` hook causing an infinite loop due to missing dependency array. The `useEffect` hook runs after every render, leading to unintended behavior. This example shows the error and how to fix it by adding a dependency array.
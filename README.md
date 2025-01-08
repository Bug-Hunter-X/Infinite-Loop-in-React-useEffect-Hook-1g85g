# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React applications where an infinite loop occurs due to an incorrectly used `useEffect` hook.  The `useEffect` hook is used to perform side effects, but if not used correctly, it can lead to unexpected behavior, such as infinite re-renders and performance issues.

## Bug Description
The provided code contains an infinite loop due to a missing dependency in the `useEffect` hook. This causes the component to re-render infinitely, leading to high CPU usage and a potentially frozen UI.  This example demonstrates how an unintended infinite loop can occur.

## Solution
The solution involves adding the correct dependency to the `useEffect` hook. This ensures that the effect runs only when the specified dependency changes.
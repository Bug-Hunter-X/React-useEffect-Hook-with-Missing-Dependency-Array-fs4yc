# React useEffect Hook with Missing Dependency Array

This repository demonstrates a common error in React applications involving the `useEffect` hook: missing dependency arrays.  The provided code showcases the problem, and a corrected version is included for comparison.

## Problem

The initial code includes a `useEffect` hook without a dependency array.  This causes the effect to run after every render, leading to unnecessary re-renders and potential performance issues.  The console will show excessive logging, indicating the problem.

## Solution

The solution involves adding a dependency array to the `useEffect` hook.  This ensures that the effect only runs when the specified dependencies change.

## How to Run

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install the necessary dependencies.
4. Run `npm start` to start the development server.

Observe the console logs in both the original buggy and the corrected version to see the difference in behavior.
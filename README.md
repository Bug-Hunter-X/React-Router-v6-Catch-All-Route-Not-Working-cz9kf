# React Router v6 Catch-All Route Issue

This repository demonstrates a problem with React Router v6 where the catch-all route (`*`) does not function as expected when navigating to a non-existent path.  Instead of displaying the 404 page, the previous route persists.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm start`.
4. Navigate to a non-existent route (e.g., `/invalid`).

You'll notice that the 'Not Found' component does not render; the previous route remains.

## Solution

The solution involves ensuring the correct usage of `Routes` and `Route` components within `BrowserRouter`.  The provided solution file (`bugSolution.js`) demonstrates the correction.
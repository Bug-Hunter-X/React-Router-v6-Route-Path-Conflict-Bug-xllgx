# React Router v6 Route Path Conflict

This repository demonstrates a common bug in React Router v6 related to route path conflicts and provides a solution.

## Bug Description
The bug occurs when defining routes in a way that creates ambiguity for the router, leading to unexpected rendering or navigation issues.  This often happens when routes overlap or are not specific enough.

## How to Reproduce
Clone this repository and run `npm install`.  Then run `npm start`. Navigate to the different routes. Observe that path conflicts can cause unexpected routing behavior.

## Solution
The solution involves carefully defining routes to avoid conflicts.  This usually involves using more specific path matching or prioritizing routes based on their specificity to resolve ambiguity.

# React Router Dom v6 Catch-all Route '*' Issue

This repository demonstrates a common issue encountered when using the catch-all route ('*') in React Router Dom v6.  The catch-all route is intended to handle any unmatched routes, rendering a 404 Not Found component. However, under certain circumstances, it may not function as expected.

## Issue Description
The provided code demonstrates the problem.  The catch-all route is not being triggered and it returns a blank screen.  The solution illustrates how to correctly implement the catch-all route to handle invalid routes. 

## Solution
The solution involves ensuring the catch-all route is placed as the last route in the `Routes` component. This ensures that React Router will only try to match it after exhausting all other defined routes.   

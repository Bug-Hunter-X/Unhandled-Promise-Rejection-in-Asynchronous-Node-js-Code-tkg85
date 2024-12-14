# Unhandled Promise Rejection in Asynchronous Node.js
This repository demonstrates a common issue in asynchronous Node.js applications: unhandled promise rejections.  The `bug.js` file contains code that simulates an asynchronous operation which may throw an error.  Because the error is not properly handled, it results in an unhandled promise rejection, causing the application to crash.

The `bugSolution.js` file provides a corrected version that uses `try...catch` within the `async` function or proper promise handling to catch the error gracefully.
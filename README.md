# Express.js Route Handler Error

This repository demonstrates a common error in Express.js route handlers:  failure to handle invalid input gracefully.  The `bug.js` file shows a route that's vulnerable to crashes if a non-numeric user ID is provided. The `bugSolution.js` demonstrates how to resolve this issue using robust error handling and input validation.
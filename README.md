# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling when dealing with user input.  Specifically, this example shows a route that fetches a user by ID.  If the ID is not a valid number, the application will crash or behave unexpectedly.

## Bug
The `bug.js` file contains the flawed code. It attempts to parse the user ID as an integer without validating it first. This can cause errors if the ID is not a number.

## Solution
The `bugSolution.js` file provides a corrected version of the code. This improved code includes input validation to ensure that the user ID is a valid number before attempting to access the user data.
# Next.js Runtime Error: Accessing Undefined Variable

This repository demonstrates a common Next.js runtime error caused by accessing an undefined variable within a page component. The error occurs because the `about.js` file attempts to access a variable named `data` which is not defined in its scope. This results in a runtime error and the application crashing.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install the necessary dependencies.
3. Run `npm run dev` to start the development server.
4. Navigate to `/about`.
5. Observe the runtime error in your browser's console.

## Solution

The solution involves either defining the `data` variable or removing the line that attempts to access it. The provided `aboutSolution.js` file offers the corrected code that solves the error.
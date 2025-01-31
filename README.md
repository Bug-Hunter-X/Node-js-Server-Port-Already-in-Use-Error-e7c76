# Node.js Server Port Already in Use

This repository demonstrates a common error in Node.js where a server fails to start because the specified port is already in use.  The `bug.js` file contains the problematic code, while `bugSolution.js` provides a solution.

## Problem

When you run a Node.js HTTP server, it attempts to bind to a specific port. If that port is already in use (e.g., by another instance of the server or a different application), the server will fail to start and an error will be thrown.

## Solution

The solution involves checking if the port is available before attempting to bind to it.  This can be done using various techniques, such as those illustrated in the `bugSolution.js` file.
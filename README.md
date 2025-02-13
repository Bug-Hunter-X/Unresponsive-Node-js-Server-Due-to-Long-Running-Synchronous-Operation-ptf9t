# Unresponsive Node.js Server

This repository demonstrates a common issue in Node.js where a long-running synchronous operation blocks the event loop, making the server unresponsive.  The `bug.js` file contains the problematic code. The `bugSolution.js` provides a solution using asynchronous operations.
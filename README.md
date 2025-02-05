# Unhandled Errors in Node.js HTTP Server

This repository demonstrates a common error in Node.js: improper error handling in an HTTP server. The original `bug.js` lacks error handling, causing the server to crash silently if an error occurs. The solution, `bugSolution.js`, provides robust error handling using the `'error'` event listener.
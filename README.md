# Unhandled Exception in Node.js HTTP Server

This repository demonstrates an example of an unhandled exception in a Node.js HTTP server and how to properly handle it using error handling mechanisms.

## Bug

The `bug.js` file contains a Node.js HTTP server that throws an unhandled exception when the request URL is '/error'. This results in the server crashing without any proper error handling. 

## Solution

The `bugSolution.js` file demonstrates the corrected implementation.  It includes a `try...catch` block within the request handler to gracefully handle the error, preventing the server from crashing.
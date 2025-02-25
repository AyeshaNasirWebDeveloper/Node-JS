# What is Node.js?

Node. js is not a programming language; it is a runtime environment allowing you to execute JavaScript code on the server side, outside a web browser. Built on the V8 JavaScript engine from Chrome, Node. js compiles JavaScript into machine code for efficient execution.

# Installation

To install Node.js, go to the official Node.js website (nodejs.org), download the latest Long Term Support (LTS) version for your operating system, run the installer, and follow the on-screen instructions; you can verify the installation by opening your command prompt and typing "node -v" which should display the installed Node.js version. 

# How does Node.js works?

Node.js provides a set of asynchronous I/O primitives in its standard library that prevent JavaScript code from blocking and generally, libraries in Node.js are written using non-blocking paradigms, making blocking behavior the exception rather than the norm.

# How is Node.js code executed?

Node. js uses JavaScript Event Loop to process each client request. This Event loop is an indefinite loop to receive requests and process them. Event Loop continuously checks for client's requests placed in Event Queue.
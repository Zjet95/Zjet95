# Putting it all together

## Reading

## 1. What is node.js?

* Node.js is an open source server environment
* Node.js can generate dynamic page content
* Node.js runs on various platforms (Windows, Linux, Unix, Mac OS X, etc.)
* Node.js uses JavaScript on the server
* Node.js can create, open, read, write, delete, and close files on the server

## 2. In your own words, what is Chrome’s V8 JavaScript Engine?

* V8 is Google's open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node.js, among others.

## 3. What does it mean that node is a JavaScript runtime?

* The Node. js runtime is the software stack responsible for installing your web service's code and its dependencies and running your service.

## 4. What is npm?

* The name npm (Node Package Manager) stems from when npm first was created as a package manager for Node.js.

* All npm packages are defined in files called package.json.

* The content of package.json must be written in JSON.

* At least two fields must be present in the definition file: name and version.

## 5. What version of node are you running on your machine?

* ~ node -v

> v19.6.1

## 6.What version of npm are you running on your machine?

npm -v
> 9.4.0
>
## 5.What command would you type to install a library/package called ‘jshint’?

* To install the JSHint tool, run the command npm install jshint in CLI. If you want to check if JSHint has been successfully installed, run the command jshint -version to see its version.

## 6.What is node used for?

* Node.js is a single-threaded, open-source, cross-platform runtime environment for building fast and scalable server-side and networking applications. It runs on the V8 JavaScript runtime engine, and it uses event-driven, non-blocking I/O architecture, which makes it efficient and suitable for real-time applications.

**How can you identify where state needs to live?**

* Firstly, identify every component that render something based on state. That means the component receives all, or part of the state as props. 

* Then, find a component higher up the tree than all the components that use the state, and put state in this component. This could be an immediate owner component or a component even higher up the tree. 

* Lastly, if it doesn't make sense for state to live in a common owner component or one doesn't exist, create a new component to hold state, and add it to the hierarchy and appropriate place. It may be the two or more separate trees converge at this new component. And it may only serve to provide a sensible place for state to live.

## Things I want to know more about

Were Diving into NodeJs tomorrow morning, So excited to see the possibilites with it.

[Back to Home]

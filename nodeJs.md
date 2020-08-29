# NodeJs

NodeJs is a JavaScript runtime built on Chrome’s V8 JavaScript engine. which mean your javascribt will work outside the browser. and to do that nodeJs use v8 JavaScript engine. but nodeJs use enhanced v8 engine to make it work outside of the browser.

**_to compile a js file simply write node filename.js in the console then boom it works_**

# npm

npm used to download packages into your project.

```
npm init -y
```

This will create and auto-populate a package.json file in the same folder.

Node.js is single-threaded. It’s also event-driven, which means that everything that happens in Node is in reaction to an event. For example, when a new request comes in (one kind of event) the server will start processing it. If it then encounters a blocking I/O operation, instead of waiting for this to complete, it will register a callback before continuing to process the next event. When the I/O operation has finished (another kind of event), the server will execute the callback and continue working on the original request. Under the hood, Node uses the libuv library to implement this asynchronous (that is, non-blocking) behavior.

Node’s execution model causes the server very little overhead, and consequently it’s capable of handling a large number of simultaneous connections. The traditional approach to scaling a Node app is to clone it and have the cloned instances share the workload. Node.js even has a built-in module to help you implement a cloning strategy on a single server.

JavaScript is everywhere, and Node is a vast and expansive subject. Nonetheless, I hope that in this article I’ve offered you the beginner-friendly, high-level look at Node.js and its main paradigms that I promised at the beginning. I also hope that when you re-read the definitions we looked at previously, things will make a lot more sense.

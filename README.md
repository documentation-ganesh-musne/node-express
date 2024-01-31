## NodeJS

### <span style="color:#0d6efd">What is node JS?</span>

---

**Node.js is an open-source, cross-platform JavaScript runtime environment
that executes JavaScript code outside of a browser.
Node.js is built on Chrome's V8 JavaScript engine.
Node.js is commonly used for developing server-side applications,
but it can also be used for developing desktop and mobile applications.**

---

### <span style="color:#0d6efd">What is NPM?</span>

---

**NPM stands for Node Package Manager, responsible for managing all the packages and modules for Node.js.
Node Package Manager provides two main functionalities
Provides online repositories for node.js packages/modules, which are searchable on search.nodejs.org
Provides command-line utility to install Node.js packages and also manages Node.js versions and dependencies**

---

### <span style="color:#0d6efd">What is the command used to import external libraries?</span>

---
**The “require” command is used for importing external libraries. For example - “var http=require (“HTTP”).”  This will load the HTTP library and the single exported object through the HTTP variable.
Now that we have covered some of the important beginner-level Node.js interview questions let us look at some of the intermediate-level Node.js interview questions.**

---

### <span style="color:#0d6efd">What is the package.json file?</span>

---
**The package.json file is the heart of a Node.js system. This file holds the metadata for a particular project. The package.json file is found in the root directory of any Node application or module
This is what a package.json file looks like immediately after creating a Node.js project using the command: npm init
You can edit the parameters when you create a Node.js project.**

[<img src="./images/node-npm.jpeg" width="400"/>](./images/node-npm.jpeg)

---

### <span style="color:#0d6efd">How do you install, update, and delete a dependency?</span>

---
[<img src="./images/npm-install.jpeg" width="400"/>](./images/npm-install.jpeg)

---

### <span style="color:#0d6efd"> How do you create a simple server in Node.js that returns Hello World?</span>

---
```
var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/html'});
  res.end('Hello World!');
}).listen(8080);

```
---

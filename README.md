<h1>My e-commerce project using nodejs</h1>

<h2>What is Node.js</h2>

Node.js is a JavaScript runtime

JavaScript is a programming language that manipulates webpages on the browser.

Javascript is not limited to just runninning on webpages and Node.js is build on javascript.

Node.js runs JS code on a server.

Node.js uses V8 which is an engine that runs javascript on the browser.

V8 takes the JS code and compiles it to machince code. V8 adds features such as adding file systems.

<h2>Using NodeJS</h2>

You will run node js on the terminal

```bash
node -v
```
This command checks the version of node you have

```bash
node
```

This commands opens a REPL for nodejs which can run commands.

Install the meterial icon theme for nice icons.

Make a new file called first-app.js

write
```JavaScript
console.log('Hello from nodejs')
```

to run app use

```bash
node first-app.js
```

inside first-app.js use the command:

```JavaScript
const fs = require('fs');
```

fs stands for file systems which allows for file systems functionalities

```JavaScript
fs.writeFileSync();
```

`writeFileSync()` function takes some arguments:
- The first argument takes the path of the file to be created
- The second argument is the data put inside the file
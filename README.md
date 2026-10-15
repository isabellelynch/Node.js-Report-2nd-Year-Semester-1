# Node.js – A JavaScript Runtime Environment

**Author:** Isabelle Lynch
**Date:** 10th November 2025

A research report and presentation on Node.js, the open-source runtime that lets JavaScript run outside the browser. They cover where Node.js came from, how it works, its strengths and weaknesses, what it is used for, and how companies such as LinkedIn and PayPal use it. A short sample program is included.

**[Read the report on GitHub →](NodeJS/NodeJS_Report.md)**

---

## Contents

| File | Description |
|------|-------------|
| [`NodeJS_Report.md`](NodeJS/NodeJS_Report.md) | The report in Markdown, readable directly on GitHub |
| `NodeJS_Report.docx` | The original report (Word) |
| `NodeJS_PowerPoint.pptx` | The presentation (16 slides) |
| [`server.js`](NodeJS/server.js) | The sample "Hello World" server from the report |
| `images/` | Images used by the Markdown report |

---

## What the report covers

1. **Introduction**: JavaScript's move from the browser to the server.
2. **What is a JavaScript framework**: libraries and frameworks explained.
3. **Node.js – the beginning**: created by Ryan Dahl in 2009.
4. **The role of Node.js**: running JavaScript on the server for full-stack development in one language.
5. **Features**:
   - Asynchronous, event-driven architecture
   - Single-threaded event loop
   - npm and modular structure
   - Cross-platform compatibility
   - Community support
6. **Advantages**: performance, adaptability, scalability, community and cost.
7. **Disadvantages**: the single-threaded limitation, "callback hell", and library compatibility issues.
8. **What Node.js can do**:
   - Build tools
   - Web servers
   - File system operations
   - Databases
   - REST and GraphQL APIs
9. **Companies that use Node.js**: LinkedIn and PayPal.
10. **Sample code**: a line-by-line walkthrough of a minimal HTTP server.
11. **Conclusion**, **References** and **Bibliography**.

---

## Running the sample code

The report's example creates a web server that replies "Hello World!".

```js
let http = require('http');

http.createServer(function (req, res) {
    res.writeHead(200, {'Content-Type': 'text/plain'});
    res.end('Hello World!');
}).listen(8080);
```

1. Install [Node.js](https://nodejs.org/) (any current version).
2. In this folder, run:
   ```
   node server.js
   ```
3. Open <http://localhost:8080> in a browser. You should see **Hello World!**
4. Press `Ctrl + C` in the terminal to stop the server.

The example is based on the [W3Schools Node.js tutorial](https://www.w3schools.com/nodejs/).

---

## References

- Dryka, M. (2025, June 5). *9 Famous Node.js Apps*. Brainhub. <https://brainhub.eu/library/famous-apps-built-with-nodejs>
- Herron, D. (2020). *Node.js Web Development*. Birmingham: Packt Publishing Ltd.
- McPeak, J. (2011). *JavaScript 24-hour trainer*. Indianapolis: Wiley.
- Nodejs.org. (2025). *Node.js*. <https://nodejs.org/en/about>
- Panchal, Y. (2024). *Building Scalable Web Applications with Node.js and Express.js*. Delhi: Orange Education Pvt Ltd.
- W3Schools. (2025). *Node.js Tutorial*. <https://www.w3schools.com/nodejs/>

The full bibliography is at the end of the [report](NodeJS/NodeJS_Report.md#bibliography).

---

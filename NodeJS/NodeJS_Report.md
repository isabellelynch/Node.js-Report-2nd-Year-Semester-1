# Node.js

**A JavaScript runtime environment**  
By Isabelle Lynch · 10th November 2025

## Table of Contents

- [Introduction](#introduction)
- [What Is a JavaScript Framework?](#what-is-a-javascript-framework)
- [Node.js – The Beginning](#nodejs--the-beginning)
- [The Role of Node.js](#the-role-of-nodejs)
- [Features of Node.js](#features-of-nodejs)
  - [Asynchronous and Event-Driven Architecture](#asynchronous-and-event-driven-architecture)
  - [Single-Threaded Event Loop](#single-threaded-event-loop)
  - [Node Package Manager (npm) and Modular Structure](#node-package-manager-npm-and-modular-structure)
  - [Cross-Platform Compatibility](#cross-platform-compatibility)
  - [Community Support and Open-Source Accessibility](#community-support-and-open-source-accessibility)
- [Advantages of Node.js](#advantages-of-nodejs)
  - [Performance and Speed](#performance-and-speed)
  - [Adaptability and Cross-Platform Functionality](#adaptability-and-cross-platform-functionality)
  - [Scalability](#scalability)
  - [Community and Open-Source Development](#community-and-open-source-development)
  - [Cost-Effectiveness](#cost-effectiveness)
- [Disadvantages of Node.js](#disadvantages-of-nodejs)
  - [Single-Threaded Limitation](#single-threaded-limitation)
  - [Callback Hell](#callback-hell)
  - [Library Compatibility Issues](#library-compatibility-issues)
- [What Can Node.js Do?](#what-can-nodejs-do)
  - [Build Tools](#build-tools)
  - [Create Web Servers and Network Applications](#create-web-servers-and-network-applications)
  - [Perform File System Operations](#perform-file-system-operations)
  - [Interact with Databases](#interact-with-databases)
  - [Build APIs](#build-apis)
- [Companies That Use Node.js](#companies-that-use-nodejs)
  - [LinkedIn](#linkedin)
  - [PayPal](#paypal)
- [Sample Code / Implementation (W3Schools, 2025)](#sample-code--implementation-w3schools-2025)
- [Conclusion](#conclusion)
- [References](#references)
- [Bibliography](#bibliography)

## Introduction

JavaScript is one of the most widely used programming languages in the world, it was originally designed to enhance interactivity and functionality on the client side of web applications. However, the evolution of web technologies has expanded JavaScript’s role far beyond the browser. One of the most significant developments in this progression is Node.js, a powerful, open-source JavaScript runtime environment that enables developers to execute JavaScript code on the server side.

This report explores Node.js in depth, examining its origins, key features, advantages and disadvantages. It discusses how Node.js differs from traditional server-side technologies and highlights its role in creating scalable, high-performance, cross-platform applications. Furthermore, the report presents real-world examples of organizations that have successfully implemented Node.js, such as LinkedIn and PayPal, to demonstrate its practical benefits in industry. Finally, the report concludes by summarizing the overall impact of Node.js on software development and evaluating its continuing significance in modern web architecture.

## What Is a JavaScript Framework?

A JavaScript framework is a structured collection of prewritten JavaScript code, typically organized into libraries. These libraries provide reusable functions and components that streamline development and reduce repetitive coding tasks. A framework provides a structure for developers to write code, which in turn simplifies the completion of both common and complicated tasks. Frameworks are an all-encompassing set of tools that you can manipulate and use for designing a website more conveniently. Most frameworks are open source, meaning they are constantly updated by the community of developers that use them. (McPeak, 2011)

## Node.js – The Beginning

Founded by Ryan Dahl in 2009, Node.js was developed to achieve greater concurrency at a lower cost than what other programming languages had achieved at the time. When Ryan demonstrated his work at the JSConf EU conference in 2009, *“he stated that the concurrency was achieved by threads in most of the top languages and that using threads has certain problems as context switching between threads is costly.”* (Panchal, 2024)

## The Role of Node.js

The primary role of Node.js is to provide a JavaScript runtime environment that enables developers to execute JavaScript code outside of a web browser, primarily on the server side, for building fast, efficient, and *scalable network applications* (Nodejs.org, 2025). Traditionally, JavaScript was limited to client-side scripting, however, Node.js extends its capabilities to server-side development, allowing for full-stack programming within a single language. According to *Herron (2020),* Node.js is a versatile platform designed for *“developing web applications, application servers, any sort of network server or client, and general-purpose programming”.* Herron (2020) further describes Node.js as an *ingenious* innovation created to deliver *“extreme scalability in networked applications”* through the integration of JavaScript, asynchronous I/O and asynchronous programming principles.

## Features of Node.js

### Asynchronous and Event-Driven Architecture

One of the key features of Node.js is its asynchronous and event-driven architecture, which allows the server to process multiple client requests simultaneously without waiting for any single process to complete. This nonblocking I/O model ensures high performance and scalability, making Node.js particularly suitable for applications that handle large volumes of concurrent data, such as chat systems, streaming services, and online gaming platforms. (Herron, 2020)

### Single-Threaded Event Loop

Although Node.js operates on a single thread, it efficiently manages numerous operations through the event loop mechanism, delegating heavy or blocking tasks to background workers. This approach enables it to manage many simultaneous connections with minimal resource consumption, providing better performance compared to traditional multi-threaded models. (Herron, 2020)

### Node Package Manager (npm) and Modular Structure

Node.js includes Node Package Manager (npm), which provides access to one of the largest ecosystems of open-source libraries in the world. Developers can utilize millions of prebuilt modules and tools to simplify and accelerate application development. This modular design encourages code reusability, reduces development time, and allows developers to easily integrate or replace components without disrupting the overall system. (Panchal, 2024)

### Cross-Platform Compatibility

Node.js is cross-platform compatible, meaning that code can be developed and executed on Windows, macOS, and Linux without modification. This flexibility simplifies deployment, ensures consistency across different operating systems, and allows applications to run reliably in diverse environments. (Herron, 2020)

### Community Support and Open-Source Accessibility

Node.js benefits from an active global developer community that continuously contributes updates, modules, and security patches. Being open source ensures that Node.js remains up to date, secure, and adaptable to new technologies, while providing extensive resources such as tutorials, forums, and documentation for developers at all levels. (McPeak, 2011)

## Advantages of Node.js

### Performance and Speed

Node.js has many positive attributes, its speed, performance, and scalability being the most notable.

It operates faster than most of its competitors due to its powerful runtime environment, built on the Google Chrome V8 engine. Its caching capabilities allow data to be stored temporarily in memory, reducing database queries and improving load times. Node.js achieves high performance through asynchronous, non-blocking I/O operations, which handle multiple requests concurrently without waiting for other responses. (Herron, 2020)

### Adaptability and Cross-Platform Functionality

Node.js’s cross-platform compatibility enables development and deployment across various operating systems, making it highly portable, adaptable, and consistent across devices. It supports a wide variety of applications, including web servers, Application Programming Interfaces (APIs), microservices, realtime applications and Internet of Things (IoT) solutions. Its modular design, supported by Node Package Manager (npm), allows developers to integrate or replace components without disrupting the overall system, making it easy to adapt to new requirements. (Herron, 2020)

### Scalability

Although Node.js is single threaded, it scales effectively under heavy traffic. It can manage many concurrent requests through the ‘cluster’ module, which creates child processes to balance workloads and reduce application strain (Panchal, 2024). This efficient handling of concurrency allows developers to scale their applications seamlessly as user demand increases. (Herron, 2020)

### Community and Open-Source Development

As an open-source technology, Node.js benefits from a vast and active global community of developers who continuously improve the platform by fixing bugs, adding new features, and maintaining documentation. This strong community support also makes Node.js accessible and easy to learn, with extensive resources such as forums, tutorials and troubleshooting pages available online. The large npm ecosystem offers millions of prebuilt modules and libraries, which further reduces development time. (Herron, 2020)

### Cost-Effectiveness

Node.js is also highly cost-effective. It allows developers to use JavaScript on both the frontend and backend, eliminating the need for separate specialist teams and thereby reducing labour costs. Additionally, the availability of free npm packages accelerates development and lowers expenses. Node.js can efficiently manage increasing user loads without requiring significant hardware or maintenance upgrades, enabling both startups and large enterprises to scale economically. (Panchal, 2024)

## Disadvantages of Node.js

### Single-Threaded Limitation

While Node.js’s single threaded architecture offers simplicity and efficient handling of concurrent I/O operations, it can also be a drawback in certain scenarios. Because Node.js runs on a single thread, it struggles with CPU intensive or heavy computational tasks, which can block the event loop and negatively impact performance. This limitation makes Node.js less suitable for applications that require extensive data processing or complex mathematical operations. (Panchal, 2024)

### Callback Hell

The asynchronous nature of Node.js, while powerful, can lead to challenges in managing multiple nested callbacks, a situation commonly referred to as ‘callback hell.’ This occurs when callback functions are nested within other callbacks, making the code difficult to read, debug and maintain. To address this issue, developers often use Promises, async/await syntax, or external libraries such as Async.js, which simplify asynchronous flow and improve code readability. (Panchal, 2024)

### Library Compatibility Issues

Although Node.js benefits from a vast ecosystem of third-party libraries available through the Node Package Manager (npm), not all libraries are consistently maintained or compatible with the latest versions of Node.js. This can lead to compatibility issues, deprecated features, or bugs, which may require developers to seek alternative packages or implement additional debugging and testing. (Panchal, 2024)

## What Can Node.js Do?

### Build Tools

Node.js allows developers to create powerful command-line and build tools that assist in software development and automate repetitive tasks. These tools can also communicate with other services or development infrastructure, streamlining workflows and improving efficiency. (Herron, 2020)

### Create Web Servers and Network Applications

Node.js is widely used to create fast, scalable network applications and web servers. Its non-blocking, event driven architecture allows it to manage multiple connections simultaneously, making it ideal for real-time applications such as chat servers, streaming platforms and online gaming platforms. (Herron, 2020)

### Perform File System Operations

Node.js provides built in modules that allow developers to perform file-related operations such as reading, writing, updating, and deleting files directly on the server. This is useful for tasks like logging, configuration management, and content generation. (Herron, 2020)

### Interact with Databases

Node.js supports seamless integration with various databases, both relational and non-relational, including MySQL, PostgreSQL, and MongoDB. It allows developers to efficiently query, update, and manage data within applications. (Herron, 2020)

### Build APIs

Node.js is commonly used to build RESTful and GraphQL APIs, enabling communication between client and server. Its lightweight architecture and modular ecosystem make it suitable for building scalable backend services that power modern web and mobile applications. (Herron, 2020)

## Companies That Use Node.js

### LinkedIn

LinkedIn is a professional networking platform designed to connect individuals, businesses, and organisations worldwide. Launched in 2003, it enables users to create personal profiles highlighting their professional experience, education, and skills. Users can connect with colleagues, peers and potential employers, facilitating networking and career development. LinkedIn is available in more than twenty-five languages and has over one billion members across more than two hundred countries and territories.

LinkedIn uses Node.js to power the server side of its mobile application, significantly increasing performance while reducing operational costs. According to LinkedIn’s Mobile Development Lead, Kiran Prasad, “One reason was scale. The second is, if you look at Node, the thing it is best at doing is talking to other services.” As a result, the new LinkedIn mobile application became up to twenty times faster than the previous version, while their server requirements drastically reduced from thirty to three. (Dryka, 2025)

### PayPal

PayPal is a digital payment platform that enables individuals and businesses to send and receive money securely over the internet. Founded in 1998, PayPal revolutionised online transactions by offering a fast, convenient, and secure alternative to traditional payment methods. It allows users to link their bank accounts, credit cards, or debit cards to a PayPal account and make payments without directly sharing financial information with merchants. PayPal has approximately 438 million active accounts worldwide.

PayPal adopted Node.js to build the consumer-facing side of its web applications. According to Jeff Harrell, Senior Director of Payments Products and Engineering at PayPal, “Node.js helps us solve this (boundary between the browser and server) by enabling both the browser and server applications to be written in JavaScript. It unifies our engineering specialties into one team which allows us to understand and react to our users’ needs at any level in the technology stack”. The Node.js application required 33% fewer lines of code and 40% fewer files and it was built almost twice as fast with fewer people, when compared to their previous versions. (Dryka, 2025)

## Sample Code / Implementation (W3Schools, 2025)

An example of a simple program, written on Node.js is shown in Figure 1. This program creates a server and prints out ‘Hello World!’, which is demonstrated in Figure 2.

```js
let http = require('http');

http.createServer(function (req, res) {
    res.writeHead(200, {'Content-Type': 'text/plain'});
    res.end('Hello World!');
}).listen(8080);
```

*Figure 1*

![Browser window showing the Hello World! response](images/figure-2-hello-world.png)

*Figure 2*

```js
let http = require('http');
```

This line imports the built in Node.js http module. This module allows developers to create HTTP servers and handle requests/responses. The ‘require()’ function loads the module and returns it as an object. The http object now gives the developer access to functions within the http module.

```js
http.createServer(function (req, res) {
```

This line creates the HTTP server. The ‘createServer()’ function takes a callback function as an argument. The callback function provided will run every time a call is made to the server. Within the function the ‘req’ refers to the request object which contains details about the client’s request such as the URL, method, headers etc, the ‘res’ refers to the response object which is used to send data back to the client.

```js
res.writeHead(200, {'Content-Type': 'text/plain'});
```

This line sets the HTTP response header. ‘200’ refers to the status code, which in this case, means ‘OK’. ‘Content-Type’: ‘text/plain’ tells the browser that the response body is made up of plain text.

```js
res.end('Hello World!');
```

This line sends the response body, in this case the message ‘Hello World!’ to the client. ‘res.end’ closes the response, indicating that no more data will be sent.

```js
}).listen(8080);
```

This line tells the server to listen for connections on port number 8080. Port 8080 is commonly used for testing web servers locally.

## Conclusion

This report examined Node.js as a JavaScript runtime environment and evaluated its key advantages and disadvantages. I believe the findings demonstrate that Node.js represents a significant advancement in modern software development, primarily due to its asynchronous, non-blocking I/O model, which enables the efficient handling of multiple concurrent requests and enhances overall performance. The research has also shown that Node.js is a scalable, adaptable, and cost-effective solution for building networked applications across diverse platforms.

However, certain limitations were also highlighted, such as the constraints of its single-threaded architecture and potential performance issues when handling CPU-intensive operations. Challenges such as ‘callback hell’ and occasional library compatibility issues were also noted as potential drawbacks that may complicate development and maintenance.

In conclusion, despite these minor limitations, I believe Node.js has made a mostly positive impact on the software development industry. Its efficiency, scalability, and strong community support have established it as one of the most valuable tools for developing fast, modern, and reliable web applications. I believe the innovation introduced by Ryan Dahl will continue to shape the future of full-stack JavaScript development and inspire ongoing improvements in server-side technologies.

## References

Dryka, M. (2025, June 5). *9 Famous Node.js Apps*. Retrieved from Brainhub: <https://brainhub.eu/library/famous-apps-built-with-nodejs>

Herron, D. (2020). *Node.js Web Development.* Birmingham: Packt Publishing Ltd.

McPeak, J. (2011). *JavaScript 24-hour trainer.* Indianapolis: Wiley.

Nodejs.org. (2025). *Node.js*. Retrieved from Node.js.org: <https://nodejs.org/en/about>

Panchal, Y. (2024). *Building Scalable Web Applications with Node.js and Express.js.* Delhi: Orange Education Pvt Ltd.

W3Schools. (2025). *Node.js Tutorial*. Retrieved from W3Schools.com: <https://www.w3schools.com/nodejs/>

## Bibliography

Dryka, M. (2025, June 5). *9 Famous Node.js Apps*. Retrieved from Brainhub: <https://brainhub.eu/library/famous-apps-built-with-nodejs>

Herron, D. (2020). *Node.js Web Development.* Birmingham: Packt Publishing Ltd.

McPeak, J. (2011). *JavaScript 24-hour trainer.* Indianapolis: Wiley.

Nodejs.org. (2025). *Node.js*. Retrieved from Node.js.org: <https://nodejs.org/en/about>

Panchal, Y. (2024). *Building Scalable Web Applications with Node.js and Express.js.* Delhi: Orange Education Pvt Ltd.

Resende, D. (2018). *Hands-On Microservices with Node.js.* Mumbai: Packt Publishing.

Robbins, J. N. (2025). *Learning Web Design.* Sebastopol: O'Reilly.

W3Schools. (2025). *Node.js Tutorial*. Retrieved from W3Schools.com: <https://www.w3schools.com/nodejs/>

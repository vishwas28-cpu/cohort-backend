# Day 2 - Backend Learning 🚀

## What I Learned Today

Today, I learned how to send a response from an Express server and deploy my server on Render.

## 1. Sending a Response from the Server

I learned how to create a route using `app.get()` and send a response to the browser.

```js
app.get("/", (req, res) => {
  res.send("Hello World");
});
```

### Explanation

* `app.get()` is used to handle a GET request.
* `"/"` represents the home route.
* `req` contains information about the incoming request.
* `res` is used to send a response back to the client.
* `res.send("Hello World")` sends the message to the browser.

When I open the server URL, the server responds with:

```text
Hello World
```

## 2. Deploying the Server on Render

I also learned how to deploy my Node.js and Express server on Render.

This helped me understand how to make a backend server available online.

## Technologies Used

* Node.js
* Express.js
* NPM
* Render

## Commands and Concepts Learned

```bash
npm init -y
npm i express
```

### Express Server

```js
const express = require("express");

const app = express();

app.listen(3000);
```

## Learning Progress

This repository is part of my Backend Development learning journey. Today, I practiced creating an Express server, sending responses from the server, and deploying the server on Render.

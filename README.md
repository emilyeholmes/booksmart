# Hello, welcome to BookSmart!

BookSmart is your one stop shop to getting personalized book recommendations (tailored to just you!), finding out what books are trending and what people are reading, and discussing in depth about the books you’ve read. To that end, our application features a recommendations page (where you can train the AI model based on your likes and dislikes by clicking on the hearts), a personalized profile (Username: amateur, Password: aces) where you can specify your preferences and add/save books to shelves, a discussions page to talk about books, and book search where you can find your favorite books and add them to shelves. 

This repository was built off other projects created so far in this class so the instructions for building and running are very similar. 

## Building and Running BookSmart
Please start by cloning this repository.

Then, make sure you have recent versions of `node` and `npm` installed (definitely at least version 12 of Node).
Installation instructions for most operating systems are available [on the Node.js website](https://nodejs.org/en/download).
You can check your `node` and `npm` versions using the following commands:

```bash
node --version
npm --version
```

Node.js is a tool that enables you to run JavaScript code outside of the web browser; it's a full-featured language runtime just like the `python3` or `java` command, and you can build desktop software using Node.js.
In this case, we'll use it to run a simple Web server that serves files from the project directory.
Although the code in `server.js` is written in JavaScript just like the JavaScript code within the `public/` directory, the code runs very differently.
In the &ldquo;real world&rdquo;, as a Web developer, you would run `server.js` on some computer you control in the cloud (say, an Amazon AWS server).
When people visit your website, they download HTML, CSS, and JavaScript code from your server, and that frontend code runs on their own computer.

Since you're developing this project locally, all of the code will live and run on your own computer.
Code in `server.js`, however, runs within the Node.js runtime, and the downloaded code in the `public/` directory will run within your web browser, which communicates with the web browser much as it would communicate with a real remote server when you typically browse the Internet.

This repository contains a `package.json` file, which is the standard way to tell Node.js some information about the program, including what libraries are needed to run the server code.
The server software requires an external library called [Express](https://expressjs.com/), which makes it easy to develop Web servers.

Run the `install` command in `npm`, Node's default package manager:

```bash
npm install
```

This will read `package.json`, then look to the [NPM package repository](https://www.npmjs.com/) to grab the appropriate dependencies.

Run the server script on your development computer:

```bash
node server.js
```

Navigate to [http://localhost:8000](http://localhost:8000) in your Web browser and voila! You should have BookSmart running.

## ACCOUNT DETAILS
Our application features a login page where you must sign in to use some of our features. The information is also at the top of the README but in case it was missed:
Username: amateur
Password: aces

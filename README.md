<div align="center">
    <a href="" target="_blank">
      <!-- <img src="" alt="Project Banner"> -->
    </a>
  <h3 align="center">Amazon Scraper API</h3>
</div>

## <br /> 📋 <a name="table">Table of Contents</a>

- ✨ [Introduction](#introduction)
- ⚙️ [Tech Stack](#tech-stack)
- 📝 [Features](#features)
- 🚀 [Quick Start](#quick-start)

## <br /> <a name="introduction">✨ Introduction</a>

**[EN]** This repository features a small REST API project that scrapes data from Amazon, utilizing Node.js and Express. The project showcases the development and deployment of a custom JavaScript API, complete with integration on RapidAPI for monetization. Key functionalities include data extraction and API endpoint creation. 

**[FR]** Ce dépôt présente un petit projet d'API REST qui extrait des données d'Amazon, en utilisant Node.js et Express. Le projet démontre le développement et le déploiement d'une API JavaScript personnalisée, avec intégration sur RapidAPI pour la monétisation. Les fonctionnalités clés incluent l'extraction de données et la création API endpoints. 

## <br /> <a name="tech-stack">⚙️ Tech Stack</a>

- **REST API** (Representational State Transfer Application Programming Interface) is a specific type of API that adheres to the principles of REST, an architectural style for designing networked applications. REST APIs use standard HTTP methods (GET, POST, PUT, DELETE) to interact with resources, which are typically represented in JSON or XML format. REST APIs are stateless, meaning each request from a client to the server must contain all the information needed to understand and process the request. This approach simplifies the interactions between client and server and ensures scalability and performance.

- **Node.js** is a JavaScript runtime built on Chrome's V8 JavaScript engine. It allows developers to execute JavaScript on the server side, enabling the creation of scalable and high-performance applications. Node.js's non-blocking, event-driven architecture makes it particularly suitable for building real-time, data-intensive applications. [📄](https://nodejs.org/en) 

- **NPM** (Node Package Manager) is the default package manager for Node.js. It allows developers to install, share, and manage dependencies in their projects. NPM provides access to a vast repository of open-source packages, facilitating the rapid development and integration of new features. [📄](https://nodejs.org/en/learn/getting-started/an-introduction-to-the-npm-package-manager) 

- **Nodemon** is a utility that automatically restarts a Node.js application when file changes in the directory are detected. It enhances the development workflow by eliminating the need to manually stop and restart the server after each change. Nodemon is highly configurable and supports a wide range of options to tailor its behavior to the specific needs of a project. [📄](https://github.com/remy/nodemon#nodemon) 

- **Express** is a minimal and flexible Node.js web application framework that provides a robust set of features for building web and mobile applications. It simplifies the process of creating RESTful APIs by providing a thin layer of fundamental web application features, including routing, middleware support, and HTTP utilities. [📄](https://expressjs.com/en/starter/installing.html) 

- **request-promise** is an extension of the request library that adds promise support to HTTP requests in Node.js. It provides a straightforward way to handle asynchronous operations, allowing developers to write cleaner and more maintainable code when making HTTP requests. With request-promise, handling responses and errors becomes more manageable through the use of JavaScript promises. [📄](https://www.npmjs.com/package/request-promise) 

- **Requestr** is a Node.js library designed for making HTTP requests. It simplifies the process of sending HTTP requests and handling responses, offering a user-friendly API for interacting with web servers. This library supports various request methods like GET, POST, PUT, and DELETE, making it versatile for different use cases. 


## <br /> <a name="quick-start">🚀 Quick Start</a>

Follow these steps to set up the project locally on your machine.

<br/>**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

<br/>**Cloning the Repository**

```bash
git clone {git remote URL}
```

<br/>**Installation**

Let's install the project dependencies for both the client and server, from your terminal, run:

```bash
npm install
# or
yarn install
```

<br/>**Set Up Environment Variables**

Create a new file named `.env` inside the server folder and add the following content:

```env
PORT=8000
API_KEY=
```

Replace the placeholder values with your actual respective account credentials:

- [Rapid API](https://rapidapi.com/hub)

<br/>**Running the Project**

Installation will take a minute or two, but once that's done, you should be able to run the following command:

```bash
npm run dev
# or
yarn dev
```

Server is now running on [`http://localhost:8000`](http://localhost:8000)
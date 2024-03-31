# Book Saver
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)](https://reactrouter.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Apollo GraphQL](https://img.shields.io/badge/Apollo%20GraphQL-311C87?style=for-the-badge&logo=Apollo%20GraphQL&logoColor=white)](https://www.apollographql.com/)
[![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![JWT](https://img.shields.io/badge/json%20web%20tokens-323330?style=for-the-badge&logo=json-web-tokens&logoColor=pink)](https://jwt.io/)

This is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application that allows users to search for books via the Google Books API and save their favorite books for later viewing. The application uses Apollo Server for GraphQL APIs and Apollo Client for state management in the React application.

Deployed application: [Book Saver](https://book-saver-mern.onrender.com)

## Features

- Search for books using the Google Books API.
- View detailed information about the books.
- Save favorite books for later viewing.
- View a list of all saved books.
- Remove books from the saved list.


## Getting Started

### Prerequisites

- Node.js
- npm
- MongoDB

### Installation

1. Clone the repository:

```sh
git clone git@github.com:hyrumsdolan/Book-Saver-MERN-.git
```

2. Install NPM packages in both the root, client, and server directories:

```sh
npm run install
```

### Usage

To start the application in development mode, run:

```sh
npm run develop
```

To build the application for production, run:

```sh
npm run build
```

To start the application in production mode, run:

```sh
npm start
```

## Application Structure

The application is divided into two main parts:

- [`client`](command:_github.copilot.openRelativePath?%5B%22client%22%5D "client"): This is the front-end part of the application, built with React.js. It uses Apollo Client for state management and to interact with the GraphQL API. The main application entry point is [`client/src/main.jsx`](command:_github.copilot.openRelativePath?%5B%22client%2Fsrc%2Fmain.jsx%22%5D "client/src/main.jsx").

- [`server`](command:_github.copilot.openRelativePath?%5B%22server%22%5D "server"): This is the back-end part of the application, built with Express.js and Apollo Server. It uses MongoDB as the database, with Mongoose as the ODM. The main server entry point is [`server/server.js`](command:_github.copilot.openRelativePath?%5B%22server%2Fserver.js%22%5D "server/server.js").


## License

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)


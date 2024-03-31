# Google Books Search App

This is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application that allows users to search for books via the Google Books API and save their favorite books for later viewing. The application uses Apollo Server for GraphQL APIs and Apollo Client for state management in the React application.

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

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
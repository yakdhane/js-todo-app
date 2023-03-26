Sure, here's a sample README.md file:

# Todo App

A simple todo app built with React.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Docker](#docker)
- [Files](#files)

## Installation

To install the dependencies, run:

```bash
npm install
```

## Usage

To start the app, run:

```bash
npm start
```

This will start the app on `http://localhost:3000`.

## Docker

To run the app using Docker, first build the Docker image:

```bash
docker build -t todo-app .
```

Then run the Docker container:

```bash
docker run -p 3000:3000 todo-app
```

This will start the app on `http://localhost:3000`.

## Files

- `App.js`: The main component that renders the todo app.
- `Form.js`: The component that renders the form for adding new todos.
- `Todo.js`: The component that renders a single todo item.
- `TodoList.js`: The component that renders the list of todos.
- `index.js`: The entry point of the app.
- `styles.css`: The stylesheet for the app.
- `package.json`: The npm package file.
- `README.md`: This file.
- `Dockerfile`: The Dockerfile for building the Docker image.
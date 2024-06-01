# About Todo-List App

## General Info

The Todo-List application is designed with a robust virtual lab setup using Docker and Docker Compose. It includes both SQLite and MySQL implementations for database persistence, and it utilizes various tools and libraries for development and testing, including Node.js, Express, React, Jest, and others. 

## Depenecies:

### Server-Side

Node.js:

Express: Web framework for Node.js to build the API.
mysql2: MySQL client for Node.js.
sqlite3: SQLite client for Node.js.
uuid: Library to generate unique IDs.
wait-port: Utility to wait for a TCP port to be available.

Development Tools:

jest: JavaScript testing framework.
nodemon: Utility that automatically restarts the Node.js server when file changes are detected.
prettier: Code formatter.

### Client-Side

React: JavaScript library for building user interfaces.
React-Bootstrap: Bootstrap components for React.
Bootstrap: CSS framework for responsive design.


## List the services

```
docker compose ps
NAME                    IMAGE            COMMAND                  SERVICE   CREATED          STATUS          PORTS
todo-list-app-app-1     node:18-alpine   "docker-entrypoint.s…"   app       27 seconds ago   Up 10 seconds    127.0.0.1:3000->3000/tcp
todo-list-app-mysql-1   mysql:8.0        "docker-entrypoint.s…"   mysql     27 seconds ago   Up 23 seconds   3306/tcp, 33060/tcp
```




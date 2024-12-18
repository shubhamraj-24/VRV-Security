# Role-Based Access Control (RBAC) System

## Overview
This project is an Authentication and Authorization System that uses Role-Based Access Control (RBAC) to manage user access based on roles and permissions. It provides a structured way to control who can perform specific actions or access certain resources.

## Features

### Frontend :-
- **User Management**: View, add, edit, delete, and manage user roles and statuses.
- **Role Management**: Create and modify roles, and assign permissions to them.
- **Dynamic Permissions**: Assign or remove specific permissions (Read, Write, Delete etc.) to roles, enabling role-based actions for users.

### Backend :-
- **User Registration**: Users can create accounts securely.
- **User Login/Logout**: Secure authentication with session management.
- **Role Management**: Different roles with specific permissions.
- **JWT Authentication**: Secure token-based authentication.
- **RBAC Implementation**: Access control based on user roles.



## Technologies Used

### Frontend :-
- **Library & Language**: React, TypeScript
- **UI Framework**: Material UI
- **Routing**: React Router DOM

### Backend :-
- **Frameworks & Library**: Node.js, Express
- **Database**: MongoDB (or your chosen database)
- **Authentication**: JSON Web Tokens (JWT)
- **Libraries**: bcrypt for password hashing, mongoose for MongoDB interaction

---


## Project Set Up Instructions
---
### Clone the repository
1. Fork this repository.
2. Clone the repository:
```
https://github.com/shubhamraj-24/RBAC-VRV-Security.git`
```

### Configure the client

1. Navigate to client folder:
```
cd client
```
2. Install required packages:
```
npm install
```

### Configure the server

1. Navigate to server folder:
```
cd client
```
3. Install required packages:
```
npm install
```
5. Set up the database and configure the environment variables by following the instructions in the next steps.

### Set up the database

1. Create a MongoDb Atlas Account or MongoDb Compass and create a new database.
2. Create a `.env` file in the server folder and add the following environment variables:

```
PORT= <port_to_run_node_server>
MONGODB_URL= <mongodb_connection_string>
MONGO_DB_URL_MANAGEMENT= <mongodb_connection_string>
TOKEN_SECRET= <JWT_secret_key>

```

### Run the application

#### Run the server first

1. Navigate to server folder: `cd server`
2. Start Client : `npm start`
3. Server will be running at `http://localhost:5001`

#### Now Run the client

1. Navigate to server folder: `cd client`
2. Start Client : `npm start`
3. Open the application in your browser at `http://localhost:3000`

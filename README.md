# mern-stack-auth-starter

A MERN Stack Authentication Starter
* Passport and JWT for security and authentication.

## Technologies

### Frontend
* React and React Router

### Backend
* Express and Node

### Database
* MongoDB (NoSQL)

### State Management between React components
* Redux

## Configuration

Database setup - `config/keys.js`.

```javascript
module.exports = {
  mongoURI: 'mongodb://localhost:27017/mern-stack-auth-starter', // Change this URI to your database location
  secretOrKey: 'secret'
};
```

## Prerequisite

```javascript
// Install dependencies for server & client

npm install && npm run client-install
```

## Start the application

```javascript
// Run client & server with concurrently

npm run dev

// Server runs on http://localhost:5000 and client on http://localhost:3000
```

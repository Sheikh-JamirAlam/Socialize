# Socialize

Here are the steps to run Socialize app on your local system :-

## Prerequisites

- ReactJS
- NodeJS
- Git
- NodeJS

## Installation

Follow these steps to install the app on your local machine.

```sh
git clone https://github.com/Sheikh-JamirAlam/Secrets.git
```

Code to setup server:

```sh
cd server
npm install
```

Create a .env file and fill in with information:

```
MONGO_URL= <URL to MongoDB>
JWT_SECRET= <Any String>
PORT= <Port number>
```

Go back to the main ("Socialize") folder then setup the client:

```sh
cd client
npm install
```

## Deployment

Open two terminal and follow these steps.
Run this command in one of the terminal:

```sh
cd server
npm run start
```

On the other terminal, run these:

```sh
cd client
npm start
```

If app doesn't run automatically, then open http://localhost:3000/ in your browser.

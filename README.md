# Building Serverless RESTful Web APIs with Cloud Functions, Firestore, Express and TypeScript

This is a simple API that saves contact information of people. 

## Requirements

[NodeJS](https://nodejs.org/en/)

You will need a Firebase project and firebase tools cli

```
npm install -g firebase-tools
```

## Getting Started

You can follow the guide on [Medium](https://medium.com/@dalenguyen/building-a-serverless-restful-api-with-cloud-functions-firestore-and-express-f917a305d4e6) or clone this repository.

## Clone this repository

```
git clone git@github.com:dalenguyen/serverless-rest-api.git .
```

You need to change the firebase project name in *.firebaserc* file.

After that, you can log in to firebase in the terminal 

```
firebase login
```

## Deploy to firebase

For the first time, you have deploy the hosting and functions together

```
firebase deploy
```

After that, you just need to deploy functions only

```
firebase deploy --only functions
```

# React Chat App 📳📲

## Tech stacks

 * AWS API Gateway Websockets
 * Dynamodb and custom Cognito authorizer.
 * React 16.8+
 * Serverless 1.38+
 * Node.js 8.10

## Directory structure

```bash
	/backend/            # api Gateway Websockets and Lambda functions
	/frontend/           # frontend React web app
```

## Deploy Backend

```
cd backend && sls deploy
```

## Run React Native App

```
cd frontend
npm install
npm start
```

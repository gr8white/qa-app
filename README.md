This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Starting this App

In the 'backend' directory, run:

### `node src`

In the 'frontend' directory, run:

### `npm start`

To pre-populate the app with questions or enter questions with the backend, run:

`curl -X POST -H 'Content-Type: application/json' -d '{
  "title": "<Enter your main question here>",
  "description": "<Enter a basic description of your question here>"
}' localhost:8081`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.


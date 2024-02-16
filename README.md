# Building a Simple React Weather App


Below are some steps to build it:

Get OpenWeather account and API Keys
Install Node and NPM (or check the version on your device)
Create React project
Install additional packages.
Create your weather app components (Fetch weather data using  API key)
Display weather Data
Style your app 
Run your app

## Step 1: Get an API key
Visit the OpenWeatherMap website (https://openweathermap.org/) and click on “Sign Up” or “Log In” to create an account or log into your existing account.
Once logged in, navigate to your account dashboard.
From the dashboard, locate my API Keys section and click on “Create Key” or “API Keys” to generate a new API key.
These were tested in Mac, however this might be similar in windows.

## Step 2: Check or Install Node.js
Open your terminal
Check if Node.js is already installed by running:

node -v

If Node.js is installed, you'll see a version number. If not, you need to install it. You can download the installer from the official Node.js website.

## Step 3: Create a new React app
Once Node.js is installed, you can create a new React app using Create React App. In your terminal, run:

npx create-react-app weather-app
This will create a new directory called weather-app with all the necessary files and dependencies. Navigate into the newly created directory.

As mentioned here: https://create-react-app.dev/ 

## Step 4: Install additional dependencies
While in the weather-app directory, install Axios for making HTTP requests and Bootstrap for styling (you can use any other CSS framework or custom styling if you prefer):

npm install axios

## Step 5: Create your weather app components and fetch API data using API key 
Inside the “src” directory, create a new file called “Weather.js” and open it in your code editor.
Use Axios (or another HTTP library) to fetch weather data from the API using the API key you obtained earlier. You can make the API call in a useEffect hook to fetch data when the component mounts.
Replace {YOUR_API_KEY} in the API URL with the API key you generated from OpenWeatherMap. 
Add the following code to define a functional component named Weather (for example):
import React, { useEffect, useState } from 'react';
import axios from 'axios';



## 5b. Change App.js

	To run your Weather.js and connect it with App.js


## Step 6: Display weather information
Once you've fetched the weather data, display it in your Weather component. You can show information like temperature, humidity, wind speed, etc.

## Step 7: Style your app
Use CSS or a CSS framework like Bootstrap to style your app and make it visually appealing. You can also use your design from Figma. 

## Step 8: Run your app
Start your React app by running:

npm start / npm run start
This will start a development server and open your weather app in a web browser.



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

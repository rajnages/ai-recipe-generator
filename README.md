Introduction
Follow step-by-step instructions to create a simple serverless web application using AWS Amplify and Amazon Bedrock

Overview
In this tutorial, you will learn how to use AWS Amplify to build a serverless web application powered by Generative AI using Amazon Bedrock and the Claude 3 Sonnet foundation model. Users can enter a list of ingredients, and the application will generate delicious recipes based on the input ingredients. The application includes an HTML-based user interface for ingredient submission and a backend web app to request AI-generated recipes.

What you will accomplish
In this tutorial, you will:

Configure AWS Amplify to host your frontend application with continuous deployment built in
Configure Amplify Auth and enable Amazon Bedrock foundation model Access
Build an app backend for handling requests for your web application
Use Amplify Data to call the serverless backend
Connect the app to the backend
Prerequisites
Before starting this tutorial, you will need:

An AWS account: if you don't already have one follow the Setup Your Environment tutorial.
Your AWS profile configured for local development.
Installed on your environment: Nodejs and npm.
Familiarity with git and a Github account.
﻿# Serverless-Web-Application
## Application architecture
![image](https://github.com/Muzamilraheman/Serverless-Web-Application/assets/98537723/99bb216e-ed8d-4822-8750-250a7cce6f47)
The application architecture uses AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console. Amplify Console provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.

## Step 1: Static Web Hosting
AWS Amplify hosts static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser.

## step 2: User Management
Amazon Cognito provides user management and authentication functions to secure the backend API.

## step 3: Serverless Backend
Amazon DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.

## step 4: RESTful API
JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway.

## Conclusion
In this project, I have created a serverless web application that enables users to request unicorn rides from the Wild Rydes fleet. The application will present users with an HTML-based user interface for indicating a pick-up location and a RESTful web service on the backend to submit the request for dispatching a unicorn. The application will also provide facilities for users to register with the service and log in before requesting rides.

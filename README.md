# Welcome to My Yelp
***
The app is hosted and available at this link: https://d2q2uyyu7dcf49.cloudfront.net

## Task
The goal of this project is to create a clone of the popular Yelp app using React, AWS Amplify, and GraphQL. This project aims to implement a business review platform where users can browse and interact with restaurants by adding, viewing, and reviewing entries, just like on Yelp. The challenge lies in integrating GraphQL for managing restaurant data, enabling real-time updates via subscriptions, and ensuring seamless deployment to the cloud.

## Description
This project addresses the problem of building a highly interactive web application that mimics Yelp’s core functionalities. The project leverages ReactJS for the frontend, AWS Amplify for backend services (such as Authentication, API via GraphQL, and Storage), and GraphQL for querying and mutating data. The user can:

Add new restaurants to the list.
View a list of restaurants.
See real-time updates when a new restaurant is added, thanks to GraphQL subscriptions.
The UI is designed using React Bootstrap to make it responsive and visually appealing, mimicking Yelp’s user interface style.

## Installation
To install the project and set it up locally, follow these steps:

Clone the repository
Navigate to the project directory:
cd my_yelp
Install all dependencies using npm:
npm install
Set up your AWS Amplify backend by configuring your AWS resources:
amplify init
amplify push
Start the project:
npm start

## Usage
Once installed and running, the project works as follows:

A user can view all restaurants listed on the platform.
Users can add new restaurants by filling out the form with the restaurant’s name, city, and description.
New entries are updated in real-time thanks to the AWS AppSync subscription feature.
Users can view the newly added restaurants and interact with them on the platform.
```
./my_project argument1 argument2
```

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>

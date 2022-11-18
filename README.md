<p align="center">
    <br/>
    <a href="https://github.com/bslockhart/brians-social-network-api">	
        <img src="https://i.imgur.com/oT7d23g.png" alt="Brian's Social Network API">
    </a>
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

MongoDB is a popular choice for many social networks due to its speed with large amounts of data and flexibility with unstructured data. Because the foundation of these applications is data, it’s important to understand how to build and structure the API first.

The following is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.

Because this application is not being deployed, a walkthrough video that demonstrates its functionality and all of the following acceptance criteria being met will be submited along with the README file.

## Table of Contents

- [Tools](#tools)
- [Mock Up](#Mock-Up)
- [Instructions](#Instructions)
- [User Story](#User-Story)
- [Acceptance Criteria](#Acceptance-Criteria)
- [Walkthrough Video](#walkthrough-video)
- [Technical Accaptance Criteria](#technical-acceptance-criteria)
- [Repository Quality](#Repository-Quality)
- [Bonus](#bonus)
- [Submission](#Submission)

## Tools

- Express.js
- Mongoose
- MongoDB
- Mongoose ODM

## Mock Up

![Text Editor](./assets/images/18-nosql-homework-demo-01.gif)
![Text Editor](./assets/images/18-nosql-homework-demo-02.gif)
![Text Editor](./assets/images/18-nosql-homework-demo-03.gif)
![Text Editor](./assets/images/18-nosql-homework-demo-04.gif)

## Instructions

1. Clone the main project, then open the cloned file.
2. Make sure you are in the main project folder using the 'cd' command.
3. Open command prompt and run: npm install
4. Run: `npm i express` to install Express.js.
5. Run: `npm i mongoose` to install Mongoose.
6. Run: `npm i nodemon` to install Nodemon.

## User Story

```text
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```text
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## Walkthrough Video

- A walkthrough video that demonstrates the functionality of the social media API must be submitted, and a link to the video should be included in your README file.
- The walkthrough video must show all of the technical acceptance criteria being met.
- The walkthrough video must demonstrate how to start the application’s server.
- The walkthrough video must demonstrate GET routes for all users and all thoughts being tested in Insomnia.
- The walkthrough video must demonstrate GET routes for a single user and a single thought being tested in Insomnia.
- The walkthrough video must demonstrate POST, PUT, and DELETE routes for users and thoughts being tested in Insomnia.
- Walkthrough video must demonstrate POST and DELETE routes for a user’s friend list being tested in Insomnia.
- Walkthrough video must demonstrate POST and DELETE routes for reactions to thoughts being tested in Insomnia.

## Technical Acceptance Criteria

- Uses the Mongoose package Links to an external site.to connect to a MongoDB database.
- Includes User and Thought models outlined in the Challenge instructions.
- Includes schema settings for User and Thought models as outlined in the Challenge instructions.
- Includes Reactions as the reaction field's subdocument schema in the Thought model.
- Uses functionality to format queried timestamps properly.

## Repository Quality

- Repository has a unique name.
- Repository follows best practices for file structure and naming conventions.
- Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
- Repository contains multiple descriptive commit messages.
- Repository contains a high-quality README with description and a link to a walkthrough video.

## Bonus

- Application deletes a user's associated thoughts when the user is deleted.

### Submission

- Date Submitted: November 30, 2022
- You are required to submit BOTH of the following for review:

1. A walkthrough video demonstrating the functionality of the application and all of the acceptance criteria being met.
2. The URL of the GitHub repository. Give the repository a unique name and include a README describing the project: https://github.com/bslockhart/Brians-Social-Network-API

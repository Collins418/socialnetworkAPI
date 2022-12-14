# Social-network

## Description
Due to its speed and adaptability to unstructured data, MongoDB is a popular choice for many social networks.

I developed an API for a social network web application that allows users to share their thoughts, respond to those of their friends, and create a friend list in this project.

For routing, Express.js and the Mongoose packages are used.


## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Installation](#installation)
- [Usage](#usage)
- [Acceptance Criteria](#acceptance-criteria)
- [Contributors](#contributors)
- [Tests](#tests)
- [Technology Used](#technology-used)
- [Questions](#questions)

## User Story
```
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria
```
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia Core for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia Core
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## Installation

To install this application, clone the code into your terminal for the respective repository. Then, install npm by entering the command ```npm install```  into the terminal. Install express and mongoose by entering ```npm i express``` and ```npm i mongoose``` into the command line, respectively.

Note- I had to use npx nodemon server for mine to work

<img width="791" alt="api screenshot" src="https://user-images.githubusercontent.com/106499144/200136051-e76777ee-31ec-48bc-853a-4a181f1d14e3.png">

## Usage
1. Install npm and dependencies: npm install
2. Open Insomnia and test API GET, POST, PUT, and DELETE routes for thoughts, users, friends, and reactions

## Contributors
To contribute to social-network, clone this repo locally and commit your code on a separate branch.
  
## Tests

Demo-https://watch.screencastify.com/v/76crn92NcFmosRIJCynr

Terminal results-https://watch.screencastify.com/v/qIGC8ooum9EXEMKKvRDa


## Technology Used
•	Node
•	Express.js
•	Javascript
•	Mongoose
•	MongoDB
•	Insomnia

## Questions
My Github username is collins418, which can be accessed here :https://github.com/Collins418/socialnetworkAPI

You can reach me at msdavistoday@gmail.com with additional questions.

Below is the link to my demo video on my Github:

Demo-https://watch.screencastify.com/v/76crn92NcFmosRIJCynr

Terminal results-https://watch.screencastify.com/v/qIGC8ooum9EXEMKKvRDa

# social-network-challenge

## Description

For this challenge we are building an API for a social network web application where users are able to share their thoughts, reactions, and friend lists!

AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data

## Acceptance criteria

GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Installation
- Clone repository
- Install MongoDB
- npm install mongoose
- npm install express

when everything needed is installed:
- npm start

## Walkthrough

[User Routes](https://drive.google.com/file/d/1dA_Zz2-3Vyvt7T1sZSwBX0gcwj9AZ1x0/view)
[Thought Routes](https://drive.google.com/file/d/1UmxkfJvIIgIJLsdMcCn635FwzDo1-05q/view)
[Reaction Routes](https://drive.google.com/file/d/12weDQP-lYtfuB_JBTFanARVzmZOEc4yx/view)
[Friend Routes](https://drive.google.com/file/d/1NiWDVfkcehxgsQ21X0yuf-uyxfpmXyYa/view)
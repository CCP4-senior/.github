# Runtomo
Hi and welcome to Runtomo! An app for finding and meeting new buddies to run with.

# Why our App?
Runtomo is a running application that understands where you’re going, but more importantly who you’re going with. Running can be a lonely activity; and let's face it, it can be a chore that we do just to stay in shape.  However, what if you had one or two people who could hold you accountable? Who held your same goals? And maybe, just maybe, have more fun while running?
**About **
Most of the developers who made this app currently live in Japan and have the goal of joining people together to stay active and make connections in one of the most populated cities in the world.  

The application is built with React Native, Django rest framework, PostgresQL, JWT authentication, JavaScript, Heroku and Expo.

React native was preferred due to the nature of our application (Running = AFK), so a mobile application was the ideal choice.  
Django rest framework was implemented due to the ease of building a complete backend, spending more time creating something than building everything from scratch.
PostgresQL was selected for its popularity and reliability with many languages as a database; especially as our server of choice requires Heroku to be used.
JWT was used for authentication of the requests made to our backend, ensuring validated users could alter the database.
Heroku is our server for deploying the database and backend logic, so that requests can interact with it.
Expo, a mobile application for displaying our content to users.


# How it works

**Pre-recorded demonstration**
https://www.youtube.com/watch?v=ijyDfnP7na8

Runtomo is a mobile application centered around the Tokyo area, allowing users to create accounts, make their own running sessions, find other users and join up!  Newcomers and locals can encourage fitness, friendship, and language exchange.  

**Sign up feature**
New users can create accounts and login to use the app.  Without an account, users won’t be able to see, interact with or create sessions.
Users are also required to enter how many times a week they run, and an estimate of their 5k and 10k times so that they can match with users more easily.  They also include a date of birth, an image and email.

**Event searching**
Scroll through the list of events and find a session that sounds good to you. Without joining a session, a user won’t be able to see the exact location but it will show the Tokyo ward.  Events can be filtered by ward and sessions happening soon.

**Join events**
When selecting an event, you can explore the details of where/when it is happening and make a join request.
Users can then communicate within that event with other participants to stay up to date with each other.

**Create events**
Users can create their own events; inputting a title, location, ward, date and time, running duration, description and image file.

**User profiles**
Users can develop their profile by adding running tags (E.g. Social, Marathon etc)and level (E.g. Beginner, Intermediate, Advanced, Pro etc)

**Google Maps**
The map feature will present users with a pin for the meeting location, as well as several running stations in Tokyo that can provide services such as: coin lockers, showers, water fountains, changing rooms and car parking.

# Installation:
**Backend:**
https://github.com/CCP4-senior/runtomo-backend/blob/main/README.md

**Frontend**
https://github.com/CCP4-senior/runtomo-frontend/blob/main/README.md

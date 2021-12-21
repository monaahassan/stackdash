# stackdash


Overview
Stack Dash is a flashcards web app designed to study for the Lambda School web core interview. It shows the student a random question using Fisher-Yates, encourages the student to use active recall to answer the question, and uses card flipping functionality to display the answer in the back of the card.

Check it out at stackdash.com

Check out the lightning talk from Lambda School's Roundtable in May 2021 where I demo the app, describe the design process, and dive into some features.

Getting Started
The base technologies are JavaScript, HTML and CSS. The frontend leverages React, the backend uses Express and SQLite and the app lives on Heroku.

Developer Instructions
Create a forked copy of this project
Clone a version to your local repository
From the root directory in your terminal:
Create a an environment file (.env) and declare NODE_ENV=development and PORT=5000[1]
Add the .env to your .gitignore
Download the server dependencies by running npm install
Start up the server by running npm run server
From the frontend directory in your terminal:
Download the frontend dependencies by running npm install
Start up the app by running npm start
Happy hacking... and when you're ready, share it or pull request me!
Feedback
If you've made it this far, I bet you have some feedback (ideas, insights, improvements, criticisms, maybe even a good ol' fashioned rant). I would welcome any and all of it. I like being the filter of my noise so even if you think it may not be useful, send it along. I'll be grateful.

Thanks for checking out the project.

Notes
[1] You may run the backend server in a different port. If you do, make sure to update your local API call in the frontend action creator.

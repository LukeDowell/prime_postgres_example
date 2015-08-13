# Learnings

1. Database
  -We learned that database.js is just setting up the database for our application
  -We saw that a pg module was added to our dependancies
  -The database.js file simply prepares our application
  -The pg driver creates a bunch of catalog information
  -Our schema is now set in our database.js file, NOT by mongoose using models

2. Node
  -We learned that node will just run whatever you tell it to, it can be a blank console log or a full app.js
  -We learned that nodemon is the best thing ever
  -Express routers have a command for each type of rest request. router.put goes to a type: 'PUT', .get goes to type: 'GET' and so on.

3. Client
  -When you click on a task, it sends a













# Prime Peer - Databases PG (SQL)

Hello everyone! Welcome to this 'challenge'.
In this one, you will not be writing any code (unless you want to), you will actually be learning from a build 
that already exists. You will be going through the code and the goal of this challenge, is to learn from the build.
Specifically, what I would like, is for you all to write down 'learnings' in bullet point format, of what you find
in this build that taught you something you did not no before. The objective is to tinker, understand, turn things
on and off, and whatever else you need to do to understand what the build is doing. Once again, the product of this
challenge should be a list of learned things.

Go ahead and copy this repo to your computer. Open it up in Webstorm.

Next, run 'npm install'.
Then, with postgres already running, run 'node server/database/database.js' in the command line. Take a close look
at what that file is doing, and see if you can make the connection of how this line is working.

Update:
Next, start up your server, open another terminal window.
Run this in that command line:
curl --data "text=test&complete=false" http://127.0.0.1:3000/api/example_database

Fire up the app. Note that the app is not running on port 5000, find what port it is running on. Then play with the
application to get a sense of how its all working.

Write down what you and your pair learn from the activity.

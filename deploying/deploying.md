# Deploy

### Projected Time
30-45 minutes

### Prerequisites
[Create a free Heroku account](https://signup.heroku.com/dc)
Download and install the Heroku CLI with > `brew install heroku/brew/heroku`

Node.js and npm must be installed
An existing Node.js app
JS I - VI
Node
Express
MongoDB
Test Edit 

### Motivation
Deployment is a fancy term for getting your website or on the web. After building out your app, you might want to share it with others.
One typical work flow to deploying your app could include creating your website, finding a domain name, finding a hosting service, uploading files with SFTP, and lastly deploying your server-side app.


### Objective
**Students will be able to** deploy their web site to a third-party hosting service such as Heroku.

### Specific Things To Teach
- Heroku - a cloud based server

### Materials
- [What is Heroku - YouTube Video](https://youtu.be/r5ZUQvl9BtE)
- [MDN Express & Node Deployment ](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/deployment)
- [Heroku Dev Center Deployment](https://devcenter.heroku.com/articles/deploying-nodejs)
- [Domain Names,Name Servers, and Cloud Based Servers explained with CodeScool](https://www.codeschool.com/beginners-guide-to-web-development/deploying-your-first-website)
- [Introduction to Heroku by Salesforce](https://www.youtube.com/watch?v=QTOkqzCTGxw) 38 min video

### Mini Lesson

Have you heard of Heroku before? If you had to guess what it is or what it does, what would your guess be? Take a minute and jot down at least two sentences to document your answers. Great, now that we've gotten that part out of the way...
Heroku is a cloud based service. But why should you or would you use Heroku? With Heroku, you can create a live version of your site for people to interact with and for you to showcase your functional web apps.

-Create a Heroku account using the link found in the prerequisites
-Download the Heroku CLI using the brew install link above
-Next, navigate to the root directory of your app, and run > `npm init`
-That last step will walk you through creating a package.json file, in it you can expect to JSON.
- Next run > `heroku local web` if dependencies are missing type > `rm -rf node_modules; npm install --production`





### Common Mistakes / Misconceptions

This is something that students might not realize or might assume at first.

Make sure they avoid this: thing


### Guided Practice

Have the students work with you as you do something.


### Independent Practice

Class does this thing themselves with specific additional items.


### Challenge

Students can try to do this other thing.


### Check for Understanding

Have students summarize to each other, make a cheat sheet, take a quiz, do an assignment, or something else that helps assess their understanding.

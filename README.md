# face-detector

This application can detect faces using image urls, which can be accessed from the register and login system (the application is local to the system
so any data can be inputted). Once logged in, users can also view the amount of images they have scanned.

This is the front-end portion of the application, and requires the back-end portion with the API (https://github.com/VTeas2000/face-detector-api)
in order to access all features of the application.

In order to run this application (RUN THE BACK-END API PORTION FIRST):
1. Clone this repository
2. Run `npm install`
3. Run `npm start`
(Agree if prompted to run this front-end portion on another port)

The App.js file contains my own Clarifai API key from (https://clarifai.com/). It can be replaced with your own Clarifai API key if you desire.

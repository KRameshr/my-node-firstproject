Project: Build an API using NodeJS

Industry: General

Problem Statement:

Your company wants you to build an API which can sign up and sign in users based on data provided by the users when using the API Description: In this project we will use ExpressJS to build and serve the API. The API needs to be able to accept user data and store it in a mongodb server. At the time of sign up check if the user is unique and at the time of sign in check if username and password match and are available in the database.

Tasks to be performed:

 Initialize an empty npm project
 Install express and a mongodb package (either mongodb or mongoose)
 Create routes for sign up and sign in with POST as request method
 In sign up check if user does not already exist in the database. If not then check if password is at least 5 characters long and add it to the database.
 If either or both condition returns false, then return an error to the user with the appropriate error messages.
 Make sure to hash the password before storing them in the database (use the bcrypt package)
 During sign in check if username exists and then check if the given password matches. If it does return a randomly generated token of 64length
 If username does not exist or password is incorrect return an error with 404 status code and message incorrect credentials
 NOTE: When comparing passwords make sure you are comparing the hashed version of passwords with each other. 

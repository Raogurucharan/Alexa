# Live Astronaut 

This repository contains code for Live Astronaut skill built for Alexa devices.This skill helps you find the number and names of Astronauts that are currently in space. 

# About Alexa Skills Kit

The Alexa Skills Kit (ASK) is a software development framework that enables you to create content, called skills. Skills are like apps for Alexa. With an interactive voice interface, Alexa gives users a hands-free way to interact with your skill. Users can use their voice to perform everyday tasks like checking the news, listening to music, or playing a game.

# Okay! How does this work ?

* When you call the invocation for Alexa , lets say something like "Alexa, how many people are in sppace currently?" a AWS lambda function is triggered to run the code and the code fetches the name and number of result from Opensea API .
* Once the result is returned alexa will speak/display the result.

Tech stack:
* Node.js
* AWS lambda
* API's

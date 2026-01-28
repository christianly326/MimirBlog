---
title: "Supervisor Meeting"
excerpt_separator: "<!--more-->"
date: 2026-01-28
categories:
  - Sprint 9
tags:
  - meeting
  - supervisor meeting
show_date: true
---
We updated Dr. Nie of our progress since the last meeting

- We concluded the tests to decide on what ai to use - its claude sonnet 4.5
- We ran into some issues with the tests for the clothing generation on an avatar
  - OOTDiffusion - made error and mistakes when using their own example clothing and changed the visuals of the the avatr
  - VITON-HD - was successful using the example clothing and avatars but when trying to use our own clothing the model was unsuccessful in even generated a fully black tank top onto the avatar. This modeel was suspected to be the one used in the final mimir project but with this poor performance we had to search for other models
  - Cat-V2TON - this is the new model we found to hopefully use in the project, though when testing we ran into a local hardware issue as our own device only has 6GB gpu but this model requires at least 8GB gpu to run. As such we have decided to try testing out the model using Google Colab results are yet to be seen
- We worked on the implementation of the login system
  - Session werte implemented with the login so that a user stays logged in until their session expires
  - Experimented with the flutter packages fro the UI of the login
  - Completed login, signup and logout
- Have a backend implemented for the user wardrobe
  - This includes adding in clothes, seeing outsfits, removing clothing items from outfits all attched to the users profile
  - The front end is yet to be implemented for this just the backend works
- We asked for advice on when should we start cloud deployment - answer: now
- Additionally Dr. Nie recommended that even though the blog isnt a deliverable for this project we should continue writing and updating the blog to ensure that we can remember the issues we encountered during the development
- Finally Dr. Nie told us that we should set our own deadline for having a prototype to be completed of the project - she reccomends beginning of April as its a month before the official deadline

<!--more-->

**Attendees:** Christian Michael Lagura Yacapin, Dongyun Robin Nie
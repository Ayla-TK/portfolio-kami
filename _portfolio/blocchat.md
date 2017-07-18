---
layout: post
title: BlocChat
thumbnail-path: "img/bloc-chat.png"
short-description: BlocChat is a real-time chat application.

---

{:.center}
![]({{ site.baseurl }}/img/bloc-chat.png)

## Explanation

Used Angular and Firebase to create a real-time chat application from the ground up, including setting up the database. Basic wireframes were given but no starting HTML or CSS.

## Problem

In addition to the creation of the application and database, the functions of the app for the user need to include seeing a list of available chat rooms, ability to create new chat rooms, see a list of messages in each chat room, set their username to display in chat rooms, and send messages associated with their username in a chatroom.

## Solution

An AngularJS application was developed that utilizes Firebase to store the chatroom and message data.

List of chat rooms

A service was created to access the rooms listed in the database. The rooms were displayed using the ng-repeat directive and ng-click directives were added to update the chat display area based on what room the user clicked-on.

Create new chat rooms 

Using UI Bootstrap’s $uibModal service, a modal form pop-up was developed for the user to create a new room. When submitted, it utilized the service to immediately update the database and show the available room in view.

Set username

The Angular cookies module was integrated. Then a new service was created in order to access and store a username in a cookie. They would only be prompted if their username had not already been saved. Once a new user entered their username the modal closed.  

Send messages

Additional functionality was added to existing services in order to  send the required information (username, room, time posted and message) to the database. A function was built in the controller to populate the object with the required information when a user submits a message.

## Results

All user requirements were met and some additional items were added to help improve the user experience.

## Conclusion

BlocChat is a functional chatroom.  It deepened my knowledge and understanding of Angular and challenged me to troubleshoot more on my own.  
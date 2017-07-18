---
layout: post
title: BlocJams
thumbnail-path: "img/bloc-jams.png"
short-description: Bloc-Jams is a Spotify-inspired music player application built with jQuery and AngularJS

---

{:.center}
![]({{ site.baseurl }}/img/bloc-jams.png)

## Explanation

Bloc-Jams is the front-end foundation curriculum project which teaches the basics of front-end development using HTML, CSS, JavaScript, jQuery and AngularJS.

## Problem

The first part of the project focused on building a foundation of HTML, CSS and JavaScript. The app’s style needed to be consistent with modern web applications, have a responsive design and interactive abilities.  The second part of the project required building a functional music player using jQuery. Lastly, the BlocJams was reworked to use the Angular JS framework.

## Solution

HTML and CSS

Responsive Design

This involved using viewport and media queries with CSS to apply styles based on device breakpoints.

Interactive app

First DOM scripting with JavaScript was used to make the app interactive. Later, the application was refactored with jQuery, introducing a music player with play/pause and seek functionality. Using jQuery helps to code faster and easier compared to JavaScript. However there are tradeoffs with the switch. jQuery will run slower because its library is running alongside your own code.

Refactoring with Angular JS

The site was centered around one Angular module built with a UI-router to connect the different controllers and services. The controllers were organized according to the different pages within the application- one for the landing page, one for the collection of albums, and one for the album page that lists the album songs. A player-bar controller was also created to compartmentalize the functionality of the bottom bar and incorporate it in the appropriate views.

## Results

The application is fully functioning with the ability to navigate between the different pages. The song player will play songs upon request with the ability to stop, pause, skip to the next/previous song, skip to a later point in the song, and to control the volume.



## Conclusion

Building an app from the ground up was a challenging learning experience.  It taught me the languages, the process, and the resources available to compose a site.  

Particularly, Angular was an efficient way to build this web based music player. BuzzFeed sounds made simple music tasks such as start, stop, and play easy. The UI-Router was an easy and efficient way to structure the application that made the single page application very effective.

I still have a long way to go but this site built a strong foundation.
---
layout: post
title:      "My Javascript SPA with Rails backend - Community Library"
date:       2020-03-07 22:59:57 +0000
permalink:  my_javascript_spa_with_rails_backend_-_community_library
---


Finally a project with Javascript! For my fourth project, I had to build a single page application(SPA) with a Javascript front-end and a Rails backend. For this project, I decided to build a simple library web application that an extracurricular literature club can use to facilitate the members of the club in borrowing books.

There were some big differences with how I built this project compared to the previous projects I built with just Rails. The obvious difference was the fact that, instead of using Rails to build out the frontend and backend, I was using Rails as just an api backend and using HTML, CSS, and Javascript to build my frontend. This big change made me see how I can use fetch requests to send and receive information to the backend. By using get fetch, post fetch and patch fetch for my app, I was able those fetch requests to asynchronously fire off the code I wrote, sending and receiving information to and from the backend.

The other big difference was the ability to dynamically change the DOM to make the page interactive and display information based on events. I found myself frequently using .querySelector to find and grab specific elements and I also learned the magic of using event listeners  to elements to make things dynamic. In my journey of using event listeners, I was even able to use event delegation to trigger events on elements that were not there in the beginning but were dynamically added by my code and a user’s input.

All in all even though it was a challenge switching from just using Rails, I really enjoyed building this single page application. Using Rails as just an api was definitely similar but also different, and using vanilla Javascript to be responsible for the frontend was something I really enjoyed learning about and also implementing. Now that I experienced building this app using vanilla Ja

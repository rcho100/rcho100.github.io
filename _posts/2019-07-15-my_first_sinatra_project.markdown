---
layout: post
title:      "My First Sinatra Project"
date:       2019-07-15 04:19:53 +0000
permalink:  my_first_sinatra_project
---


I have completed my first Sinatra Project! I am very excited that I was able to accomplish this task of making my own sinatra application. I remember my first CLI project was a bit daunting to me at first, since it was my very first coding project that I had to build from the ground up. 

The sinatra application I created is basically a web application where users can sign up and start documenting and listing all their favorite games, from past to present. A user first has to sign up if they do not have an account already, and once they have an account, the user is able to log in to access the rest of the site. To help me get this application up and running, I used the corneal gem to help put some structure in place. Then I proceeded to make the necessary migration files and migrating the files to create my tables. I also used the MVC (Model-View-Controller) pattern to provide a separation of concerns with all the different parts of this application.

For the models in this application, I created the user model and the game model and set the associations for the user to have many games and for a game to belong to a user. Then for the controllers I made a users controller and a games controller and had them inherit from the application controller that was made through the corneal gem. I then made some modifications and also added some helper methods, so I can use them throughout the controller files and even the view files when needed. As I worked on the individual routes in the controller files, I made the view files in tandem with all the routes to have a better sense of the flow of the application. 

As I was working on this application, there were two things that I realized. The first was the fact that I was running shotgun, more than I thought I would. Throughout the development process, the ability to run shotgun proved to be a great tool in helping me build features and also debug. The second thing I realized was the fact that I was not getting overwhelmed or anxious during the process of building this application. To my delight, I realized that I was able to be calm headed whenever something broke and wasn't working in my application. I think in the past I would have been more overwhelmed but I felt a lot more comfortable working on this project compared to the first project that I worked on. I hope this will encourage whoever reads this, that if you work hard, you will see progress!

---
layout: post
title:      "My React & Redux Project - Movie Central"
date:       2020-07-02 20:56:01 +0000
permalink:  my_react_and_redux_project_-_movie_central
---


For my fifth project, I made a web application using the very popular JavaScript framework React & also the handy framework Redux. Growing up I was never really into watching movies and I became somewhat known to not keep up with all the popular movies and as someone who didn't watch movies that are considered "classic movies". Hoping to increase my knowledge of movie references and be more in the know, I wanted to create an app that will be helpful to me and to others in seeing what movies were currently popular and also the movies that are rated very highly.

To create this project I used React & Redux for the frontend of my application and Ruby on Rails as an api for the backend of my application. With React I was able to build components that I can reuse at will to build out the client side. With the help of Redux and redux thunk, I was able to asynchronously send fetch requests to the Rails api I built. 

I decided that this application will allow users to browse through popular movies and top rated movies. I also inculded the option of adding a specific movie to a watchlist specific to every user, but this function is only open to users who register and is logged in to their account. I made this decision with the notion that while logging into and account to save movies to a watchlist is a great feature, I did not want an authentication wall to block people from browsing through movies.

I also used The Movie Database API as an external api to get the info I wanted on all the movies. I made the choice to make the get requests from the rails api I built and then send the necessary info to the front end of my application when a GET request would come in from the user. Although there was the possibility of just building out the frontend and letting it communicate with the TMDB API directly, I felt that it would be better to have the info centralized in my Rails API as was also using it as a way to persist user account information including the movies that a user saves into their watchlist. 

With all of the HTML requests being made from the frontend, I used Redux to have a central store to organize state better in my React frontend. I still made use of passing in props but the redux store definitely helped in organizing state as I built this application. 

All in all, I was able to experience first-hand the power of React & also Redux. It is no wonder why React is so popular today, and I am looking forward to making a React application in the future using Hooks to experience another way to control state.

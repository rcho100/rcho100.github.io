---
layout: post
title:      "My Rails Project - Save the Food"
date:       2019-10-05 00:54:33 +0000
permalink:  my_rails_project_-_save_the_food
---


I am excited to say that I have finished my Rails project! For this project, I decided to create a recipe manager application. I thought of this idea as something that might be useful for the people that I know, to share recipes with each other as we have increasingly leaned towards cooking something ourselves instead of eating out. Then I figured that if the app were to be used by a greater number of people than my circle, it would be helpful to have the feature to review recipes that other people have added onto the app. 

As I started to plan out my app, I realized that figuring out the associations between the models was a lot harder than I first thought it would be. Even though I had a basic outline on what the models in the app would look like with the attributes and associations, I found myself having to make create more files to migrate in the migrate file, to modify a table in some way. I originally had four models: User, Recipe, Ingredient, and Review. I had the Review table to be a join table to establish associations between User and Review. When I was planning this out, I only planned to have one join table in my app. As I was building the app however, I realized that I needed to add another join table to connect Recipe and Ingredient in a many to many relationship. With this change and some other minor changes I became very thankful that I was able to make those changes easily through the migration files. 

After establishing all the associations in the models, I proceeded to add all the necessary routes, controller actions, forms and other view pages. I found it very cool to use some Rails macros as well to help in setting my app up. Things like accepts_nested_attributes_for and validates came very useful for me in implementing a nested form and validations, respectively. 

There were many things that I found interesting, while working on this app, but there were two specific things about this app that I thought was really. The first was adding some styling to the app with bootstrap. There were no styling requirements for this project, but I felt like I should add at least some, given that this was looking like a bigger project than the ones I worked on before. Working with bootstrap, of course I had to make some modification and only use what I needed, but it was really helpful in adding stying quickly. The second was implementing OAuth with Omniauth. I used Google as the OAuth provider for my app and as someone who always wondered how that whole process worked, it was nice to learn how it works and to implement it in my app. 

This project is definitely the biggest project that I have completed thus far and I am very pleased with the outcome. I'm definitely looking forward to making tweaks to the app in the future and to adding in javascript to the app.

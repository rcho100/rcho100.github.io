---
layout: post
title:      "My First CLI Data Gem"
date:       2018-09-27 21:34:49 +0000
permalink:  my_first_cli_data_gem
---


I have finally finished my first CLI Data Gem Project! It feels like this was a long time coming, but I finally was able to complete this gem! As this was my first portfolio project, it was daunting to begin to build this app at first. As I read and continued to code however, it became less and less daunting and I was able to enjoy building my first gem. I especially became a lot more confident with scraping, as I feel like that took the most time to implement than the other parts of the gem. 

The CLI Data Gem I made, shows a list of broadway shows that are currently playing. I had my executable file call a new instance of my CLI class and called the call instance method to start my program. Once the program is executed, a welcome message appears in the terminal and then a list of current popular broadway shows appears after the welcome message. After the list is shown, a prompt appears informing the user to enter a number corresponding to the show they would like more info on. The prompt also gives an option to see the list again or exit the program. Once a user enters a number corresponding to a show they are interested in, the name of the show is presented along with other details pertaining to that specific show, such as the theatre it is playing at, the run-time of the show, and a brief description of the show. Once the additional details are presented the program gives the option of choosing another number to get details on another show, show the list of shows again, or exit the program. This pattern continues until the user types 'exit' to exit out of the program.

The scraping portion did give me a lot of trouble at first because the website itself had some html that was not done in the clearest way possible. I learned that when I scrape websites, there will be a lot of sites that aren't as clear, but I would have to adapt and work with what I have. By working on this project, I feel I have gained a lot of experience to scrape with much more ease the next time I need to scrape a website for an application I am working on.

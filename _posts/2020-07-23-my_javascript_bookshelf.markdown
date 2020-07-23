---
layout: post
title:      "My JavaScript Bookshelf"
date:       2020-07-23 16:30:34 +0000
permalink:  my_javascript_bookshelf
---


  Never having built an API or JavaScript web site before, I was prepared for many challenges going into my fourth project.  It was nice to still exist within the familiar realm of Ruby on Rails while venturing into the unknown.  I found JavaScript to have several similar elements to Ruby on Rails making it easier to learn.  

  Lots of ideas surrounded me as I attempted to choose a topic for my JavaScript project.  I thought of several game ideas and tried them out, such as a Wordsearch.  I was not happy with my results however, so in the end, I chose to make a Bookshelf.  

  I started my project by creating the backend elements.  I set up two controllers, two models, two databases, and added the appropriate routes.  I ran into one error while creating the backend of my program.  I realized that I needed to create the author table first since each book belonged to an author.  Overall, creating the backend API was not that different from creating a regular Ruby on Rails application.

  After completing my backend API, I started to work on the frontend.  I started my frontend by creating an index.html page and an index.js page.  I added the appropriate content to each page, then created a JS page for both of my objects.  I also created an app page that contained the main functions and an adapter page that contained the fetch requests.  The index.js page called the fetch requests and the listeners so that they would start when the program loaded.

  After working on the backend and the main elements of the frontend, I decided that I would like to add the ability for the user to add an author and to delete a book as well as update the author’s name or book title.  I created new fetch requests for each action and also updated the html layout for the author and the book sections to allow the user to perform these actions.  I learned that I needed to push my change to GitHub for each section before switching to either the backend or the frontend.  

  I ran into several small bugs and several larger issues while building this project.  Since I was new to JavaScript, it took me awhile to get used to trouble shooting using the console.  I also learned how to display the values of variables on the console so that I could see what was going on.  One of the largest issues I faced was within my findByID function listed on the JavaScript page for each object.  After searching around and posting to Stack Overflow, I realized that I needed the + sign when comparing my ID within my function.  

  I also ran into a couple of issues while building the section of my program that allowed the user to delete books.  I learned how to debug using the terminal for my backend in order to solve this issue.  There were several errors within my backend code that prevented the book from being deleted.  Once I solved the issues and bugs, I was happy with my finished result.  


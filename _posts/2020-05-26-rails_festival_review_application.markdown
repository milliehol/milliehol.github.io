---
layout: post
title:      "Rails Festival Review Application"
date:       2020-05-26 23:17:35 +0000
permalink:  rails_festival_review_application
---


I approached my third project with excitement and very little angst.  I realized that it was similar in many ways to my second project, so I was confident from my last experience that I could complete it with ease.  I looked forward to this next endeavor.

I relied on a friend’s hobby interest when deciding on the topic for my third project.  She enjoys attending festivals so I decided to create an application that would allow a user to add and rate festivals in various cities.  The application would also allow a user to login using GitHub.

I chose four main areas to include in my project that would align directly with my database tables.  I chose to add a users section, reviews section, festivals section, and cities section.  I added their database files, view files, control sections, and routes by using the Resource Rails generator.  This allowed me to automatically create many sections with one line of code.  

After creating the four main sections, I started to edit the navigation and main application layout pages.  I added several stylistic elements before I created the main root page within a sessions layout folder.  I linked the user to two pages that allowed them to sign up or login.  I created separate routes for each of these elements.  

After working on the beginning elements, I added the necessary code within the user’s controller page and the session’s controller page.  These aspects allowed the user to log in and lot out successfully.  Subsequently, I worked on the city and festival controllers and layout pages.  Lastly, I added the review section controller and layout code.

The two greatest problems that I ran into while creating this project were adding the dropdown menu that used bootstrap and the Omniauth login.  After trying various methods of code for the dropdown menu, I realized that I needed to add Webpacker since I was using Rails 6.  Rails 6 links to Javascript through Webpacker instead of the assets section.  After directly installing Webpacker in my console, I needed to change several aspects of my html code before the menu finally functioned correctly.  

The second issue I ran into was the Omniauth login not working initially.  I tried the Google login first and after that did not work, I tried adding the Github login.  The error I kept receiving was the User ID could not be found.  I wondered why the user was not added to the database after the information was retrieved.  After learning how to work the console debugger, I found out that the e-mail was sent over as nil from Github and the user account was not created because of this.  After I added a public e-mail on Github, everything within my application functioned smoothly.  


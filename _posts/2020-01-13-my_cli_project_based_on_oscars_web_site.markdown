---
layout: post
title:      "My CLI Project based on Oscars Web Site"
date:       2020-01-14 02:49:23 +0000
permalink:  my_cli_project_based_on_oscars_web_site
---


I started the CLI project with excitement and trepidation since it was my first project within the Flatiron program.  After learning Ruby for the first time, I was overwhelmed with all of the knowledge I had gained within such a short period.  I was anticipating that my first project would be challenging but not too difficult to complete.  The time of year also posed issues due to the amount of activities that arose during the holiday period.

I decided to scrape a web site that listed the Oscar winners since the Inception of the award program.  I chose the page that listed the Oscar winners in the actor category.  After reviewing the scraping section on Flatiron, I opened up sandbox and entered the code that would allow me to scrap my desired information.  I tried lots of different types of scraping code before the actor data populated as I wished.

After obtaining the correct code that would allow me to scrape the Oscars site, I started reviewing past CLI projects and the modules included within the CLI section.  I observed that three main files were needed, so I created these within my test CLI project that I had created on Git Hub.  I wrote the code that allowed me to scrape the Oscars web site, then progressed to the command line page.  I wrote the call section and the sections that pulled the data from the different objects.  Then, I wrote the section that appeared to the user when they ran the program.  I modified it many times in order to create the flow that I desired.

I worked on the actors ruby file that created the objects that would appear when the user started the program.  I created one object for each year that corresponded to a separate actor winner.  After I added and modified all of the various files needed for the program, I tried running my program within the sandbox.  I ran into numerous and varied errors.  After I had modified my files so that the errors went away, the command line started to work.  However, I noticed that the scraping page was not working.

I posted my scraping file to Slack and received an answer to my question quickly.  I had used a div class that was no longer on the Oscars web site and modified my code so that it scraped the correct table.  After I updated my code, the program worked well.  At this point, I created a new repository on Git Hub and called it Oscars instead of Test-Cli.  I copied and renamed all of the various files needed for my program.  I ran the program within Sandbox and fixed all of the various errors that appeared.

After my program started working, I modified the CLI file again so that it flowed more smoothly.  I also adjusted my All class so that only the selections of years appeared that corresponded to Oscar winners and no other data was displayed.  I also added validation so that the user could not enter a number that was not available on the list.  I tested out my new additions and was happy when my program worked successfully.  


---
#Mid-term review
title: "Mid-term update"
date: 2018-03-13 18:00
author: Daniel
---

Since I finished installing the required softwares and cloning all of the needed github repositories, I began working on Github issues.

I have since taken on 3 issues:

	*Display of class locations
	*Consolidation of disjoint models
	*Fix bug which displays inconsistent colors on schedule view

My major goals for my first task were:

- Update the needed front-end files to display the class location

- Add a location column to the database

- Whitelist the location data in the needed back-end files

- Run the database migration


As of now, the YACS schedule displays the location of each section on the schedule. The next step, once the refactor of the front-end has been completed, will be to work on displaying class section locations in the course list window. 

For my second task, I was simply able to follow the detailed description on the Github issue to correctly name the new files and place them in the appropriate place. Then I went through all YACS-Web files and changed the neded imports to accomodate the updated files and their locations.

My third task was based around a bug which I found while testing the class location update. The issue was slightly clouded and required inspection of the YACS site to locate the error. In the end, it came down to a mismatch between the allocated section background color and display text colors. The issue was fixed by adding the missing colors and simplifing all arrays to one instnce of the colors. These arrays were then made class constants and an iteration loop was added to the file which allocates these colors to account for there being more selected classes than there are colors.    

I faced many challenges along the way from learning the basics of Ruby and running database migrations to learning how to correctly route files using git and github. At this point, I now have a clear understanding of the structure of both the YACS system and Angular 4.  
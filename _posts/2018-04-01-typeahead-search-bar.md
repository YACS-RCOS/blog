---
#YAML Front Matter.
title: "TypeAhead Search Bar Implementation Complete!"
date: 2018-04-01 6:24:00 -0400
author: "James Milne"
---

Hey everyone! Here’s an update on my progress for the YACS front-end team.

I have completed the front end implementation of the Notice Bar and it has been merged with the main branch. For this to be useful we still need the API to support notices. 
https://github.com/YACS-RCOS/yacs/issues/232
Now to my more recent project.

I have been working on the search bar, specifically adding a drop down feature that displays the best search matches so the user can selected exactly what class they are looking for without having to scroll through the search menu. 

Here are the list of features added: 
- Displays drop down after 3 characters have been typed in the search bar (not including whitespace)
- Displays a maximum of 10 search options
- Displays cross listed classes only once
- When an option is either clicked or entered from the drop down the user is taken to the specific page of the course they have selected, the general search is overridden
- If a course is cross listed and selected from the drop down, all cross listings will show
- The drop down is not auto selected so normal search functionality still works

This task has helped me understand angular and typescript to a much higher level. I have worked with anonymous functions, mapping, filtering and slicing to create the exact component implementation we need. I also worked with the HTML and ng-bootstrap to implement the ngb-typeahead feature. 

Besides just learning code I have also gained a better understanding of how to find the information I need online. A lot of this implementation is find out how to do it by googling. Normally if I couldn’t find what I was looking for on StackOverflow I assumed it didn’t exist. But I have recently learned to look through github issues and the official documentation of the library we are using (in this case ng-bootstrap). 

I am very happy to have implemented something that will be very useful to all users.

- James Milne

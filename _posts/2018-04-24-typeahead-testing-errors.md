---
#YAML Front Matter.
title: "TypeAhead Search Bar Testing Errors."
date: 2018-04-24 2:45:00 -0400
author: "James Milne"
---

Hey everyone! Here’s an update on my progress for the YACS front-end team.

Having completed the TypeAhead Search Bar implementation a few weeks ago, I have been working on testing through Jasmine. To start, the goal was to learn the basics of Jasmine. I looked through the current YACS spec files and through some online tutorials to find the general structure. I then set up Jasmine testing to run locally which wound up being much simpler than I anticipated. Running “npm test” in the correct folder is all you need once it is set up.

Through my research, as well as simply trial and error, I have discovered that testing bootstrap features with Jasmine is difficult if not impossible. After substantial time figuring out how to actually write the tests, I was unable to actually run them. It seems as though Jasmine does not support bootstrap’s TypeAhead feature because we could not get rid of the testing compilation errors. We tried various bootstrap imports into the spec file as well as adding the bootstrap library to the Jasmine packages file. 

I have decided to put front-end testing on hold for the rest of this semester. For the remaining time, I will continue to work on adding features to the search bar. Through my own manual testing and fairly simple implementation, I believe TypeAhead Search Bar feature to be stable. Though of course, testing would be nice.

James Milne



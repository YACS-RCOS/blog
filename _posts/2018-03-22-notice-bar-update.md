---
#YAML Front Matter.
title: "Notice Bar Progress and Issues"
date: 2018-03-22 12:20:00 -0400
author: "James Milne"
---

Work on the Notice Bar has proved to be more difficult than it first seemed. When I first read the issue and decided to do it I assumed I would simply be adding some text if there was a notice to display. But this quickly turned into a much more involved task. Don’t underestimate the size of a project, think through how it should be able to scale and plan for that, then start coding. 

After messing around with code for awhile we decided on the implementation, a detailed look of the implementation can be seen on the github issue page. https://github.com/YACS-RCOS/yacs/issues/232

Early on my issues came from my lack of experience with typescript and angular. This caused me to encounter a strange error that took ample debugging. My mistake was adding a member variable to the noticeService constructor. This was due to my confusion on how data was transferred between service to component to html. 

Having worked through most of the typescript implementation I began to work on the HTML and SCSS. I have never worked with CSS so figuring out how to simply move the notice bar out from behind the header bar was an issue. I finally found the keyword “margin-top” which allowed me to lock the notice bar under the header bar. 

Before I began to utilize bootstrap I was modeling the notice bar after the header bar. This was an ugly design that was bulky and unnecessary. Through bootstrap alerts, notice bar can be simply displayed. 

Slowly I have been learning the front end of YACS. This project has taken me much longer than expected but the end result will be very functional.

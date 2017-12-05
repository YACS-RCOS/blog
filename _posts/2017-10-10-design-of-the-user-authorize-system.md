---
layout: post
title: User System Implementation
date: 2017-10-10 12:32:40
type: post
author: Yuze Ma
---

To be cotinued, we were stuck on choosing the proper implmentation for the user authorization system. Finally, after a long discussion, we decided to choose the one we came out with a week a go. It looks like this:

![DB_Diagram](/assets/images/DB_Diagram.png){: width="300"}

We choose to separate the users and roles into separate tables, which allows us to dynamically change rights for a user.

However, it may also leads to the problem of querying rights of a user every single time if a user needs to be authentiated to do something. It does takes a while to combine tables and do query compared with a mathmatically supported user sytem. Personally, I think this problem could be implemented well if we properly arrage the rights in roles table. To be honest, I may not need to worry about it for now, and I think our solution is the best for current purpose. 

I can't wait to see it!

#GO YACS
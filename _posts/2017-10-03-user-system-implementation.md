---
layout: post
title: User System Implementation
date: 2017-10-03 18:10:40
type: post
author: Yuze Ma
---

Yo, this is Yuze. I'm new to the team, and currently working on the integration with the user system for yacs.

Lately, Richy and I were talking about how we should make the integration with user management system for YACS to make it into a more official project. We ended up in writing a new backend rather than adding code to the original repo, and the original service will be served as service while the new user system will be served as an intermediate to call those services.

Hopefully, our new system should work like :

#### user -> user system -> yacs backend -> YACS_DB

We are having more discussion about how we should split users roles because it is kind complicated on campus. We might make use of the design from Linux, which is user, admin, and super admin. Haven't figured out yet, but will be out soon.

The baisc database diagram is presented below:

![DB_Diagram](/assets/images/DB_Diagram.png){: width="300"}

#GO YACS
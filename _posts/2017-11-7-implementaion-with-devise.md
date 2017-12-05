---
layout: post
title: User System Implementation
date: 2017-11-7 19:30:40
type: post
author: Yuze Ma
---

This week, we officially started working on the code.

To avoid spending too much time understanding how the existing yacs-core works, we decided to start a new repo handling the whole user system, which basically includes:

- User Sign Up
- User Log In
- User Log Out
- User authorize

One thing good about using Ruby On Rails to do web dev is the frameworks that has been built already.The process of programming is much faster than with other frameworks and languages, partly because of the object-oriented nature of Ruby and the vast collection of open source code available within the Rails community.

We choose to use [Devise](https://github.com/plataformatec/devise) to do our basic user system implementation like user sign up and login. After that, we built our own yacs-auth library to do authentications works.

However, it is not very easy to make use of this module, because it has too many features that we don't want. We have to manually modify this module and localize the dependency to do this. For example, we changed the HTTP request for user log out.

Another thing I don't quite like about Ruby is its dependency usage method. It make use of modules like the way python does, which is using the file from the system level. Compared with NodeJs, this is actually very inconvenient for a dev team with several developers. I'm sure there is someway to user all dependencies from the current working directory rather than the ruby inside the system, but I haven't figured yet.

We'll see.
#GO YACS
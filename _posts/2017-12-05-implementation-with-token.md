---
layout: post
title: User System Implementation
date: 2017-12-5 14:54:21
type: post
author: Yuze Ma
---

Right after finished re-design the SingUp and SignIn form, we are on the stage of passing the token after user logged in.

However, before that, we worked on building the docker image. We haven't given this new image a name yet. Hence, if we want to build it, we need to run 
```
docker build .
```

and 

```
docker run -tid --name yacs-user -v <PATH_ON_MY_LAPTOP>:/usr/src/app <IMAGE_ID>
```

Hopefully, we will get that fixed soon, or it just gonna be really annoying to run it because we have to know the newly generated id like df615afcbb90.

We also implemented the function for user to jump back to where they are from after they sign in, which is really nice.

Ideally, we can get it work with core in short.

We'll see.
#GO YACS
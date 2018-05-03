---
layout: post
title: Interactive Chart
date: 2018-04-12 11:32:44 
type: post
author: Yuze Ma
---

After using Jupyter notebook for weeks, we have quite a lot to say about it, and here is a short Pros. Vs Cons. for using python jupyternotebook.


On the good side, jupyternotebook is eays to deploy with docker. Now, yacs-BI team can have the whole development environment with one single command. Also, it supports using Bash shell with in the jupyternotebook, which is extremely helpful when we need to install some new package/module inside the python running environment.

Besides, it also support R language as well for building prototype on prediction model.

However, here are some hazards on using jupyternotebook:

First and foremost, the python kernal is very likely to collapse when it wants to collapse or the task in the current kernal is loading way too m
uch work.

Next, python jupyter notebook is not easily for team collaboration. So far, I haven't find any modules could be "inserted" in to notebook system for using git. Maybe we could do that from the bash interface.

Lastly, the graph generated are static. That is to say, we cannot interact with the generated graph.

Luckly, we get to find a module called [Bokeh](bokeh.pydata.org/en/latest/). Bokeh is an interactive visualization library that targets modern web browsers for presentation. Its goal is to provide elegant, concise construction of versatile graphics, and to extend this capability with high-performance interactivity over very large or streaming datasets. Bokeh can help anyone who would like to quickly and easily create interactive plots, dashboards, and data applications.

We've installed it and merged it into the master branch. However, we are still working on deploying that to the production server. We'll see.


Go Yacs.



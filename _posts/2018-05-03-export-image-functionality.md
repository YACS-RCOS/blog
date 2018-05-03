---
#export image
layout: post
title: "Export Image Functionality"
date: 2018-05-03 00:00
type: post
author: Haochang Qian
---

Hi everyone! It's very glad to work with YACS development team this semester. And here is my progress for this semester. I'd like to introduce a new feature to you — exporting schedule as an image.

They way to convert DOM element on the page into an image cannot be done directly. It has to be converted to a canvas element, then, to an image. I initially tried to write this function myself. Unfortunately, the work is not that easy, and considered the development efficiency, I chose to use a package called `dom-to-image`, which let me easily accomplish this function.

However, when I want to select a DOM element, I was told not to use javascript `document.getElementById`. It took me a long time to understand how to use `viewChild`, which is a "more angular way" to do so.

At the time I finished this task, I found I really learned a lot.

Hope I can learn more and make more contribution next semester.

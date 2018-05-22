---
layout: post
title: Fall 2017 Proposal
date: 2017-09-17 20:00:00
type: post
author: Ada
---

Hello Everyone,

We are back! In preparation for the Fall semester, we've outlined our high-level goals and proposal for the next few months. Our proposal is listed below! As always though, we are very open to suggestions and new ideas, so feel free to email us if you have any requests.

# YACS Fall 2017 Proposal

# Team
----------

Ada Young - architecture
Cameron Root - frontend, core
Kathleen Burkhardt - full stack, admin
Ayushi Mishra - design, core & planner
Mark Robinson - mobile & devops
Cole Gregory - admin
Rutvik Manohar - frontend, core
Perri Adams - backend, core
Yuze Bob Ma - backend, users
Alex Zuckut - frontend, tests

# Description
----------

YACS, or Yet Another Course Scheduler, is a tool to help students create schedules and find courses. Its aim is to make planning a semester as painless as possible. YACS also aims to be easily portable and compatible with colleges other than RPI.

This semester is focused on extending the application and ecosystem we have create to allow for development of advanced new features, and to improve the modularity of the system. By the end of the semester we intend to have a fully modular YACS with several extensions, including Planner and the Admin Panel. We also intend to finally address some long awaited features, and begin leveraging the data updated we have access to to track changes over time.

In order to realize some of these goals and improve usability, the API will need to be re-versioned to V6. API V6 will have streamlined support to multiple semesters, field selection, relational requests, pagination, and will be normalized for efficiency.

# Goals
----------

At a high level, our goals this semester are to deploy YACS at another school, finish our authentication, user, and admin systems, polish our new front-end and begin developing new features.

Our goals are divided into the following milestones.

## Finish the new Update Architecture (9/31)
[ ] Create batch API update actions
[ ] Write and service to pull from data source and push to YACS
[ ] Finish data aggregator service
[ ] End-to-End test the entire system
## Finish the new Angular Frontend ( 9/24)
[ ] Finish Schedule View
[ ] Re-implement sharing features
## Improve Schedule View (9/31)
[ ] Create interactive frontend grid to add custom events
[ ] Enhance schedule view 
## Support Multiple Semesters ( 10/15)
[ ] Finalize new semester / course data model
[ ] Write migrations to adapt old schema
[ ] Expand API to include multiple semesters
## Finish Admin / User system
[ ] Integrate authentication into admin panel
[ ] Create user login / data service
[ ] Create login view with configurable redirects
[ ] Integrate login into core frontend
[ ] Store and pull saved preferences and schedules from user data service
## Create Notification System (10/31)
[ ] Finish and merge notifier
[ ] Create node.js bouncer service to read from redis and write to an EventSource
[ ] Create angular component for events
[ ] Create angular service to read from stream
[ ] Create angular component to hold and update event stream
## Optimize API (11/15)
[ ] Add pagination
[ ] Normalize relational data
[ ] Add rate limiting
[ ] Change DSLs to generators
## Deploy YACS at another school (TBD)
[ ] Create static site
[ ] Move blog to static site
[ ] Make blog posts for every release
[ ] Create formal instructions for creating a data service
[ ] Compare schema to other schools
[ ] Work with students from NYU
# Team Contract
----------
## Issues

All pending and in-progress work will be tracked using Github issues. All contributions should correspond to a specific issue. Questions and comments regarding acceptance criteria and implementation details should be made as comments on the issue, as opposed to slack conversations or other communication channels.

## Contributing

Contributors will fork the project, and submit pull requests to the staging branch once an issue is complete and build checks have passed. All pull requests should have a passing build. Once the PR has been peer-reviewed the work will be merged into staging. Before being merged into master and deployed, the changes should be manually vetted in the staging environment. These instructions will be mirrored on the project README, which is the point-of-truth for this information.

## Code of Conduct

All participants and community members must adhere to the Contributor Covenant Code of Conduct. In general, students 

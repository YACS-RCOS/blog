---
layout: post
title: YACS Admin - Big News
date: 2017-12-31 16:12:28
type: post
author: Kathleen 
---

I wasn't intending on working on YACS Admin over winter break, but the YACS team wanted the admin panel to be working with real data by the beginning of the semester.

On the final day of 2017, I am glad to announce that the admin panel works with both fake and real data!

Before this big update, the service used to interact with mock data was `FakeYacsService`. Now, there is a master `YacsService` that both the `FakeYacsService` and the new `YacsProdService` inherit from. Below is a UML diagram of the new system:

![uml-diagram](https://i.imgur.com/qf5NYXd.png)

Both the `prod` and `staging` environments now use the new `YacsProdService` to load real data into the application. The `dev` environment still uses `FakeYacsService`, and the automated tests run off the `dev` environment.

With that in mind, here are the revised goals for Spring 2018:
  - Load data on demand to improve page load time with real data
  - Implement core frontend functionality across all four objects (schools, depts, courses, sections)
  - Implement periods 
  - Add search functionality
  - Frontend improvements
    - Loading animation
    - Consistent use of icons
    - Highlight active tab
    - Add footer (imported from `yacs-web`)
    - Make cursor consistent among all links
  - Better project management
    - Use Projects to track sprints/milestones
    - Create an issue and pull request template
  - Test and build automation
    - Use Grunt or Gulp to automate prod, test, and dev builds
    - Integrate with Docker and Travis
    - Generate test coverage reports
  - Integrate test/build automation into repository
  - Possibly upgrade to Angular 5 (or whatever version Angular will be on in 1-6 months)

A possible stretch goal would be to have a logging system for changes and errors, but that would require yet another backend, so it could be a possible summer or fall project. I will be interning in the city this summer, so if this is implemented in the summer, I wouldn't really be able to do much.

Here's to a productive 2018!

---

layout: post
title: YACS Admin - Semester in Review
date: 2017-12-02 17:20:00
type: post
author: Kathleen
---

It's very hard to believe the semester is coming to a close already!

Since I last blogged, significant progress has been made by both team members. Here is an overview of what has been completed, what is in progress, and what still needs to be done.

Completed:
- Frontend for departments and schools
- Create, update, and delete operations for departments and schools using a mock service
- Better test coverage
- Filtering courses by department
- Code of conduct, contributing guidelines
- Staging branch separated from master branch

In progress:
- Frontend for courses and sections
- Adding periods to sections
- Mock YacsService

What's left for this semester:
- Create, update, and delete operations for courses, sections, periods
- Filter departments by school, sections by course
- Use Bootstrap modals for confirmation

Before the end of the semester, we should meet two of the three milestones I defined in my last blog post: completing the bare minimum frontend design and completing CRUD functionality. 

Although it looks like we do not have time to implement a "real" backend integration or "extra" frontend features, this semester is ending on a much higher note than last semester. Even though we had to essentially start from square one, the development process has gone much more smoothly despite bugs. Implementing tests from the start allowed us to constantly have a working product on the master branch as well as easily identify bugs.

In addition, I have learned a lot this semester including:
  - Technical:
    - Angular with TypeScript
    - Jasmine
  - Project management:
    - Using wireframes
    - Keeping track of branches
    - Setting up a GitHub repo for community
  - Soft skills:
    - Improved mentorship skills
      - Running a small group
      - Giving feedback
      - I noticed that I was a lot less overwhelmed this semester with one semester of mentorship under my belt.
    - Improved team communication skills

With that in mind, here are some tentative goals for next semester:
  - Create a production mode with a real YacsService
    - Dev mode and test mode will still use FakeYacsService
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

YACS will be presenting this Friday, so we are also going to need to prepare for this presentation. I was absent from our first presentation as I was on an onsite interview, so I am looking forward to finally demoing my progress. 

Overall, this semester has been focused on refactoring the YACS Admin application with a much smoother experience for developers and users. Next semester will be focused on polishing the application for production use, as well as integrating any new features and fixing any new bugs that come up. I am looking forward to seeing the direction this project takes!
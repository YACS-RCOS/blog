---

layout: post
title: Test Suite Review
date: 2017-11-29 18:10:47
type: post
author: "Alex Z"
---
So far through the semester, fantastic progress has been made in regards to testing. I have completed testing for most components, which is great and look to finish the rest of the components as well as the services within the end of them semester. So far, the progress that has been to test that services render the correct data as well as just correctly running components. The issues have arose when trying to mock in data which has not been accepted by the components correctly and therefore, spits out errors. Currently I am fixing this which should be done soon and then the stretch target will be to implement a extensive test suite for the services that are provided for the web application.

The services that need to be tested include the conflict generator, the selection service, and finally the Yacs service that is referencing YAC's api.

To note, the greatest challenge that I have encountered while creating these tests was when I created a stub to receive the http request for the YACs service. Another issue encountered was with importing and declaring correctly with the jasmine/anulgar framework which in some cases can be quite confusing.

Overall good progress with frontend testing and I shall have an update in a few weeks!

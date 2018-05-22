---
#YACS at NYU
title: "The New YACS Data Pipeline"
date: 2018-03-28 13:00:00 -0400
author: "Ada"
---

Hello folks,

As promised, I'd like to provide some more details about the improvements we are
making to YACS to make it more robust, modular, and scalable.

One of the key goals of the YACS project has always been to create an
architecture that welcomes new developers and first time contributors, while
still being robust and modular enough to facilitate adoption at other schools.
To that end, we are internally working on an entirely new streaming data
pipeline.

The greatest challenge of having one pipeline that supports (ideally) any school
is that there are many different proprietary systems that schools use to manage
and expose their data to students, and many schools use a combination of several
systems. So, the main purpose of this pipeline is to be able to ingest data from
a variety of different sources, and amalgamate and filter that data in a way
that is flexible, and configurable.

In order to make this possible, while still be easy to implement, we've created
a spec for data sources to interface with YACS. The complete spec is in draft
stage, and is documented in the [repository](https://github.com/YACS-RCOS/hamilton).
But in short, any school can implement YACS by creating a an adapter that
conforms to the spec. We will post a full guide and set of tutortials on how to
do this after we test it out with the folks from NYU and work out the kinks.

So check back soon for more updates on how that's going, and for the tutorial
on how to bring YACS to your school!

Best,
Ada
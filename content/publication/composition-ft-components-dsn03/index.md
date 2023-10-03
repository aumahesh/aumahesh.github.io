---
abstract: >
  In this paper, we show how a distributed fault-tolerance
  component can be replaced dynamically. The need for
  such replacement arises due to the fact that there are often several
  fault-tolerance components that are suitable for adding faulttolerance
  to a fault, and the choice of the component depends
  upon the environment. Since a distributed fault-tolerance component
  has a fraction installed at every process, replacing such
  a component requires that the replacement be done consistently.
  More specifically, it requires that the dependency among the
  fractions of the component be handled so that a component
  fraction is not removed while other component fractions or
  the underlying application depends on it. We show how the
  dependency relation among component fractions is correctly
  handled while ensuring that the component replacement is
  transparent to the application. As an illustration of different types
  of dependency relations, we present a message communication
  example and show how dynamic composition is performed in it.
  Finally, in our approach, it is also possible to deal with faults
  that occur during dynamic composition.
author_notes:
authors:
  - Sandeep S. Kulkarni
  - Karun N. Biyani
  - admin
date: "2003-06-01"
doi: ""
featured: false
image:
  caption: ''
  focal_point: ""
  preview_only: false
projects:
publication: In proceedings of the *Workshop on Principles of Dependable Systems*
publication_short: In *Workshop on Principles of Dependable Systems*
publication_types:
- workshop
publishDate: "2003-06-01T00:00:00Z"
slides: 
summary: In this paper, we show how a distributed faulttolerance component can be replaced dynamically.
tags: ["distributed systems", "composition", "fault-tolerance"]
title: "Composing Distributed Fault-Tolerance Components"
url_code: 
url_dataset: 
url_pdf: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: 
url_video:
---



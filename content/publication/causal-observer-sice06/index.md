---
abstract: >
  In this paper, we focus on the problem of approximate causal delivery. This problem identifies the tradeoff between causal delivery and timely delivery of messages. Causal delivery requires that delivery of a message, say m, be delayed until all messages on whom m is causally dependent are delivered. By contrast, timely delivery requires that messages be delivered as soon as possible. In the context where messages could be lost and the value of messages decreases as the delay increases, the requirements of causal delivery and timely delivery are conflicting. We show how a simple logical timestamp program can be used to obtain a solution for approximate causal observer. This solution is intended for systems that provide simple guarantees about the clock drift and about maximum delay of messages that are not lost. While O(n2) unbounded integers are required to implement perfect causal delivery, our solution uses only O(log n) bounded space. Our solution permits a process to tradeoff between causal delivery and timely delivery, i.e., it allows the process to choose the level of causality violations it can tolerate (0% or more) and the time for which it will have to buffer the received messages. We also show that the information maintained by our program, although small, is important to provide such a tradeoff; we show that the number of causality violations increase by an order of magnitude if this information is not maintained. Finally, we show how our solution can be used to observe computations in sensor networks while providing a continuum where one can choose the size of the timestamps based on the acceptable level of causality violations.
author_notes:
authors:
  - Sandeep S. Kulkarni
  - admin
date: "2006-01-01"
doi: ""
featured: false
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/@jannerboy62)'
  focal_point: ""
  preview_only: false
projects:
publication:  Transactions of Society of Instrument and Control Engineers (SICE), Special Issue on Networked Sensing Systems
publication_short: In *SICE*
publication_types:
- journal
publishDate: "2006-01-01T00:00:00Z"
slides: 
summary: In this paper, we focus on the problem of approximate casual delivery. This problem identifies the tradeoff between causal delivery and timely delivery of messages. Causal delivery requires that delivery of a message, say m, be delayed until all messages on whom m is causally dependent are delivered. By contrast, timely delivery requires that messages be delivered as soon as possible.
tags: ["causal delivery", "timeliness", "logical timestamps", "sensor networks"]
title: "Approximate Causal Observer"
url_code: 
url_dataset: 
url_pdf: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: 
url_video:
---



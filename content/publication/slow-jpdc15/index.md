---
abstract: >
  Transformations from shared memory model to wireless sensor networks (WSNs) quickly become inefficient in the presence of prevalent message losses in WSNs, and this prohibits their wider adoption. To address this problem, we propose a variation of the shared memory model, the SF shared memory model, where the actions of each node are partitioned into slow actions and fast actions. The traditional shared memory model consists only of fast actions and a lost message can disable the nodes from execution. Slow actions, on the other hand, enable the nodes to use slightly stale state from other nodes, so a message loss does not prevent the nodes from execution. We quantify over the advantages of using slow actions under environments with varying message loss probabilities, and find that a slow action has asymptotically better chance of getting executed than a fast action when the message loss probability increases. We also present guidelines for helping the protocol designer identify which actions can be marked as slow so as to enable the transformed program to be more loosely-coupled, and tolerate communication problems (latency, loss) better.
author_notes:
authors:
  - Reza Hajisheykhi
  - Ling Zhu
  - admin
  - Murat Demirbas
  - Sandeep S. Kulkarni
date: "2015-03-01"
doi: ""
featured: false
image:
  caption: 
  focal_point: ""
  preview_only: false
projects:
publication: In *Journal of Parallel and Distributed Computing (JPDC)*
publication_short: In *JPDC*
publication_types:
- journal
publishDate: "2015-03-01T00:00:00Z"
slides: 
summary:  we propose a variation of the shared memory model, the SF shared memory model, where the actions of each node are partitioned into slow actions and fast actions. The traditional shared memory model consists only of fast actions and a lost message can disable the nodes from execution. Slow actions, on the other hand, enable the nodes to use slightly stale state from other nodes, so a message loss does not prevent the nodes from execution.
tags: ["sensor networks", "shared-memory model", "SF shared-memory model", "transformations", "slow actions", "fast actions"]
title: >
  ''Slow is Fast'' for Wireless Sensor Networks in the Presence of Message Losses
url_code: 
url_dataset: 
url_pdf: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: 
url_video:
---



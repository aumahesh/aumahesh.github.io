---
date: "2014-12-01"
external_link: ""
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
links:
slides: 
summary:  DHT provides a key-value store for NetScaler (now, called Citrix ADC) packet engines to store application state in multiple cores of a node or across multiple nodes/cores in a cluster.
tags:
- Professional
title: "Distributed hash table for Cluster of Citrix ADCs"
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

DHT provides a key-value store
for NetScaler (now, called Citrix ADC) packet engines to store application
state in multiple cores of a node or across multiple nodes/cores in a cluster.
DHT provides eventual consistency semantics to the applications. In this
project, I was responsible for the following: (i) reliable replication of
entries across the nodes, (ii) dealing with nodes joining/leaving (transitional
period) the cluster, (iii) hunting for existing key-value entry in the cluster
during transitional period. 
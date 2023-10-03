---
date: "2017-06-01"
external_link: ""
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
links:
slides: 
summary:  StyleBooks is a declarative language that allow users to consume NetScaler (now, called Citrix ADC) services in a variety of data center configurations and cloud architectures, providing both configuration simplification and smart operational visibility.
tags:
- Professional
title: "StyleBooks: A declarative configuration language for Citrix ADC"
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

StyleBooks is a declarative
language that allow users to consume NetScaler (now, called Citrix ADC)
services in a variety of data center configurations and cloud
architectures, providing both configuration simplification and smart
operational visibility. It captures useful NetScaler configuration and
includes operational aspects (health, counters, logs). New StyleBooks can be
created by cloning and modifying existing ones, or by composing existing
StyleBooks into new ones, thus, allowing for modular and incremental design.
In this project, I was responsible for the following: (i) compiler for
StyleBooks that generates an equivalent Python package, (ii) design of the
runtime engine that instantiates a compiled StyleBook to create an actual
configuration, (iii) design of config audit and config diffs for computing the
differences when an existing configuration is updated, (iv) design of the
REST APIs.
---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---



Improving Data Ingestion Performance in Apache AsterixDB
======
Data is parsed using a single node since the data intaking module and the data parsing
module are coupled together in AsterixDB currently, which does not utilize the advantage
of distributed architecture of AsterixDB. I worked to tackle this limitation.

* Decoupled the data intaking and data parsing in the data feed
* Made the data parsing parallel and optimize the efficiency of data ingestion 
* Designed comprehensive experiment settings to evaluate the improvement



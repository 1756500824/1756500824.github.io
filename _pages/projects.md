---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

{% include base_path %}

<br>

Improving Data Ingestion Performance in Apache AsterixDB
======

Supervisor: [Prof. Michael J. Carey](https://www.ics.uci.edu/~mjcarey/) & [Xikui Wang](https://www.linkedin.com/in/xikuiw/)                                    

Data is parsed using a single node since the data intaking module and the data parsing
module are coupled together in AsterixDB currently, which does not utilize the advantage
of distributed architecture of AsterixDB. I worked to tackle this limitation.

* Decoupled the data intaking and data parsing in the data feed
* Made the data parsing parallel and optimize the efficiency of data ingestion 
* Designed comprehensive experiment settings to evaluate the improvement

[Slides](https://1756500824.github.io/files/AsterixDBIngestion.pdf) [Slides2](https://1756500824.github.io/files/AsterixDBIngestion.pptx)

Discovering Top-k Newsworthy Facts from Multidimensional Dataset
======

Supervisor: [Prof. Bo Tang](https://acm.sustech.edu.cn/btang/)

The program serves to find intriguing facts through an efficient algorithm framework
and an insightful measurement.

* Implemented skyline, prominent streak and other operators
* Proposed a score function and non-trivial pruning techniques

Improving Maximum Inner Product Search by GPU
======

Supervisor: [Prof. Bo Tang](https://acm.sustech.edu.cn/btang/) & [Xiao Yan](https://scholar.google.com/citations?hl=zh-CN&user=rzNoyOIAAAAJ)

State-of-the-art of MIPS (maximum inner product search) is calculated by CPU based
on the graph index. We are trying to develop a GPU-based algorithm to solve MIPS.




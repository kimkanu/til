---
title: Maintaining Referential Integrity in Planetscale
tags:
    - database
    - referential integrity
    - data duplication
date: 2023-07-17T18:33:39.941Z
icon: database
---

Planetscale has no foreign key support, so to maintain referential integrity

* Use normalized forms to handle duplicates
* Then run cleanup scripts regularly to reclaim the space

## Link

* https://github.com/planetscale/discussion/discussions/74


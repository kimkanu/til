---
title: Maintaining Referential Integrity in Planetscale
tags:
    - database
    - referential integrity
    - data duplication
date: 2023-07-17T18:33:39.941Z
icon: other
---

Planetscale has no foreign key support, so to maintain referential integrity

* Don't be afraid to duplicate data
* Use `on delete no action`
* Then run cleanup scripts regularly to reclaim the space

## Link

* https://github.com/planetscale/discussion/discussions/74


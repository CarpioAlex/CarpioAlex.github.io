---
title: Drawing Directional Arcs like in Rhino
createdAt: 2023-10-11 10:18
lastmod: 2023-12-12 10:18
categories: [animal]
lang: en
permalink: /posts/directional_angle
pin: true
math: true
mermaid: true
---
# _Changes as of 2023/12/12_
> As of 2023/12/12, most of the implementation methods have been changed due to refactoring. The flowchart is still used.
{: .prompt-warning }

# 1. Understanding the Problem
There are cases where an arc needs to be drawn given three points C, P, Q (center point C and two reference lines CP, CQ).
​
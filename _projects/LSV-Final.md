---
title: "Range-Preserving Logic Relation Determinization"
excerpt: "An exploration of algorithms to achieve range-preserving determinization.<br/><img src='/images/LSV_final.png'>"
collection: projects
---
## Team Menber
**Sheng-Jung Yu** and Tung-Wei Lin

## Report Link
[PDF Report](https://YuTaiwan.github.io/files/LSV_report.pdf)
[PPT Slides](https://YuTaiwan.github.io/files/LSV_slides.pdf)

## Abstract

Boolean relations are more flexible in representation than boolean functions because of its non-determinism. 
However, circuits must be implemented by deterministic behaviors. 
Therefore, when creating circuits from boolean relations, the problem of determinizing boolean relations arises. Range-preserving determinization, which introduce additional variables to determinize relations while preserving all relation between orignal variables, is one way of such determinization.
In this work, we propose three methods to achieve range-preserving determinization, including Maximum Clique, MaxSAT and a unate-splitting methods.
We implemented all three mothods in programming language c++, as an extension function of [ABC](https://people.eecs.berkeley.edu/~alanmi/abc/) 
Experimental results show that the unate-splitting method are most efficient among the proposed methods.

![Example](https://YuTaiwan.github.io/images/LSV_final.png)
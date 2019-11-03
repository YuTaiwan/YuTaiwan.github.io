---
title: "Equivalent Capacitance Guided Dummy Fill Insertion"
collection: publications
permalink: /publication/2020-01-14-Dummy-Fill

date: 2020-01-14
venue: 'Asia and South Pacific Design Automation Conference'

citation: 'Sheng-Jung Yu, Chen-Chien Kao, Chia-Han Huang and Iris Hui-Ju Jiang. &quot;Equivalent Capacitance Guided Dummy Fill Insertion,&quot; <i>ASPDAC-20</i>.'
---

We designed and implemented an Equivalent Capacitance Guided Dummy Fill Insertion Engine to mitigate the timing impact caused by dummy fills
![Dummy Fill Insertion](https://YuTaiwan.github.io/images/Dummy_Fill_Layout.png "Result Layout")

To improve manufacturability, dummy fill insertion is widely adopted for reducing the thickness variation after chemical mechanical polishing.
However, inserted metal fills induce significant coupling to nearby signal nets, thus possibly incurring timing degradation.
Existing timing-aware fill insertion strategies focus on optimizing induced coupling capacitance instead of resultant equivalent capacitance.
Therefore, the impact on timing cannot be fully captured.
In contrast, in this paper, we analyze equivalent capacitance friendly regions for dummy fills.
The analysis can wisely guide dummy fill insertion to prevent unwanted and unnecessary increase in the resultant equivalent capacitance of timing critical nets. 
Experimental results based on the ICCAD 2018 CAD Contest benchmark suite show that our solution outperforms the contest winning teams and state-of-the-art work.
Moreover, our analysis results are highly correlated to actual equivalent capacitance values and indeed provide accurate guidance for timing-aware dummy fill insertion.

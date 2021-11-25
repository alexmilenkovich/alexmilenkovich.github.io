---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.com/citations?user=JNrVfvgAAAAJ&hl=en">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

2021
------
IEEE.TED'21 

ACM.TECS'21 Prawar Poudel, Biswajit Ray, Aleksandar Milenković, "Microcontroller Fingerprinting Using Partially Erased NOR Flash Memory Cells," ACM Transactions on Embedded Computing Systems, Vol. 20, No: 3, Article 26, March 2021, doi: 10.1145/3448271.

ACM.ICPE'21 Ranjan Hebbar, Aleksandar Milenkovic, "An Experimental Evaluation of Workload Driven DVFS," in the Companion Proceedings of the ACM/SPEC International Conference on Performance Engineering (ICPE'21), Virtual Event, France, April 19-23, 2021, ACM New York, NY, 8 pages. doi: https://doi.org/10.1145/3447545.3451192.

IEEE.SE'21 Ranjan Hebbar, Aleksandar Milenkovic, "A Preliminary Scalability Analysis of SPEC CPU2017 Benchmarks," in the Proceedings of the IEEE Southeast Con 2021, Virtual Event, March 11-14, 2021, 8 pages. doi: TBD.

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<p style="margin-bottom: 6px">
<li>
<span>
Jie Zhao and Peng Di. Optimizing the Memory Hierarchy by Compositing Automatic Transformations on Computations and Data.
<i>In the 53rd IEEE/ACM International Symposium on Microarchitecture (MICRO-53)</i>, Athens, Greece, 2020. (to be appeared)
</span></li>
</p>

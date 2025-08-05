---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Jiajie. I'm passionated about GenAI for real-world designs. Currently a Ph.D. candidate in Advanced Computer Science at Leiden University, leveraging a Mechanical Engineering background from Technische Universität Darmstadt to drive innovation in generative engineering design.

## Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<ul>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</ul>


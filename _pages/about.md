---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is Jiajie Fan.

## Publications

{% include base_path %}

<ul>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</ul>


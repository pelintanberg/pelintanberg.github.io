---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<hr>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign counter = 0 %}
{% for post in site.publications %}
  {% if post.firstauthor == "RCY" %}
    {% assign counter = counter | plus: 1 %}
  {% endif %}
{% endfor %}

**{{ site.publications | size }}** publications in peer-reviewed academic journals, with **{{ counter }}** published as first author.

<hr>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
  <hr>
{% endfor %}

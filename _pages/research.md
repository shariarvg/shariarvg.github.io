---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Welcome to my research page!

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  <p> {{ post.title }} </p>
  {% include archive-single.html %}
{% endfor %}

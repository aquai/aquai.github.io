---
layout: archive
title: "Publication List"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

你来到了知识的荒漠<br/>You are in a desert of knowledge

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

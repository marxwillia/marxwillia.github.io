---
layout: archive
title: "First Author Publications"
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

----------------------------------------------------

# Coauthored Publications

{% for post in site.coauthorpubs reversed %}
  {% include archive-single.html %}
{% endfor %}
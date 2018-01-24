---
layout: archive
title: "Research contributions"
permalink: /contributions/
author_profile: true
---

{% include base_path %}

This is the page for publications where my contribution was not crucial.

{% for post in site.contributions reversed %}
  {% include archive-single.html %}
{% endfor %}

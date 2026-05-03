---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
classes: wide
---

Currently not up-to-date; renewal incoming.
For now, please refer to the publication list in the CV tab.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

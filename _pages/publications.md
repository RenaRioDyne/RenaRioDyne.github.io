---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
classes: wide
---

{% include base_path %}

{% assign selected_pubs = site.publications | where: "selected", true | sort: "year" | reverse %}
{% assign conference_pubs = site.publications | where: "type", "conference" | sort: "year" | reverse %}
{% assign journal_pubs = site.publications | where: "type", "journal" | sort: "year" | reverse %}

!! still under construction !! this is not a full list of publications.

<small>
Click on each paper to see a detailed description. Select publications are marked
with a star.
</small>

{% if selected_pubs.size > 0 %}
## Selected Publications

<div class="pub-list pub-list--selected">
{% for pub in selected_pubs %}
  {% include default-publication-item.html pub=pub %}
{% endfor %}
</div>
{% endif %}


## Journal Papers

<div class="pub-list">
{% for pub in journal_pubs %}
  {% include journal-item.html pub=pub number=forloop.index prefix="J" %}
{% endfor %}
</div>

## Conference Papers

<div class="pub-list">
{% for pub in conference_pubs %}
  {% include conference-item.html pub=pub number=forloop.index %}
{% endfor %}
</div>

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
classes: wide
---

{% include base_path %}

{% assign selected_pubs = site.publications | where: "selected", true | sort: "date" | reverse %}
{% assign conference_pubs = site.publications | where: "type", "conference" | sort: "date" | reverse %}
{% assign journal_pubs = site.publications | where: "type", "journal" | sort: "date" | reverse %}

{% assign conference_count = conference_pubs | size %}
{% assign journal_count = journal_pubs | size %}

<small>
Click on each paper to see a detailed description. Selected publications are marked
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
  {% assign jour_number = journal_count | minus: forloop.index0 %}
  {% include journal-item.html pub=pub number=jour_number %}
{% endfor %}
</div>

## Conference Papers

<div class="pub-list">
{% for pub in conference_pubs %}
  {% assign conf_number = conference_count | minus: forloop.index0 %}
  {% include conference-item.html pub=pub number=conf_number %}
{% endfor %}
</div>

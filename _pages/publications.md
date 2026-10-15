---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

{% assign pubs = site.publications | sort: "date" | reverse %}
{% assign conference = pubs | where: "pubtype", "conference" %}
{% assign journal = pubs | where_exp: "p", "p.journal" %}

## Conference Papers

{% assign by_year = conference | group_by_exp: "p", "p.date | date: '%Y'" %}
{% for year in by_year %}
<h3 class="pub-year">{{ year.name }}</h3>
<ul class="pub-list">
{% for post in year.items %}{% include publication-item.html %}{% endfor %}
</ul>
{% endfor %}

## Journal Papers

<ul class="pub-list">
{% for post in journal %}{% include publication-item.html journal=true %}{% endfor %}
</ul>

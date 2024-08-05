---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
  - /md/
  - /publications.html
---

## Research Overview

## Publications

## Work in Progress

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{https://scholar.google.com/citations?user=8xC25vUAAAAJ}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

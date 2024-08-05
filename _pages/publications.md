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

### Peer-reviewed Articles

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{https://scholar.google.com/citations?user=8xC25vUAAAAJ}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Work in Progress

For more info
------
This is a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages.
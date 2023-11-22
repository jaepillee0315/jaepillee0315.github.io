---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<!---{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}--->

## Job Market Paper

## Work in Progress
{% for post in site.research %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

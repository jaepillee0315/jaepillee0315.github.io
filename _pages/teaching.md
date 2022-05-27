---
layout: archive
title: ""
permalink: /teaching/
author_profile: true
---

## Teaching Assistant

Professor Miller's [structural econometrics](https://comlabgames.com/structuraleconometrics/):
- [GMM: OLS and LIV](/structural-econometrics/1. GMM; OLS and LIV/GMM-OLS-and-IV.html)
- [GMM: Hansen and Singleton (1982)](/structural-econometrics/2. Hansen and Singleton/2_GMM.html)

## Additional Notes

{% for post in site.teaching %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

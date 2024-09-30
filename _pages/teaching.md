---
layout: archive
title: ""
permalink: /teaching/
author_profile: true
---

## Material for Structural Econometrics Lecture Series
[Structural Econometrics](https://comlabgames.com/structuraleconometrics/)
- [Bayesian Learning](/structural-econometrics/Bayesian%20Learning/Bayesian%20Learning.html)
- [GMM: OLS and LIV](/structural-econometrics/GMM%3B%20OLS%20and%20LIV/GMM-OLS-and-IV.html)
- [GMM: Hansen and Singleton (1982)](/structural-econometrics/Hansen%20and%20Singleton/GMM.html)

## Additional Notes
{% for post in site.teaching %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

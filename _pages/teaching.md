---
layout: archive
title: ""
permalink: /teaching/
author_profile: true
---

## Teaching Assistant
[Structural Econometrics](https://comlabgames.com/structuraleconometrics/)
- [Bayesian Learning](/structural-econometrics/Bayesian%20Learning/Bayesian%20Learning.ipynb)
- [GMM: OLS and LIV](/structural-econometrics/GMM; OLS and LIV/GMM-OLS-and-IV.html)
- [GMM: Hansen and Singleton (1982)](/structural-econometrics/Hansen and Singleton/GMM.html)

## Additional Notes
{% for post in site.teaching %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

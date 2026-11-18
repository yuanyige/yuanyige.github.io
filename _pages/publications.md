---
permalink: /publications/
title: ""
excerpt: ""
redirect_from:
  - /publications.html
---

## Publications

<p class="note">* equal contribution. <a href="/">Back to home</a></p>

{% assign years = site.data.publications | map: "year" | uniq %}
{% for y in years %}
<h3>{{ y }}</h3>

{% include pub-list.html year=y mode="details" %}
{% endfor %}

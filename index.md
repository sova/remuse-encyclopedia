---
layout: default
title: Home
---

# Remuse

Music encyclopedia and reviews.

{% for band in site.bands %}
- [{{ band.title }}]({{ site.baseurl }}{{ band.url }})
{% endfor %}
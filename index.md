---
layout: default
title: Home
---

Music encyclopedia, shows, reviews.

{% for band in site.bands %}
- [{{ band.title }}]({{ site.baseurl }}{{ band.url }})
{% endfor %}
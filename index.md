---
layout: default
title: Home
---

Click on a band to see the words I chose to describe their sound and songs.  Plus, other details about the bands like who is in them, and shows they are playing soon.

{% for band in site.bands %}
- [{{ band.title }}]({{ site.baseurl }}{{ band.url }})
{% endfor %}
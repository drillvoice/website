---
layout: page
title: Tags
permalink: /tags/
---

{% raw %}{% for tag in site.tags %}
- **{{ tag[0] }}** ({{ tag[1].size }})
{% endfor %}{% endraw %}

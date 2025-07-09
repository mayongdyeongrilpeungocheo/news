---
layout: default
title: Home
---

# Latest News

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url | relative_url }})
{{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

---

{% endfor %}

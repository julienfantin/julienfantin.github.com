---
layout: default
title: Blog
---

{% if site.posts != empty %}

{% for post in site.posts %}
   {{ post.date | date_to_string }} - [{{ post.title }}]({{ post.url }})
{% endfor %}

{% else %}

*Looks like I need to start blogging!*

{% endif %}

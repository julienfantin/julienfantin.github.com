---
layout: default
---

{% capture about %}
{% include about.md %}
{% endcapture %}

{{ about | markdownify }}

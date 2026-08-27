---
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
You can also find my articles on <u><a href={{"https://scholar.google.com/citations?user=tbK9jl4AAAAJ"}} target="_blank">my Google Scholar profile</a>.</u>
{% endif %}

{% for pub in site.publications %}
- {{ pub.citation }}
{% endfor %}

---
title: "Publications"
layout: page
permalink: /publications/
order: 3
---

# Publications

This is a test publications page.

{% for pub in site.data.publications %}
## {{ pub.title }}
**Authors:** {{ pub.authors | join: ", " }}  
**Venue:** {{ pub.venue }} ({{ pub.year }})  
**URL:** [{{ pub.url }}]({{ pub.url }})

---
{% endfor %}

---
title: Publications
permalink: /publications/
---

{% assign pubs = site.publications | sort: 'date' | reverse %}
{% for pub in pubs %}
  {% include publication-card.html pub=pub %}
{% endfor %}

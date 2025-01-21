---
title: "Publications"
permalink: /publications/
---

{% assign sorted_publications = site.data.publications | sort: "year" | reverse %}
{% for pub in sorted_publications %}
[{{ forloop.index }}] **{{ pub.title }}**  
{{ pub.authors | replace: "Yu Liu", "**Yu Liu**" }}.  
*{{ pub.publication }}*{% if pub.volume %}, {{ pub.volume }}{% endif %}{% if pub.issue %}({{ pub.issue }}){% endif %}{% if pub.pages %}, pp. {{ pub.pages }}{% endif %}, {{ pub.year }}.  
{% if pub.doi %}[DOI: {{ pub.doi }}](https://doi.org/{{ pub.doi }}){% endif %}

{% endfor %}


---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Selected Publications**

For a detailed list of my publications including citations count please visit my [Google Scholar](https://scholar.google.com.au/citations?user=61Ou1P8AAAAJ&hl=en) page.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

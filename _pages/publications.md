---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
 You can also find my articles on my [Scopus](https://www.scopus.com/authid/detail.uri?authorId=28767526200) or [Google Scholar](https://scholar.google.com/citations?user=rqSaUX8AAAAJ&hl=en) profiles.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

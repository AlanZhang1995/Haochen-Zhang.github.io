---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please find more publications on my [Google Scholar profile](https://scholar.google.com/citations?user=BOI3opEAAAAJ&hl=en)

---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

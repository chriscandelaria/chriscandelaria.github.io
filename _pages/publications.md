---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a style='color: darkblue;' href="https://scholar.google.com/citations?user=_325fyQAAAAJ&hl=en">Google Scholar</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: "archive"
title: ""
permalink: /publications/
author_profile: true
---
Journal Articles
==
{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Conference Papers**
{% include base_path %}
{% for post in site.publications.confPapers reversed%}
  {% include archive-single.html %}
{% endfor %}

Conference Abstracts
{% include base_path %}
{% for post in site.publications.confPapers reversed%}
  {% include archive-single.html %}
{% endfor %}

Academic Symposiums
==
{% include base_path %}
{% for post in site.publications.confPapers reversed%}
  {% include archive-single.html %}
{% endfor %}
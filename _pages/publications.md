---
layout: "archive"
title: ""
permalink: /publications/
author_profile: false
---
Journal Articles
==
{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Conference Papers
==
Test

{% include base_path %}
{% for post in site.publications.confPapers reversed%}
  {% include archive-single.html %}
{% endfor %}

Conference Abstracts
==


Academic Symposiums
==



{% include base_path %}
{% for post in site.publications.confPapers reversed%}
  {% include archive-single.html %}
{% endfor %}
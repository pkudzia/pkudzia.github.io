---
layout: archive
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
{% for post in site.conferencePapers reversed %}
  {% include archive-single.html %}
{% endfor %}

**Conference Abstracts**
{% include base_path %}
{% for post in site.conferenceAbstracts reversed %}
  {% include archive-single.html %}
{% endfor %}

**Symposiums*
{% include base_path %}
{% for post in site.symposiums reversed %}
  {% include archive-single.html %}
{% endfor %}



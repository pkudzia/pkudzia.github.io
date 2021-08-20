---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Journal Articles 
==
{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Conference
==
{% include base_path %}
{% for post in site.publications.conferenceAbstracts reversed %}
  {% include archive-single.html %}
{% endfor %}


<sup>*</sup> Equal authorship
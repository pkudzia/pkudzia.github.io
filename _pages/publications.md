---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

title: "Test"
collection: publications
permalink: /publication/2019-bayespostest
date: 2019-10-01
venue: 'Journal of Open Source Software'
paperurl: '/files/pdf/research/BayesPostEst.pdf'
link: 'https://doi.org/10.1177/07388942211015242'
code: 'https://journals.sagepub.com/doi/suppl/10.1177/07388942211015242'
github: 'https://github.com/jayrobwilliams/conflict-preemption'


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship
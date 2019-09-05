---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
You can find my complete publications on <u><a href="https://scholar.google.com/citations?user=gNshB_kAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</u>
<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}-->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

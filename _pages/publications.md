---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Working papers
---

{% capture nursing_homes_content %}
{% include _publications/Nursing_Homes.md %}
{% endcapture %}
{{ nursing_homes_content | markdownify }}

Publications
---

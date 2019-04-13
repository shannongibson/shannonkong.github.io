---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

# Manuscripts in preparation and under review: 
------

Berdica, E., Demić, E., <b> Gibson, S. P., </b> Sakelariev, I., Van Reyn, C., Većkalov, B., & Weinerová, J. (registered report under review.). Examining the utility of ADFES-BIV in adolescent samples across four European countries. 


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

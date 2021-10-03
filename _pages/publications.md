<!-- ---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
--- -->

---
permalink: /non-menu-page/
title: "Publications"
excerpt: "This is a page not in th emain menu"
author_profile: true
redirect_from: 
  - "/nmp/"
  - "/nmp.html"
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

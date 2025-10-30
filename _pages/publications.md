---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Publication

* Kai Wang, Michael Wen Tong, Jun Pang, Jitao Wang, Weili Han. XRAD: Ransomware Address Detection Method based on Bitcoin Transaction Relationships. ACM Transactions on the Web (TWEB), 2024.

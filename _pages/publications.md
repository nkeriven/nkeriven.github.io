---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

> **Thesis**: *Sketching for Large-Scale Learning of Mixture Models* [[Pdf]](https://tel.archives-ouvertes.fr/tel-01620815/){:target="_blank"}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% assign post = site.publications | first %}

{% if post %}
  {% include archive-single.html %}
{% endif %}

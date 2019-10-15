---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<h2>Journal Articles</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


<h2>Invited Revisions and Submitted Manuscripts </h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'submitted' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}



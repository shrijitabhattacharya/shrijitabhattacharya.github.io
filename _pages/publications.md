---
layout: archive
title: "Publications"
permalink: /publications/
---

{% include base_path %}

{% for post in site.publications %}
  <div class="publication">
    <strong>{{ post.title }}</strong><br>
    {{ post.venue }}, {{ post.date | date: "%Y" }}<br>
    <a href="{{ post.paperurl }}">[Paper]</a>
  </div>
{% endfor %}

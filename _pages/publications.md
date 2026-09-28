---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<p class="pub-legend"><i><b>Bold</b> = me; * = corresponding author.{% if site.author.googlescholar %} Full list on <a href="{{ site.author.googlescholar }}">Google Scholar</a>.{% endif %}</i></p>

<ul class="pub-list">
{% for pub in site.data.publications %}
  <li>
    <b>{{ pub.venue }} —</b> <i>{{ pub.title }}.</i> {{ pub.authors }}.{% if pub.note %} <b>{{ pub.note }}</b>{% endif %}{% if pub.paper %} <a href="{{ pub.paper }}">[paper]</a>{% endif %}{% if pub.code %} <a href="{{ pub.code }}">[code]</a>{% endif %}
  </li>
{% endfor %}
</ul>

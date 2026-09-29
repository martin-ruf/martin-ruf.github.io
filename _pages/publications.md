---
layout: academic
title: "Publications"
permalink: /publications/
page_class: publications
---

{% include base_path %}

{% if site.author.googlescholar %}
<p class="academic-scholar-note">You can also find my articles on <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</p>
{% endif %}

<div class="academic-publication-list">
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
</div>

---
layout: page
show_meta: false
title: "Afrique"
subheadline: "Il y en a beaucoup..."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/pays/afrique/"
---
<ul>
    {% for post in site.categories.countries.europe %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

---
layout: post
title: Categories
published: true
---



<ul>
    {% for category in site.categories %}
    <li class=""><h3 class=""><a href="{{ site.url }}/categories/{{ category | first }}">{{ category | first | replace: 'webdev', 'Web Development ' | replace: 'books', 'Book Reviews' }}</h3></a></li>
    {% endfor %}
</ul>

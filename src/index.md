---
title: title1
layout: 'index.njk'
---

fddf d dfd  d fd f df

<ul>
    {% for post in collections.posts -%}
        <li>
            <a href="{{ post.url }}">{{post.data.title}}</a>
        </li>
    {% endfor %}
</ul>

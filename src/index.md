---
title: Olha Holovina Blog
layout: 'index.njk'
---

<figure><img src="./img/o_h_logo.png" alt=""></figure>
<ul>
    {% for post in collections.posts -%}
        <li>
            <a href="{{ post.url }}">{{post.data.title}}</a>
        </li>
    {% endfor %}
</ul>

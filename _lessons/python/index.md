---
title: "Python"
collection: lessons
permalink: /lessons/python/
layout: single
author_profile: true
---


<ul> 
    {% assign lectures = site.lessons | where_exp:"l","l.path contains 'python/'" | sort: 'index' %} {% for l in lectures %} {% if l.url != page.url %} 
    <li>
        <a href="{{ l.url }}">{{ l.title }}</a>
    </li> {% endif %} {% endfor %} 
</ul>
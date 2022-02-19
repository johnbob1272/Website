---
layout: page
title: Computer Science
permalink: /compsci/
---

This Is Under Construction

Lessons:
<ul>
    {% for lesson in site.lessons %}
        {% if lesson.category == "compsci" %}
            <li><a href="{{ site.baseurl }}{{ lesson.url }}">{{ lesson.title }}</a></li>
        {% endif %}
    {% endfor %}
</ul>
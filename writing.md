---
layout: default
permalink: /writing/
---

# Blog post(s)
<ul class="posts">
    {% for post in site.posts %}
    <li>
        <span>{{ post.date | date: "%Y-%m-%d" }}</span> &raquo;
        <a
            href="{{ post.url }}"
            >{{ post.title }}</a
        >
    </li>
{% endfor %}
</ul>

# Microblog
Short thoughts to read in a minute.

<ul class="posts">
    {% for piece in site.micro %}
    <li>
        <span>{{ piece.date | date: "%Y-%m-%d" }}</span> &raquo;
        <a
            href="{{ piece.url }}"
            >{{ piece.title }}</a
        >
    </li>
    {% endfor %}
</ul>

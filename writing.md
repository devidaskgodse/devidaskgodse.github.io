---
layout: default
---

# Blog post(s)
<ul class="posts">
    {% for piece in site.post %}
    <li>
        <span>{{ piece.date | date: "%Y-%m-%d" }}</span> &raquo;
        <a
            href="{{ piece.url }}"
            >{{ piece.title }}</a
        >
    </li>
    {% endfor %}
</ul>

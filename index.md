---
layout: default
---

I'm Devidas K. Godse. I research on granular systems at [Department of Energy Science and Engineering](https://www.ese.iitb.ac.in/) at [IIT Bombay](http://www.iitb.ac.in/).


I enjoy exploring ideas and mental models. I am also interested in tools and technologies as they have potential to change the way we operate in the world.

I like to travel, trek and try new foods.

## Articles list
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

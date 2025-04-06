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

# List of projects I've worked/working on

- [LAT.jl](https://github.com/devidaskgodse/LAT.jl): A LAMMPS Data Analysis Tool written in Julia
- [Project Vivaan](https://www.solardecathlon.gov/past/build/2023/teams/indian-institute-of-technology-bombay) at [Team SHUNYA](https://www.teamshunya.com/): A sustainable housing solution that secured 2nd place in [Solar Decathlon Build Challenge 2023](https://www.solardecathlon.gov/past/build/2023/competition-scores)


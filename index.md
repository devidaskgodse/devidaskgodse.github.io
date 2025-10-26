---
layout: default
---

I research on granular systems at [IIT Bombay](http://www.iitb.ac.in/).

Current interests: complex systems, world as a hypergraph, and the impact of design and communication on psychology and technology.

You can connect with me at [LinkedIn](https://www.linkedin.com/in/devidaskgodse/).

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


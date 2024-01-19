---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
# About

Hello! I am Vincenzo De Maio, Ph.D. from the [HPC group](http://hpc.ec.tuwien.ac.at/) of [Vienna University of Technology](http://tuwien.ac.at), Institute of Information Systems Engineering. My supervisor is [prof. Ivona Brandic](https://informatics.tuwien.ac.at/people/ivona-brandic).

My research lies at the intersection between quantum computing and high-performance computing, with the ultimate goal of harnessing potential of quantum computers to address the increasing demands of future scientific applications. I am also interested in resource allocation for Cloud-Edge Computing, IoT infrastructures and Blockchain technologies.

If you want to know more about me, check out my short [Biography](/bio/). My publication list, with links to my Scholar, DBLP, and ORCID profile can be found [here](/publications/).

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.date }} - {{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

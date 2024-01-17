---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
# About

Hello! I am Vincenzo De Maio, Ph.D. from the Vienna University of Technology, Institute of Information Systems Engineering, HPC Group, and from University of Innsbruck, Department of Experimental Physics. My supervisor is prof. Ivona Brandic.

If you want to know more about me, check out my short [Biography](/bio/). My publication list, with links to my Scholar, DBLP, and ORCID profile can be found [here](/publications/).

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.date }} - {{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

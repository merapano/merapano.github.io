---
layout: default
---

[Home](index.html)

## Categories

{% for category in site.categories %}
<a href="{{ category[0] | prepend: "#" }}">{{ category[0] | prepend: " | "}}</a>{% endfor %}

-----

{% for category in site.categories %}
  <h3><a name="{{ category[0] }}" id="{{ category[0] }}">{{ category[0] }}</a></h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}



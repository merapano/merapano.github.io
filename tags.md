---
layout: default
---


## Tags

{% for tag in site.tags %}
<a href="{{ tag[0] | prepend: "#" }}">{{ tag[0] | prepend: " | "}}</a>{% endfor %}

-----

{% for tag in site.tags %}
  <h3><a name="{{ tag[0] }}" id="{{ tag[0] }}">{{ tag[0] }}</a></h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% endfor %}

<!--

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

-->




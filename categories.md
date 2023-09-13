---
layout: default
---

# Categories

{% for category in site.categories %}
<a href="{{ category[0] | prepend: "#" }}">{{ category[0] | prepend: " | "}}</a>{% endfor %}

-----

{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}



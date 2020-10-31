---
layout: default
---
<!-- -*- coding: utf-8 -*- -->


# List of all the entries

<ul>
  {% for post in site.posts  %}
      <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
{% endfor %}
 </ul>


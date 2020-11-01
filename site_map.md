---
layout: default
---
<!-- -*- coding: utf-8 -*- -->


# Blog

## Daily entries

<ul>
  {% for post in site.posts limit:10 %}
      <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
{% endfor %}
 </ul>

[More?](./blog-list.html)


## 抜粋つき

<ul>
  {% for post in site.posts limit: 10  %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

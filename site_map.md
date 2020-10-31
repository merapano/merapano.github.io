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

## Tags

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

## 抜粋つき

<ul>
  {% for post in site.posts limit: 10  %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

# Pages

- [Link to another page](./another-page.html).
- [Leap-day manual](./leap-day.html)

# Project github pages

- [Sex and Gender](./sex_and_gender/)
- [Environmentalism](./environment/)


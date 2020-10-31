---
layout: default
---
<!-- -*- coding: utf-8 -*- -->


# Blog

<ul>
  {% for post in site.posts limit:10 %}
      <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
{% endfor %}
 </ul>

[More?](./blog-list.html)

# Pages

- [Link to another page](./another-page.html).
- [Leap-day manual](./leap-day.html)

# Project github pages

- [Sex and Gender](./sex_and_gender/)
- [Environmentalism](./environment/)


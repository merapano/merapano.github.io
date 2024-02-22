---
layout: default
---

# List of all the entries


以下ブログをすべて紹介します。

<ul>
  {% for post in site.posts %}
      <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
{% endfor %}
 </ul>

<!--

<ul>
  {% for post in site.posts limit: 20 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
      <hr />
    </li>
  {% endfor %}
</ul>

-->



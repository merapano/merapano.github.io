---
<!-- -*- coding: utf-8 -*- -->
layout: default
---

# はじめに

なかがわ・さとしです。
人類学者です。
インドネシアのフローレス島で1979年から
フィールドワークを続けています。

[オーストラリア国立大学](www.anu.edu.au)
の卒業生です。
[大阪国際大学](https://www.oiu.ac.jp/)その他で
教えていました。
ただいま無職2年目です。

[古いサイト](http://www.merapano.net/~satoshi/private/diary) 
からこちらへの移行作業中です。
2020年度中には完全に移行したいと思っています。

# このサイト

[jekyll](https://jekyllrb.com/) をつかって
[github](http://jekyllrb-ja.github.io/) の上に 
作っています。

# ブログ

## 最新のブログ

<ul>
  {% for post in site.posts limit:5 %}
      <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
{% endfor %}
 </ul>

もっと見ければ、[ここをクリック](./blog-list.html) 。

# カテゴリー、タグ

[カテゴリー別](./categories.html)
あるいは[タグ別](./tags.html) でブログの
エントリーを眺めることもできます。

# 人類学


- [Sex and Gender](./sex_and_gender/)
- [Environmentalism](./environment/)

# Pages

- [Link to another page](./another-page.html).
- [Leap-day manual](./leap-day.html)


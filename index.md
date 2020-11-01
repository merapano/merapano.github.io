---
layout: default
---
<!-- -*- coding: utf-8 -*- -->

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

[古いサイト]l(http://www.merapano.net/~satoshi/private/diary) 
からこちらへの移行作業中です。
2020年度中には完全に移行したいと思っています。

# このサイト

[jekyll](https://jekyllrb.com/) をつかって
[github](http://jekyllrb-ja.github.io/) の上に 
作っています。


# サイトの内容

サイトマップは `site_map` にあります ---
[ここ](./site_map.html)をクリックしてください。

# ブログ

## 最新のブログ

<ul>
  {% for post in site.posts limit:10 %}
      <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
{% endfor %}
 </ul>

[もっと見たい?](./blog-list.html)

# カテゴリー、タグ

カテゴリーあるいはタグ毎に見たければ
[ここ](tags.html) をクリックしてください。

# 人類学


- [Sex and Gender](./sex_and_gender/)
- [Environmentalism](./environment/)

# Pages

- [Link to another page](./another-page.html).
- [Leap-day manual](./leap-day.html)


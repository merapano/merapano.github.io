---
title: 残日録 --- The Remains of the day
layout: default
---

## はじめに

なかがわ・さとしです。
人類学者です。
ただいま無職2年目です。
より詳しい自己紹介は
[ここをクリックしてください](aboutme.html)。

## 人類学

- [Sex and Gender](./sex_and_gender/)
- [Naturalism](./naturalism/) （まもなく公開）
- [エンデに向けて](./towards_ende/) 
- [人類学でコンピューターをつかう](computer_and_anthropology/)

## ブログ

- [カテゴリー](categories.html)
- [タグ](tags.html)
- [全エントリー](blog-list)

### 最新のブログ

以下抜粋（最初の一段落）つきです。

<ul>
  {% for post in site.posts limit: 5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

もっと見たければ、[ここをクリック](./blog-list.html) 。

### カテゴリー、タグ

[カテゴリー別](./categories.html)
あるいは[タグ別](./tags.html) でブログの
エントリーを眺めることもできます。

## テクニカルなおまけ

このサイトは、
[jekyll](https://jekyllrb.com/) をつかって
[github](http://jekyllrb-ja.github.io/) の上に 
作っています。
[古いサイト](http://www.merapano.net/~satoshi/private/diary) 
からこちらへの移行作業中です。
2020年度中には完全に移行したいと思っています。

Leap-Day のテーマを
使用しています。
[Leap-day manual](./leap-day.html) 



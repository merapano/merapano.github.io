---
title: 残日録 --- The Remains of the day
author: "Satoshi Nakagawa"
layout: default
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-F5QJMGG75W"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-F5QJMGG75W');
</script>


# はじめに

なかがわ・さとしです。
人類学者です。
ただいま無職5年目です。
より詳しい自己紹介は
[ここをクリックしてください](aboutme.md)。

[RSS](feed.xml)


# 人類学

人類学関連のディレクトリ、ファイルのインデックスは
[ここ](anthrop-index.md) にあります。

- [ユーチューブ](./youtube-index.html)作品集
<!-- - [なかがわさとし論文集（その1）：民族誌篇](./paper-0-md/) -->
- [timor-wiki](./timor-wiki/) ティモール島についての Wiki

## Github Project Pages

わたしはすべての作品
（論文、授業ノーツなど）
を Github で管理しています。
そのうちに一つづつ公開していく予定です。
まずは、
人類学で Linux、git、github などを使う方法を
示します。

- [人類学でコンピューターをつかう](computer_and_anthropology/README.html)

Github の人類学関連のリポジトリはほとんどが
プライベートです。
とりあえず非常に古いリポジトリを公開しましたので、
github pages (project) を以下に示します。

<！-- - [エンデに向けて](./ende/README.html) -->
- [Sex and Gender (EPUB)](./sex_and_gender/00BOOK.epub)
  + HTML 版は 
  [こちら](http://www.merapano.net/~satoshi/anthrop/class-md/sex_and_gender/)

## 最新のブログ

<!-- 以下抜粋（最初の一段落）つきです。-->

<ul>
  {% for post in site.posts limit: 20 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
<!--      {{ post.excerpt }} -->
    <hr />
    </li>
  {% endfor %}
</ul>

もっと見たければ、[ここをクリック](./blog-list.html) 。

## Blog

- [全エントリー](blog-list)
- [カテゴリー](categories.html)
- [タグ](tags.html)


# テクニカルなおまけ

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



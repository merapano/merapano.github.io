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

[RSS](feed.xml)

# はじめに

なかがわ・さとしです。
以下、名刺にかいた「肩書」です。

- ***Independent Researcher***
  + こないだ会ったインドネシア人の研究者（退職されています）がつかっていた
    ことばです。
    とてもかっこいいなと思って、
    ぼくも使うことにしました
  + ちなみに次の ***gelandangan*** も彼が
    使っていた自称です。
- ***Gelandangan*** （グランダンガン）
  + インドネシア語で、「ホームレス」の意味です。
    サッカーでは「ミッドフィールダー」の意味です。
  「ダンドゥットの王」と呼ばれるロマ・イラマ (Rhoma Irama) が 1975年に
  「グランダンガン (gelandangan)」という歌を
  [歌っています](https://www.youtube.com/watch?v=YiPbCAiPzcs)。
- ***Bee Toro Mobha*** （ベー・トロ・モッバ）
  + エンデの言葉（正確にはンガオ語）で「あっちこちうろうろする奴」という
    意味です。
  + 日本に住んでいたり、オーストラリアに住んでいたり、
    ジャカルタに住んでいたりしたので・・・。
  + フィールドでつけてもらった名前です。
- ***破落戸*** （ごろつき）
  + 折口信夫の[「ごろつきの話」](https://www.aozora.gr.jp/cards/000933/files/18408_27478.html)
    をご参照ください。

人類学者です。
ただいま無職5年目です。
より詳しい自己紹介は
[ここをクリックしてください](aboutme.md)。


# 人類学

## Github Project Pages

わたしはすべての作品
（論文、授業ノーツなど）
を Github で管理しています。
そのうちに一つづつ公開していく予定です。

<!--

まずは、
人類学で Linux、git、github などを使う方法を
示します。

- [人類学でコンピューターをつかう](computer_and_anthropology/README.html)

Github の人類学関連のリポジトリはほとんどが
プライベートです。
とりあえず非常に古いリポジトリを公開しましたので、
github pages (project) を以下に示します。

<!--  [エンデに向けて](./ende/README.html) 
- [Sex and Gender (EPUB)](./sex_and_gender/00BOOK.epub)
  + HTML 版は 
  [こちら](http://www.merapano.net/~satoshi/anthrop/class-md/sex_and_gender/)
  (クリックで www.merapano.net/ に移動します) 

-->

<!--
- [環境主義と人類学 (EPUB)](environment/00BOOK.epub)
  + HTML 版は 
  [こちら](http://www.merapano.net/~satoshi/anthrop/class-md/environment/)
  (クリックで www.merapano.net/ に移動します) 
-->

人類学関連のディレクトリ、ファイルのインデックスは
[ここ](anthrop-index.md) にあります。


## Youtube

ユーチューブにこれまでにいくつか Zoom による講演の
録画をアップしました。
以下をみてください。

- [ユーチューブ](./youtube-index.md)作品集
<!-- - [なかがわさとし論文集（その1）：民族誌篇](./paper-0-md/) -->
<!-- - [timor-wiki](./timor-wiki/) ティモール島についての Wiki -->

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



# 2019-08-24

これまでつくってきた授業のノートを
github で公開することを考えている。

gitbook をつかってみよう。

とりあえず sex_and_gender というプロジェクトを
つくった。
これでいろいろ実験する。
うまくいったら、
いろいろと発展させていこう。


# 2019-06-25

これは
ぼく [[(merapano]] の github につくった
page です。
やはり
`skk` では markdown-mode
はだめだ。

二日目の
記入。

どうすれば
リンクをはれるのかな
ふつうの markdown ならば
[pages](pages.html) となる。
これはめんどうくさい。
[pages](pages)はどうなのだろう。

この記法 (``[['' ``]]'') はどうやら
WikiLink と呼ばれ、
multimarkdown にとりいれられているようだ。
しかし、
github pages では
multimarkdown は
（あるいは WikiLink は）
サポートされていないようだ。

jekyll が multimarkdonw を
markdown にトランスレートしてくれると
一番よいのだが、
それはできないようだ。

# 2019-06-24

これは
ぼく [[merapano]] が
github につくった
[[pages]] です。

## さぁて・・・

コメントは（いまのところ）


     (defun my--markdown-entery-key-ad 
	     (this-func &rest args)
       "markdown-modeでskk-henkan-mode中\
	   にエンターすると行頭にカーソルが飛んでしまう問題の対応"
       (if skk-henkan-mode (skk-kakutei)
        (apply this-func args)))
     (advice-add #'markdown-enter-key 
	   :around #'my--markdown-entery-key-ad)

## その次

２つの大括弧でくくると
すぐにリンクができるのは
ikiwiki の仕様かな。


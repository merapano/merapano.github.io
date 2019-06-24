# 2019-06-24

これは
ぼく [[merapano]] が
github につくった
page です。

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

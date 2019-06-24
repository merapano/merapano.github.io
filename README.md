# 2019-06-24

これは
ぼく [[merapano]] 
 github につくった
page です。
やはり
`[[skk]]` では [[markdown-mode]]
はだめだ。

ここに直接書くこともできるんだぁ。

## さぁて・・・

コメントは（いまのところ）


     (defun my--markdown-entery-key-ad 
	     (this-func &rest args)
       "markdown-modeでskk-henkan-mode中にエンターすると行頭にカーソルが飛んでしまう問題の対応"
       (if skk-henkan-mode (skk-kakutei)
        (apply this-func args)))
     (advice-add #'markdown-enter-key 
	   :around #'my--markdown-entery-key-ad)


## 

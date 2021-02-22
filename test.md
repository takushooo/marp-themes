---
marp: true
theme: test
header: 'header text'
footer: 'footer text @takushooo'
size: 4:3
page_number: true
paginate: true
---
<!--
class: title
-->


# Marp for VS Code sample

***@takushooo***

---
<!--
class: slides
-->

## もくじ

1. Marp for VS Codeとは
2. 使い方
3. 連携拡張機能
4. 書式テンプレート

---

<!--
_backgroundColor: black
_color: white
_footer: 'Photo by Michal Vasko　on Unsplash'
-->

## 1. Marp for VS Codeとは

- VS Codeの拡張機能
  VS Code上でマークダウンからスライドが作れる

---

## h2. 使い方
1. リスト
2. 背景画像

# h1 クソださグラデーション
## h2
### h3
#### h4
##### h5
###### h6

---

## 3. 連携拡張機能
<!--

-->
+ vscode-reveal
    + vscode上への資料投影
+ Presentation Mode
    + vscodeをプレゼンテーション用に全画面に表示

---
<!--
_class: slides_center
-->
## 4. 書式テンプレート
画像の貼り方

---
<!--
bgで画像を背景に設定
-->
背景
![bg](https://placehold.jp/400x400.png)

---
<!--
bgで画像を背景に設定し、fitで画像のサイズを自動調整
-->
fit背景
![bg fit](https://placehold.jp/400x400.png)

---
<!--
rightで右寄せ
-->
右寄せ
![bg right](https://placehold.jp/400x400.png)

---
<!--
leftで左寄せ
-->
左寄せ
![bg left](https://placehold.jp/400x400.png)

---
<!--
画像を縦に並べる
-->
縦並び
![bg fit vertical right](https://placehold.jp/400x400.png)
![bg fit vertical right](https://placehold.jp/400x400.png)

---
<!--
画像を横に2枚並べたい時
-->
横並び
![](https://placehold.jp/400x400.png) ![](https://placehold.jp/400x400.png)

---
<!--
画像のサイズを%で指定。透明度も設定
-->
すけすけ
![bg 40% opacity:.5](https://placehold.jp/400x400.png)

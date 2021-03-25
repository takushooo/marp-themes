---
marp: true
theme: watalab
header: 'header'
footer: 'watalab-themes @2021/03/03'
size: 4:3
page_number: true
paginate: true
---

<style>
section::after {
  color: black;
}
</style>

<!--
class: title
-->


# Marp-theme for watalab

***@takushooo***

---
<!--
class: slides
-->

# h1
## h2
### h3
#### h4
##### h5
###### h6

---
<!--
_class: slides_center
footer: https://placehold.jp/400x400.png
-->
画像の貼り方

---
<!--
bgで画像を背景に設定
-->
背景
![bg](./marp-themes/pic/icon.jpg)

---
<!--
bgで画像を背景に設定し、fitで画像のサイズを自動調整
-->
fit背景
![bg fit](./marp-themes/pic/icon.jpg)

---
<!--
rightで右寄せ
-->
右寄せ
![bg right](./marp-themes/pic/icon.jpg)

---
<!--
leftで左寄せ
-->
左寄せ
![bg left](./marp-themes/pic/icon.jpg)

---
<!--
画像を縦に並べる
-->
縦並び
![bg fit vertical right](./marp-themes/pic/icon.jpg)
![bg fit vertical right](./marp-themes/pic/icon.jpg)
![bg fit vertical right](./marp-themes/pic/icon.jpg)

---
<!--
画像を横に2枚並べたい時
-->
横並び
![](./marp-themes/pic/icon.jpg) ![](./marp-themes/pic/icon.jpg)

---
<!--
画像のサイズを%で指定。透明度も設定
-->
すけすけ
![bg 40% opacity:.5](./marp-themes/pic/icon.jpg)

---
<!--
空白
-->
&nbsp;　通常の半角スペースと同じサイズの空白
&ensp;　半角スペースより少し広めの空白
&emsp;　半角スペースよりさらに広めの空白　全角スペースとほぼ同じ幅
&thinsp;　&nbsp;`より狭い空白

---
<!--
そのまま表示，改行
-->

<pre># 囲った部分をそのまま表示できる</pre>

改<br>行
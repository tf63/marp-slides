---
# 全スライドの設定
marp: true
# theme -> default, gaia, uncoverなど
theme: lab
# sizeはthemeで宣言する必要がある
size: 16:9
# ページ番号を表示
paginate: true
# h1 ~ 3で改ページ
headingDivider: 3
# header, footer
header: ""
footer: "yyyy/mm/dd"
math: katex
---

# title
<!-- class: title -->
<!-- header: "" -->
<br/>

<span>subtitle</span>

<br/>

大学大学院 学府
研究室 g

name

### text
<!-- class: normal -->
<!-- header: "header" -->
- abcd efgh ijkl mnop qlst uvwx yz
- `This is highlighted sentence`
- **bold** ~~delete~~ _italic_

p tag 

- indent 1

    - indent 2

        - indent 3

↑ 1行開けるとpタグが適用される

### list

- item 1
- item 2
- item 3

1. number 1
2. number 2
3. number 3

### img

![Alt text](img/lab-theme.png)


### blockquote
- google$^{[1]}$
- yahoo$^{[2]}$

> [1] https://google.com, [2] https://yahoo.co.jp


### math

インライン数式 $f(x) = x^2$, $\int_a^b f(x) dx$

$$ 
\text {d} x = f(t) x \text {d}t + g(t) \text {d}w 
$$
$$ 
F(\omega ) = \frac 1 {\sqrt {2\pi} }\int_{-\infty}^\infty f(t) e^{-j\omega t}dt
$$
$$
\bm a = 
    \begin{pmatrix}
        a_1\\
        a_2
    \end{pmatrix}
, \quad

A = 
\begin{pmatrix}
   a & b \\
   c & d
\end{pmatrix}
\quad
x = \begin{cases}
   a &\text{if } b \\
   c &\text{if } d
\end{cases}
$$

### two columns
<div class="two">
    <div class="left">
        <p><b>左カラム</b></p>
        <p>左カラムのコンテンツがここに入ります。</p>
        <img src="img/lab-theme.png" width=200px style="padding: 25px;"><img src="img/lab-theme.png" width=200px style="padding: 25px;">
    </div>
    <div class="right">
        <p><b>右カラム</b></p>
        <p>右カラムのコンテンツがここに入ります。</p>
    </div>
</div>

### two columns
<br />
<br />

<div class="two">
<div class="left">

$$
    \text d \bm x = f (\bm x, t) dt + g(t) \text d \bm w
$$

<br>

$$
    \text d \bm x = - \frac 1 2 \beta(t) \bm x \text d t + \sqrt{\beta(t)} \text d \bm w
$$

</div>
<div class="right">

$$
    f(\bm x, t) = - \frac 1 2 \beta (t) \bm x
$$

$$
    g(t) = \sqrt{\beta(t)}
$$

</div>
</div>

### code
```
# this is comment
def main():
    pass

if __name__ == "__main__":
    main()

```

### table

|11|00|00|
|:----|:----:|----:|
|r1|r1|r1|
|r2|r2|r2|
|r3|r3|r3|
|r4|r4|r4|
|r5|r5|r5|
|r6|r6|r6|
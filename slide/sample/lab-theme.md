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

### blockquote
- google$^{[1]}$
- yahoo$^{[2]}$

> [1] https://google.com, [2] https://yahoo.co.jp


### invert
<!-- class: invert -->


### math

$\int_a^b f(x) dx$

$$ 
\text {d} x = f(t) x \text {d}t + g(t) \text {d}w 
$$
$$ 
\text {d} x = f(t) x \text {d}t + g(t) \text {d}w 
$$
$$ 
\text {d} x = f(t) x \text {d}t + g(t) \text {d}w 
$$
$$ 
\text {d} x = f(t) x \text {d}t + g(t) \text {d}w 
$$
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
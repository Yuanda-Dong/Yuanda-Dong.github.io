+++
title = "Writing Hugo blog in Org (File Export)"
date = 2017-09-10
lastmod = 2023-03-23T01:11:59+11:00
tags = ["hugo", "org", "preview"]
categories = ["category-2", "category-3"]
draft = false
weight = 10
mathjax = true
author = "me"
autoCollapseToc = false
hiddenFromHomePage = false
+++

> Based on [MarkdownPreview test.md](<https://github.com/facelessuser/MarkdownPreview/blob/master/examples/test.md>).


## Markdown {#markdown}


## H1 {#h1}


### H2 {#h2}


#### H3 {#h3}


#### Duplicate header {#duplicate-header}


#### Duplicate header {#duplicate-header}


## Org Babel {#org-babel}

<style>.org-center { margin-left: auto; margin-right: auto; text-align: center; }</style>

<div class="org-center">

Center

</div>

```text
example
```

```python
print('hello')
print('byebye world')
return 2
```

```text
2
```

```emacs-lisp
(+ 1 1)
```

> "This is a quote"

```cpp
auto x = std::vector()
```


## Anchor {#anchor}

_Define anchor by heading name_.

[Org Babel](#org-babel)


## Foot {#foot}

The Org website[^fn:1] now looks a lot better than it used to.
test[^fn:2]
...


## Text formatting {#text-formatting}

**Bold**

_italic_

<span class="underline">underline</span>

`verbatim`

~~strike-through~~


## Links {#links}

{{< figure src="/ox-hugo/swappy-20230220-054538.png" caption="<span class=\"figure-number\">Figure 1: </span>This is the caption for the next figure link (or table)" width="300px" >}}

Web image
![Web Picture](https://count.getloli.com/get/@even-preview?theme=konachan "Web Picture")

[Google](https://www.google.com)

This is a link <https://github.com/revolunet/sublimetext-markdown-preview/>.


## list {#list}


### List 1 {#list-1}

-   Item 1
-   Item 2
-   Item 3
    -   Item 3.1
        -   Item 3.1.1
        -   Item 3.1.2
    -   Item 3.2
-   Item 4


### List 2 {#list-2}

-   222
-   333

<!--listend-->

1.  Item 1
2.  Item 2
3.  Item 3


### taskLists {#tasklists}

-   [-] Task1
    1.  [ ] task1.1
    2.  [X] task1.2


## quotes {#quotes}

> This is a block quote
>> How does it look?


## Table {#table}

| Colors  | Fruits  | Vegetable |
|---------|---------|-----------|
| Red     | Apple   | Pepper    |
| Oranges | Oranges | Carrot    |
| green   | Pear    | Spinach   |


## Smarty {#smarty}

"double quotes"

'single quotes'

da--sh

elipsis...


## Emoji {#emoji}

😀🍉


## mathjax {#mathjax}

\\[ evidence\_{i}=sum\_{j}W\_{ij}x\_{j}+b\_{i} \\]

\\[p(x|y) = \frac{p(y|x)p(x)}{p(y)} p(x|y) = \frac{p(y|x)p(x)}{p(y)}\\]

\\[ E(\mathbf{v}, \mathbf{h}) = -\sum\_{i,j}w\_{ij}v\_i h\_j - \sum\_i b\_i v\_i - \sum\_j c\_j h\_j \\]

\\[3 < 4\\]
\\[
{\begin{align}
    p(v\_i=1|\mathbf{h}) & = \sigma\left(\sum\_j w\_{ij}h\_j + b\_i\right) \\\\
    p(h\_j=1|\mathbf{v}) & = \sigma\left(\sum\_i w\_{ij}v\_i + c\_j\right)
\end{align}}
\\]

\\[
{\begin{align}
  \dot{x} & = \sigma(y-x) \newline
  \dot{y} & = \rho x - y - xz \newline
  \dot{z} & = -\beta z + xy
  \end{align}}
\\]

\begin{equation}
C = W\log\_{2} (1+\mathrm{SNR})
\end{equation}


## 网易云音乐 {#网易云音乐}

{{% music "28196554" %}}


## Youtube {#youtube}

{{% youtube "wC5pJm8RAu4" %}}

[^fn:1]: The link is: <https://orgmode.org>
[^fn:2]: spam

[//]: # "Exported with love from a post written in Org mode"
[//]: # "- https://github.com/kaushalmodi/ox-hugo"
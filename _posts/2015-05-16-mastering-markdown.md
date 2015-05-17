---
layout: page
title: mastering-markdown
description: 该页面为markdown的样例测试页面，请参考源码和最终生成的html代码
---

## Reference
[mastering-markdown](https://guides.github.com/features/mastering-markdown/)

[kramdown syntax](http://kramdown.gettalong.org/syntax.html)

<http://spec.commonmark.org>

## Syntax guide

### Headers
---
# This is an <h1> tag

## This is an <h2> tag

###### This is an <h6> tag


<hr>

### Emphasis
---
*This text will be italic*

_This will also be italic_


**This text will be bold**

__This will also be bold__

*You **can** combine them*


### Lists
---

#### Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b

#### Ordered
1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

### Images
---
![GitHub Logo](/assets/images/yaktocat.png)
Format: ![Alt Text](https://octodex.github.com/images/yaktocat.png)

### Links
---
Information can be found on the <http://example.com> homepage.
You can also mail me: <me.example@example.com>

[GitHub](http://github.com)

### Blockquotes
---
> Hello World, This is block quotes

---
> This is a blockquote.
---
> on multiple lines
that may be lazy.

> > A nested blockquote.


###Inline code
---
I think you should use an
`<addr>` element here instead.


### Code Blocks
---

common usage (indent your code by four spaces)

    function test() {
      console.log("notice the blank line before this function?");
    }

for kramdown (without syntax highlight)

~~~js
function test() {
  console.log("notice the blank line before this function?");
}
~~~

for kramdown (with syntax highlight)

{% highlight js %}
function test() {
  console.log("notice the blank line before this function?");
}
{% endhighlight %}

Nested code blocks

~~~~~~~~~
~~~~~~~
code with tildes
~~~~~~~~
~~~~~~~~~~~~~~~~

### Task Lists
---
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

### Tables
---

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column



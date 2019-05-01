---
title: 'Markdown Examples'
date: 2019-05-01T11:00:10-04:00
draft: false
tags: ['blog', 'markdown']
summary: 'A set of example markdown for display'
---

### This page shows examples of Markdown

Used mostly as a reference for me when creating blog posts

<p class="divder"></p>

## Headers

{{< markdown-blocks tabID="headers" >}}

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

##### Header 6

{{< /markdown-blocks >}}

<p class="divder"></p>

## Typography

{{< markdown-blocks tabID="typography" >}}
Emphasis, aka italics, with _asterisks_ or _underscores_.

Strong emphasis, aka bold, with **asterisks** or **underscores**.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
{{< /markdown-blocks >}}

<p class="divder"></p>

## Lists

{{< markdown-blocks tabID="lists" >}}

**Ordered list**

1. item 1
1. item 2
    1. sub-item a
    1. sub-item b
1. item 3 with paragraph

    Just have it indent to see nice
    indentations

    And just add blank line for continuation

1. Last item

**Unordered list**

-   first
-   second
-   third

{{< /markdown-blocks >}}

<p class="divder"></p>

## Links

{{< markdown-blocks tabID="links" >}}
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or <http://www.example.com>

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

{{< /markdown-blocks >}}

<p class="divder"></p>

## Images

{{< markdown-blocks tabID="images" >}}

Here's our logo (hover to see the title text):

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png 'Logo Title Text 1')

Reference-style:
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png 'Logo Title Text 2'

{{< /markdown-blocks >}}

<p class="divder"></p>

## Code Blocks

{{< markdown-blocks tabID="codeblocks" >}}

```javascript
var s = 'JavaScript syntax highlighting'
alert(s)
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

{{< /markdown-blocks >}}

<p class="divder"></p>

## Tables

{{< markdown-blocks tabID="tables" >}}

Colons can be used to align columns.

| Tables            |      Are      |   Cool |
| ----------------- | :-----------: | -----: |
| col 3 is          | right-aligned | \$1600 |
| col 2 is          |   centered    |   \$12 |
| zebra stripes.... |   are neat    |    \$1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

| Markdown | Less      | Pretty     |
| -------- | --------- | ---------- |
| _Still_  | `renders` | **nicely** |
| 1        | 2         | 3          |

{{< /markdown-blocks >}}

<p class="divder"></p>

## BlockQuotes

{{< markdown-blocks tabID="blockquotes" >}}

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_ **Markdown** into a blockquote.

{{< /markdown-blocks >}}

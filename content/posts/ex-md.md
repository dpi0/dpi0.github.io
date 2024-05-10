+++
author = "Hugo Authors"
title = "markdown syntax guide"
date = "2024-05-05"
description = "Sample article showcasing basic Markdown syntax and formatting for HTML elements."
tags = [
    "dev"
]
categories = [
    "themes",
    "syntax",
]
series = ["Themes Guide"]
aliases = ["migrate-from-jekyl"]
+++

this article offers a sample of basic markdown syntax that can be used in hugo content files, also it shows whether basic html elements are decorated with css in a hugo theme.

## headings

the following html `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

# h1
## h2
### h3
#### h4
##### h5
###### h6

## paragraph

xerum, quo qui aut unt expliquam qui dolut labo. aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? quiatem. nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

itatur? quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## blockquotes

the blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

#### blockquote without attribution

> tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **note** that you can use *markdown syntax* within a blockquote.

#### blockquote with attribution

> don't communicate by sharing memory, share memory by communicating.</p>
> — <cite>rob pike[^1]</cite>


[^1]: the above quote is excerpted from rob pike's [talk](https://www.youtube.com/watch?v=paakcszug1c) during gopherfest, november 18, 2015.

## tables

tables aren't part of the core markdown spec, but hugo supports supports them out-of-the-box.

   name | age
--------|------
    bob | 27
  alice | 23

#### inline markdown within tables

| inline&nbsp;&nbsp;&nbsp;     | markdown&nbsp;&nbsp;&nbsp;  | in&nbsp;&nbsp;&nbsp;                | table      |
| ---------- | --------- | ----------------- | ---------- |
| *italics*  | **bold**  | ~~strikethrough~~&nbsp;&nbsp;&nbsp; | `code`     |

## code blocks

#### code block with backticks

```
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```
#### Code block indented with four spaces

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

#### Code block with Hugo's internal highlight shortcode
{{< highlight html >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

## list types

#### ordered list

1. first item
2. second item
3. third item

#### unordered list

* list item
* another item
* and another item

#### nested list

* item
1. first sub-item
2. second sub-item

## other elements — abbr, sub, sup, kbd, mark

<abbr title="graphics interchange format">gif</abbr> is a bitmap image format.

h<sub>2</sub>o

x<sup>n</sup> + y<sup>n</sup> = z<sup>n</sup>

press <kbd><kbd>ctrl</kbd>+<kbd>alt</kbd>+<kbd>delete</kbd></kbd> to end the session.

most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.


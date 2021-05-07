---
title: "Markdown Style"
date: 2021-05-05T12:09:08-05:00
lastMod: 2021-05-05T12:09:08-05:00
categories: [ "markdown" ]
tags: [ "programming", "tech" ]
description: "Markdown Styles"
disableComments: true
draft: true
---

# Headers
## Headers
### Headers
#### Headers
##### Headers
###### Headers
```
# Headers <h1>
## Headers <h2>
### Headers <h3>
#### Headers <h4>
##### Headers <h5>
###### Headers <h6>
```
## Heading with custom id
### A Great Heading {#custom-id}
```
### A Great Heading {#custom-id}
```

# Emphasis
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__
```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__
```

# Strikethrough
~~Strike through text.~~
```
~~Strike through text.~~
```

# Lists
## Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```
* valid bullet
- valid bullet
+ valid bullet

* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

## Ordered
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

```
Using 1. for each of them markdown will automatically number each
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```
# Task List
- [x] Completed
- [ ] Still in Progress
- [ ] Still in Progress
```
- [x] Completed
- [ ] Still in Progress
- [ ] Still in Progress
```

# Images
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```

# Links
http://github.com - automatic!
[GitHub](http://github.com)
[Upstage](https://github.com/upstage/ "Visit Upstage!")
```
http://github.com - automatic!
[GitHub](http://github.com)
# This adds a title to the link
[Upstage](https://github.com/upstage/ "Visit Upstage!")
```

# Named Anchors
* [Chapter 1](#chapter-1)
```
* [Chapter 1](#chapter-1)
```

# Blockquotes
As Kanye West said:

> We're living the future so
> the present is our past.
>> can also be nested

```
As Kanye West said:

> We're living the future so
> the present is our past.
>> can also be nested
```

# Inline Code
I think you should use an
`<addr>` element here instead.
```
I think you should use an
`<addr>` element here instead.
```

# Indented Code
    // Some Comments
    line 1 of code
    line 2 of code
    line 3 of code
```
    // Some Comments
    line 1 of code
    line 2 of code
    line 3 of code
```

# Block Fenced Code
```markdown
Sample text here...
```

```
    ```markdown
    Sample text here...
    ```
```

# HTML Comments
```
<!--
Can't see this
-->
```
<!--
Can't see this
-->

Can't see what's above

# Horizontal Rules
```
___
---
***
```
___
---
***

# Paragraphs
Text is automatically wrapped in paragraph tags

# Tables
| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |
```
| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |
```

# Foonotes
This is a digital footnote[^1].
This is a footnote with "label"[^label]

[^1]: This is a digital footnote
[^label]: This is a footnote with "label"

```
This is a digital footnote[^1].
This is a footnote with "label"[^label]

[^1]: This is a digital footnote
[^label]: This is a footnote with "label"
```

# Other Elements
The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.
This text contains <sub>subscript</sub> text.
This text contains <sup>superscript</sup> text.
Press <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Del</kbd>
Do not forget to buy <mark>Milk</mark> today.
```
abbr
sub
sup
kbd
mark
```

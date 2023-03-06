---
layout: "blog"
title: "Code Test"
date: 2023-02-26T08:15:08-05:00
lastMod: 2023-02-26T08:15:08-05:00
categories: [ "programming" ]
tags: [ "programming", "tech" ]
description: "Testing out code with hugo shortcode"
disableComments: true
draft: true
---

The below is a test of the code

## Shell
```shell
cp -R inventory/sample inventory/my-cluster
```

## CSS
```css
pre {
  background: #1a1a1d;
  padding: 20px;
  border-radius: 8px;
  font-size: 1rem;
  overflow: auto;

  @media ($phone) {
    white-space: pre-wrap;
    word-wrap: break-word;
  }
  
  code {
    background: none !important;
    color: #ccc;
    padding: 0;
    font-size: inherit;
  }
}
```

{{< prompt type="info" >}}
Here is a hint/note for something
{{< /prompt >}}


## Go
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, world.")
}
```

{{< prompt type="danger" >}}
Here is a danger for something
{{< /prompt >}}

## ini
```ini
some: value
some: value
```

{{< prompt type="warn" >}}
Here is a warn for something. Here is a link to something [https://google.com](https://google.com)
{{< /prompt >}}

## yaml
```yaml
---
player: playerOne
action: attack (miss)
---
player: playerTwo
action: attack (hit)
```

{{< prompt >}}
Here is a prompt without a type
{{< /prompt >}}

## json
```json
{
  "this": "is",
  "json": "value"
}
```

# Regular Blockquotes
As Kanye West said:

> We're living the future so
> the present is our past.
>> can also be nested
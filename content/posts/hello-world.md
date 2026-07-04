---
draft: true
date: '2026-07-04T18:24:30+02:00'
title: 'Hello World'
description: "Description text..."
# weight: 1 # Pin a post...
# --------------------------------
tags: ["", "", ""]
author: "Milijan Mosić"
showtoc: true
tocopen: true
hidemeta: false
comments: false
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: false
cover:
    image: "/images/posts/parchment.jpg"
    alt: "Parchment background, standard post"
    caption: ""
    relative: true
    hidden: false
    responsiveImages: true
editPost:
    URL: "https://github.com/milijan-mosic/rendering-scrolls/content"
    Text: "Suggest Changes"
    appendFilePath: true
---

With language (syntax highlighting test):

```go
func main() {
    fmt.Println("hello")
}
```

```python
def main():
    print("hello")
```

## Table

| Left | Center | Right |
|:-----|:------:|------:|
| a    | b      | c     |
| longer text | x | 1 |

## Horizontal rule

---

## Definition list (extension-dependent)

Term
: Definition one
: Definition two

## Footnotes

Text with a footnote.[^1]

[^1]: Footnote content here.

## Shortcodes (Hugo-specific)

{{< figure src="https://placehold.co/400x200" title="Shortcode figure" >}}

{{< youtube dQw4w9WgXcQ >}}

{{< highlight go >}}
fmt.Println("shortcode highlight")
{{< /highlight >}}

## Raw HTML passthrough

<div style="border: 1px solid red; padding: 8px;">
Raw HTML block test.
</div>

<mark>Highlighted text</mark> via raw HTML.

## Emoji (if enableEmoji = true)

:smile: :+1:

## Escaping test

\*not italic\* \`not code\`

## Long paragraph (wrapping test)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

---

---
author: yanfulin
pubDatetime: 2024-06-19T00:00:00Z
title: Markdown Style Guide
slug: markdown-style-guide
featured: false
draft: false
tags:
  - others
description: Here is a sample of some basic Markdown syntax that can be used when writing Markdown content in Astro.
---

Here is a sample of some basic Markdown syntax that can be used when writing Markdown content in Astro.

## Headings

The following HTML `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Paragraph

Xerces his nymph, let her be as snow. Now, in this bitter night when mortal woes are told, shall I be silent when good men defend their gold.

## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

> Tiam, ad dit larides liberum duplex que elemento velit esse possim assum. Quaero ena air am, stadium suptPTIVIdua dudes cornelius est.

> "Don't communicate by sharing memory, share memory by communicating."
>
> — Rob Pike

> [It was the best of times, it was the worst of times](https://example.com), it was the age of wisdom, it was the age of foolishness.

## Tables

| Italics   | Bold     | Code   |
| --------- | -------- | ------ |
| _italics_ | **bold** | `code` |
| _italics_ | **bold** | `code` |
| _italics_ | **bold** | `code` |

## Code Blocks

Pre-formatted code blocks are used for writing about programming or markup source code. Rather than forming normal paragraphs, the lines of a code block are interpreted literally. Astro will automatically highlight the syntax of code written in backticks.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```

## List Types

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- List item
- Another item
- And another item

### Nested list

- Item
  1. First Sub-item
  2. Second Sub-item

## Other Elements

### Link

[link text](https://example.com)

### Image

![sample image](https://images.unsplash.com/photo-1440784352441-6fcd64fcc078?w=500&h=500)

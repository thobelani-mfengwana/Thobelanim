---
authors:
- Lone Coder
categories:
- theme demo
- syntax
date: "2023-07-08"
description: The post demonstrates Mermaid JS support
series:
- Theme Demo
tags:
- hugo
- markdown
- css
- html
title: Mermaid JS support
---

If you want to use [Mermaid-JS](https://mermaid-js.github.io/mermaid/#/) on your website.
Provide `mermaid` as [Shortcode](https://gohugo.io/content-management/shortcodes/#readout) in your markdown file.

{{<mermaid>}}
flowchart LR

    A --> B

    B --> C

    C --> D

    D --> B

{{</mermaid>}}

{{<mermaid>}}
sequenceDiagram
participant Alice
participant Bob
Alice->>Bob: Hi Bob
Bob->>Alice: Hi Alice
{{</mermaid>}}

Find more example on [Mermaid-JS](https://mermaid-js.github.io/mermaid/#/) website.

---
title: "Hello World"
date: 2026-09-15
draft: false
authors:
  - name: Flameberry
    link: https://github.com/flameberry
tags:
  - meta
excludeSearch: false
---

First post. This one exists mostly to prove the pipeline works end to end.

<!--more-->

## What this is

A place for notes on graphics, engines, and systems programming — the kind of
thing I'd otherwise lose in a scratch file.

## Things Hextra gives you for free

Code blocks with syntax highlighting and a copy button:

```cpp
VkResult result = vkCreateInstance(&createInfo, nullptr, &instance);
if (result != VK_SUCCESS)
    throw std::runtime_error("failed to create instance");
```

Callouts:

{{< callout type="info" >}}
Everything under `content/blog/` shows up in the post list automatically.
{{< /callout >}}

Math, if you enable it per page with `math: true` in the front matter, and
Mermaid diagrams from ```` ```mermaid ```` fences.

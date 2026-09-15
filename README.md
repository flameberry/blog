# Flameberry Blog

Hugo + [Hextra](https://imfing.github.io/hextra/), deployed to
<https://flameberry.github.io/blog/> by GitHub Actions on every push to `main`.

## Local development

```sh
hugo server -D          # http://localhost:1313/blog/
```

## Writing a post

```sh
hugo new content blog/my-post.md
```

Posts start as `draft: true` — flip it to `false` (or delete the line) to
publish. Front matter worth knowing:

```yaml
---
title: "My Post"
date: 2026-09-15
draft: false
tags: [vulkan, rendering]
math: true          # opt in to KaTeX on this page
excludeSearch: true # keep it out of the search index
---
```

Text above a `<!--more-->` marker becomes the summary on the post list.

## Updating the theme

```sh
hugo mod get -u github.com/imfing/hextra
hugo mod tidy
```

---
layout:     post
title:      Centering a website
date:       2016-01-01 11:21:29
summary:   
categories: development
---

When we want to center a website, we can put everything in a container div and give it a specific width and margin.

```css
.container {
  width: 1200px;
  margin: 0 auto;
}
```

For a responsive site, we can use em or % for width instead of px.
So it would be something like the following:

```css
.container {
  width: 80em;
  margin: 0 auto;
}
```

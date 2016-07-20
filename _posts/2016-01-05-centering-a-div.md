---
layout:     post
title:      Centering a div
date:       2016-01-05 11:21:29
summary:   
categories: development
---

We might want to center a page or part of a page so that everything is aligned nicely in the center. When we want to center a page, we can put all the contents in a container div and give it a specific width and margin.

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

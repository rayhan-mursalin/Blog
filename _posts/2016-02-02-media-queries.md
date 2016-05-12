---
layout:     post
title:      Media Queries
date:       2016-02-02 11:21:29
summary:   
categories: development
---

Media queries allow us to change styles of content based on the characteristics of the device such as display, width, and height. It is very useful for creating responsive sites.

We can choose what characteristics we want for a device and style our content specifically for that device.

Here is an example of a media query for devices with width between 320px and 1024 px.

```css
@media only screen
and (min-width: 320px)
and (max-width: 1024px) {
.div {
  // style goes here
}
}```

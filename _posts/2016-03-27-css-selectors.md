---
layout:     post
title:      CSS Selectors
date:       2016-03-27 19:21:29
summary:   
categories: development
---


```css
* {
    foo: bar;
}
```
Selects all elements on the page.

```css
h1 {
    foo: bar;
}
```
Selects all h1 elements on the page.

```css
h1, h2, h3 {
    foo: bar;
}
```
Selects all h1, h2 and h3 elements on the page.

```css
.foo {
    foo: bar;
}
p.foo {
    foo: bar;
}
```
Selects all elements with class containing 'foo' or only p elements with that class.

```css
#foo {
    foo: bar;
}
```
Selects the element with 'foo' id.

```css
#foo p {
    bar: fum;
}
```
Selects all p elements within element #foo descendants.

```css
h2 + p {
    foo: bar;
}
```
Selects the sibling element p that is immediately next to h2 element.

```css
#foo > p {
    bar: fum;
}
```
Selects all p elements that are immediate children of #foo element.

```css
h2 ~ p {
    foo: bar;
}
```
Selects all elements p that are siblings to the h2 element.

```css
#foo * {
  foo: bar;
}
```
Selects all elements that is child of #foo.

```css
a:link {
    foo: bar;
}
```
Applies to link elements that have not been visited.

```css
a:visited {
    foo: bar;
}
```
Applies to link elements that have been visited.

```css
.foo:focus {
    bar: fum;
}
```
Applies to selected .foo element that is ready for input.

```css
.foo:hover {
    bar: fum;
}
```
Applies when mouse pointer is over the .foo element.

```css
.foo:active {
    bar: fum;
}
```
Applies when .foo element is in process of being clicked.

```css
.foo:first-child {
    bar: fum;
}
```
Selects the specified .foo element when it is the first child of its parent.

```css
.foo:last-child {
    bar: fum;
}
```
Selects the specified .foo element when it is the last child of its parent.

```css
.foo:nth-child(n) {
    bar: fum;
}
```
Selects the nth .foo child element.

```css
.foo:nth-last-child(n) {
    bar: fum;
}
```
Selects the nth .foo child element counting backwards.

```css
.foo::before {
    bar: fum;
    content: 'baz';
}
```
Adds generated content before the .foo element when used with content property.

```css
.foo::after {
    bar: fum;
    content: 'baz';
}
```
Adds generated content after the .foo element when used with content property.

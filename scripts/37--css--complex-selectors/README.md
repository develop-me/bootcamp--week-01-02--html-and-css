# CSS Complex Selectors

---

### More than just

```css
element {}
.class {}
#id {}
```

---

### Child & Sibling

```css
/* direct child */
parentEl > childEl  {}

/* sibling */
a ~ img  {}

/* ajacent sibling */
a + img  {}
```

---

### Attribute

```css
/* given attr is present */
section[class] {}

/* attribute */
input[type=”submit”]  {}

/* any part of attr */
a[href*=”http”]  {}

/* begins with */
a[href^=”https”]  {}

/* ends with */
a[href$=”pdf”]  {}

/* space separated */
a[class~="btn"] {}

/* hyphen separated */
[class|="page"] {}
```
---

### Pseudo classes

```css
a:link
a:visited
a:hover
a:active
a:focus

input:enabled
input:disabled
input:checked
input:indeterminate
```

Indeterminate [https://css-tricks.com/indeterminate-checkboxes/](https://css-tricks.com/indeterminate-checkboxes/)

---

### Targeting children

```css
el:first-child {}
el:last-child {}
el:only-child {}

el:first-of-type {}
el:last-of-type {}
el:only-of-type {}

el:nth-child(1) {}
el:nth-last-child(2n) {}

el:nth-of-type(2n) {}
el:nth-last-of-type(3) {}

/* Has id which is linked to via <a> with # */
section:target {}

/* no children */
div:empty {}

/* does not have */
article:not(.about) {}
```

---

### Pseudo elements

```css
div::before
section::after

p::first-letter
p::first-line
p::selection
```

---







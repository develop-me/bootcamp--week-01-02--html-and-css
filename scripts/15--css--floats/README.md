# Floats

---

- Floats originally designed for inlaying an element (usually an image) into a block of text
- But used for *all the layout* when semantic HTML became the *de rigueur*
- Now been largely replaced more modern options: flexbox, grid


```css
/* you can float left, right or none */
header h1, header nav {
    float: left;
}
```

---

### Let's see what happens...

---

Floating elements make them jump out of the block scope.

Their containing elements can't see them anymore.

We can get around this...

---

Give the containing (parent) element a *Block Formatting Context*

This happens when

- is floated
- is positioned absolute
- is displayed inline-block
- has an overflow property other than visible/clip
- [a few other situations](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Block_formatting_context)

---

### Floats

```css
header {
    overflow: auto;
    /* OR */
    display: flow-root;
}

header h1, header nav {
    float: left;
}
```
---

### Let's do this

---

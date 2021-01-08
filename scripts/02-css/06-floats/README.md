# Floats

---

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
- has an overflow property
- has a value other than visible

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
















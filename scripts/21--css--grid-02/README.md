# More Grid

---

### Explicit and implicit grids


```css
section {
    display: grid;
    /* how big the rows are */
    grid-auto-rows: 140px;
    /* Direction */
    grid-auto-flow: column;
}
```


These are an explicit grids:

When we specify the grid areas we are creating an explicit grid.

If we didn't CSS grid would place items automatically for us and be an _implicit_ grid

Explicit is what you know, implicit is what you don't know


---

### The `fr` unit

The `fr` unit is only available for grid
(We are considering it as a global unit \o/)


---

### Grid Gap

Adds gaps in-between cells

```css
section {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 1rem;
}
```

---

### `minmax()`

```css
section {
    display: grid;
    grid-template-row: minmax(100px, auto);
}
```

Like min/max width/height. Specifies how big or small something can be

---

### You can name grid lines

```css
section {
    display: grid;
    grid-template-columns: [first] 40px [line2] 50px [line3] auto [col4-start] 50px [five] 40px [end];
}
```

You can name grid lines, note the bracket syntax

---

### Children

Alignment

```css
/* on parent */
section {
    justify-items: start;
    align-items: stretch;
}

/* on individual child */
section p {
    justify-self: end;
    align-self: center;
}
```
---

### Span keyword

```css
section p {
    grid-row-start: 1;
    grid-row-end: span(2);
}
```

# Position & Transforms

---

### For moving elements

- `position`
- `transform`

Not for layout

Note:
Not for layout, for moving/transforming

Only moves element & contents, not surroundings

---

### Position

```css
/* default for all elements */
position: static;
/* gives an element position, can be moved */
position: relative;
/* position an element out of flow */
position: absolute;
/* stays put when scrolling */
position: fixed;
```

---

### Used with

You don't need all four. Movement depends on type of position and parent elements.

```css
top: unit;
bottom: unit;
left: unit;
right: unit;
```

---

### Transforms

These modify element

```css
transform: translate(10px,10px);
transform: translateX(10px);
transform: scale(x,y);
transform: rotate(30deg) skewX(25deg);
```

Further reading:
David DeSandro's transforms examples: [http://desandro.github.io/3dtransforms/](http://desandro.github.io/3dtransforms/)
CSS Transforms on CSS Tricks: [https://css-tricks.com/almanac/properties/t/transform/](https://css-tricks.com/almanac/properties/t/transform/)

---

### Exercise

See readdme

---

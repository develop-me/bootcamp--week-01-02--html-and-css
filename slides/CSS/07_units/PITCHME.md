# CSS Sizing Units

---

### Used as value

Anything that requires a size

Heights, widths, padding, margins, media, borders, background size...

---

### Pixels

Screens work in pixels: 1px = 1 screen pixel
(Not quite with retina screens but workaround)

```
margin: 10px;
```

ABSOLUTE / FIXED

---

### Percentage

Percentage of container
NB always a width, maybe not height as height is set by content

```
div {width: 50%;}
```

RESPONDS

---

### em

Font measurement - relative to parent

```css
body {font-size: 16px;} /* default */
p {font-size: 1.2em;} /* 16 x 1.2 */
p a {font-size: 1.2em;} /* 16 x 1.2 x 1.2 */
```

---

### rem

Like em but always relative to `root`

```css
body {font-size: 1rem;}
p {font-size: 1.2rem;}
p a {font-size: 1.2rem;}
```
---

### Viewport

- 1vw = 1% of viewport width
- 1vh = 1% of viewport height
- 1vmin = 1vw or 1vh, whichever is smaller
- 1vmax = 1vw or 1vh, whichever is larger

```
section {height: 100vh;}
```

RESPONDS

---

### Others

- ex - height of ‘x’
- ch - width of ‘0’
- lh - equal to the line-height
- pt - 1/72“
- mm - mm
- cm - cm

---





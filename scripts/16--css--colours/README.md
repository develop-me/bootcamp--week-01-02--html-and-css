# CSS Colour Formats

Create an element for each CSS colour type, e.g. names, hex, rgb, hsl, rgba and hsla.

Style each one using a different approach.

Starter template:

```html
<div class="colour-boxes">
    <div class="names"></div>
    <div class="hex"></div>
    <div class="rgb"></div>
    <div class="hsl"></div>
    <div class="rgba"></div>
    <div class="hsla"></div>
</div>
```

```css
.colour-boxes {
    display: flex;
}

.colour-boxes > div {
    height: 100px;
    width: 16.66%;
}
```

---
#### Anywhere you use a colour


```css
article {
    border: 1px solid #fafafa;
    background-color: hsla(146, 56%, 48%, 0.8);
}
```


---

### Colour names

Red, blue, yellow, aliceblue, firebrick

Transparent

[List of colour names](https://en.wikipedia.org/wiki/X11_color_names)

---

### Hex codes

Three part hexadecimal format

Each single or pair represent 0-255 in R, G, or B channel

- `#FF0000` = R: FF, G: 00, B: 00
- `#EEF4F1` = R: EE, G: F4, B: F1
- `#F00` = R; FF, G: 00, B: 00

---

### rgb()

Each value 0-255 represents red, green or blue channel

- `rgb(255, 255, 255)`
- `rgb(0, 255, 0)`

---

### rgba

Same as rgb but with alpha (opacity/transparency) channel 0-1

- `rgba(255, 255, 255, 1)`
- `rgba(0, 255, 0, 0.5)`

---

### hsl

Like rgb, but each value represents *hue*, *saturation* and *lightness* rather than a colour channel

- Hue on the colour wheel 0-360
    - red is 0
    - loops (e.g. 0 = 360 = 720)
- saturation & lightness percentage

- `hsl(100, 50%, 50%)`

---

### hsla

Same as before but with alpha channel

- `hsla(200, 20%, 20%, 1)`
- `hsla(0, 80%, 90%, 0.5)`

---

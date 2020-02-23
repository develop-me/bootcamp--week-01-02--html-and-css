# CSS Colour Formats

---
@snap[north-west span-40]
#### Anywhere you use a colour
@snapend

@snap[east span-70]
```css
article {
	border: 1px solid #fafafa;
	background-color: hsla(146, 56%, 48%, 0.8);
}
```
@snapend

---

### Colour names

Red, blue, yellow, aliceblue, firebrick

Transparent

[List of colour names](https://en.wikipedia.org/wiki/X11_color_names)

---

### Hex codes

3 bit hexidecimal format

Each single or pair represent R G or B channel

- `#FF0000` |
- `#F00` |
- `#EEF4F1` |

---

### rgb()

Each value 0-255 represents red, green or blue channel

- `rgb(255, 255, 255)` |
- `rgb(0, 255, 0)` |

---

### rgba

Same as rgb but with alpha (opacity/transparency) channel 0-1

- `rgba(255, 255, 255, 1)` |
- `rgba(0, 255, 0, 0.5)` |

---

### hsl

Like rgb, but each value represents *hue*, *saturation* and *lightness* rather than a colour channel

Hue on the colour wheel 0-360, saturation & lightness percentage

- `hsl(100, 50%, 50%)` |

---

### hsla

Same as before but with alpha channel

- `hsla(200, 20%, 20%, 1)` |
- `hsla(0, 80%, 90%, 0.5)` |

---

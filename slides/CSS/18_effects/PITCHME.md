# CSS Effects

---

### CSS can do some pretty cool things

- Gradients
- Filters
- Blend modes
- Image masking
- Shapes

---

@snap[north-west span-40]
#### Gradients

Linear, radial or conic functions
@snapend

@snap[east span-70]
```css
article {
	background-image: linear-gradient(90deg, red, blue);
}
```
@snapend

---

Use with multiple background images & background size to create cool patterns [https://leaverou.github.io/css3patterns/](https://leaverou.github.io/css3patterns/)

![Pattern Gallery](slides/CSS/18_effects/pattern.png)

---

@snap[north-west span-40]
#### Filters

Media (images & video)
@snapend

@snap[east span-70]
```css
/* can be blur, brightness, contrast, drop-shadow, grayscale, hue-rotate, invert, opacity, saturate, sepia */
img {
	filter: saturate(50%) hue-rotate(30deg);
}
```
@snapend

---

@snap[north-west span-40]
#### Blend modes

See through (blend) elements
@snapend

@snap[east span-70]
```css
/* difference between element & background */
article {
	mix-blend-mode: soft-light;
}
p {
	background-color: purple;
	background-image: url(image.jpg);
	background-blend-mode: multiply;
}
```
@snapend

---

### CSS Shapes

![CSS shape example](slides/CSS/18_effects/cssShape.png)

---

@snap[north-west span-40]
#### Shapes

@snapend

@snap[east span-70]
```css
img {
  float: left;
  shape-outside: circle(50%);
}
```
@snapend


---

### Masks

[Mask example on codepen](https://codepen.io/Rumyra/pen/xxGKzwp)

---

@snap[north-west span-40]
#### Masks

Gradients/images create mask of an element
@snapend

@snap[east span-70]
```css
section {
  mask-image: linear-gradient(90deg, black, transparent 90%);
}
```
@snapend

---

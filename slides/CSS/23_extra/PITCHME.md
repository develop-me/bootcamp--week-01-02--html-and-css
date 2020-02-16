# Some CSS I haven't mentioned

---

### Cursor

```css
/* little hand 👆 */
button {
	cursor: pointer;
}
```

There a quite a few different ones [https://developer.mozilla.org/en-US/docs/Web/CSS/cursor](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor)

You can put an image in

---

### List style

Shorthand 🤗

```css
ul {
	list-style: none;
}
```

For
- `list-style-type`
- `list-style-position`
- `list-style-image`

Easier to use a background image on list items for bullets

---

# Some Cool CSS

---

### Transforms

```css
transform: translate(10px,10px);
transform: translateX(10px);
transform: scale(x,y);
transform: rotate(30deg) skewX(25deg);
```

---

# Transitions & Animations

---

### Transitions

```css
a {
	color: white;
	transition: color 0.2s ease;
}
a:hover {
	color: grey;
}
```

Further reading CSS Tricks: [https://css-tricks.com/almanac/properties/t/transition/](https://css-tricks.com/almanac/properties/t/transition/)

---

### Animations

Declare your animation (can be done anywhere in a CSS file)

```css
@keyframes move {
	0% {
		transform: translate(0px, 0px);
	}
	100% {
		transform: translate(50px, 50px);
	}
}
```

Use anywhere

```css
button {
	animation: move 1s ease-in-out infinite;
}
```

---

### Blend modes

Background images

```css
section {
	background-color: purple;
	background-image: url(image.jpg);
	background-blend-mode: multiply;
}
```

Elements

```css
h1 {
	mix-blend-mode: screen;
}
```

Further reading CSS Tricks: [https://css-tricks.com/basics-css-blend-modes/](https://css-tricks.com/basics-css-blend-modes/)

---

### Filters

For media (images & video)

```css
/* can be blur, brightness, contrast, drop-shadow, grayscale, hue-rotate, invert, opacity, saturate, sepia */

image {
	filter: blur(1px) hue-rotate(90deg);
}
```

---

### CSS Shapes

![CSS shape example](day08/02coolCSS/cssShape.png)

---

I want to mention them but not well supported yet.

[https://www.html5rocks.com/en/tutorials/shapes/getting-started/](https://www.html5rocks.com/en/tutorials/shapes/getting-started/)

[https://www.sarasoueidan.com/blog/css-shapes/](https://www.sarasoueidan.com/blog/css-shapes/)


---

### Custom properties

(Sort of) variables in CSS - the spec is just about to expand...

```css
:root {
	--brandCol: red;
}

p {
	color: var(--brandCol);
}
```

More to be said [https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)

---

### Maths

```css
body {
	padding: 20px;
}
section {
	width: calc(100vw - 40px);
}
```

---

### All those links!

I know there were loads of them, [you can find them here](day08/02coolCSS/README.md)
















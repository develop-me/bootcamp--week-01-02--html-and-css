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


---

### All those links!

I know there were loads of them, [you can find them here](day08/02coolCSS/README.md)

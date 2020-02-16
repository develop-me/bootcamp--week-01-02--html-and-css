# Web Fonts

---

## Web Fonts

- System fonts
	- Whatever is on the users computer
- Custom fonts
	- Served as a file with the website
	- or
	- Used as a 'web font' - loaded via an external resource, like Google Fonts

You’re responsible for making sure users can see custom fonts

---

### You need

- Font files
- Find those fonts:
	- Ask the designer
	- Google
	- Use 'What The Font'...

---

### What the font

Upload an image of the font

[https://www.myfonts.com/WhatTheFont/](https://www.myfonts.com/WhatTheFont/)

---

## Serve yourself

---

### Add the file

- index.html
	- css
	- js
	- images
	- <mark>fonts</mark>

---

### Include it in your CSS

```css
@font-face {
  font-family: 'Gotham';
  font-weight: normal;
  src: url("fonts/gotham-book.otf") format("opentype");
}
```

---

## Web Font

---

### Include the given link

```html
<link href="https://fonts.googleapis.com/css?family=Gotham" rel="stylesheet">
```

### And then use it as per

```css
h1 { font-family: 'Gotham', Arial, sans-serif; }
```

> Don't forget a system backup

---

### System fonts

The fonts available for you to use by default are those installed on the user’s machine

You don’t know what fonts they have, although certain fonts are common

This is why CSS defines fallbacks:

```css
h1 {font-family: 'Gotham', Helvetica, Arial, sans-serif;}
```

---

### It's actually a lot more complicated than that

[https://css-tricks.com/fout-foit-foft/](https://css-tricks.com/fout-foit-foft/)

[https://css-tricks.com/snippets/css/system-font-stack/](https://css-tricks.com/snippets/css/system-font-stack/)

---

## To serve or not to serve

> What is a CDN?

---

## Styling

---

### Go mad!

```css
p {
	font-size: 1em;
	color: #666;

	line-height: 1.6;
	letter-spacing: 1px;
	word-spacing: 5px;

	text-decoration: underline;
	text-transform: uppercase;
	text-shadow: 1px 1px 1px black;

	text-align: right;
	justify-content: justify;
	text-indent: 2em;

	word-break: break-all;
	overflow-wrap: break-word;
	white-space: nowrap;


}
```

---

### I mean really mad!

```css
p {
	font-stretch: expanded;
	font-variant-caps: petite-caps;
	font-variant-ligatures: common-ligatures;
	font-size-adjust: 0.5;
	font-variant-numeric: slashed-zero;
	text-overflow: fade(10px);
	font-kerning: none;
}
```

---







# Web Fonts

---

@snap[north-west span-40]
#### Change a font in CSS

@snapend

@snap[east span-70]
```css
body {
	font-family: 'Helvetica', "Arial", sans-serif;
}
```
@snapend

Note:
Go through syntax - fonts affect child elements - this goes & finds a font file. Font's are files just like images, there are different formats

---

@snap[west span-70]
## But what if the user doesn't have that font file?
@snapend

Note:
Fonts that come installed on your system - system fonts - websites usually have different fonts

---

>You are responsible for making sure a user can see a custom font

---

### You need

- Font files
- Find those fonts: |
	- Ask the designer |
	- Google |
	- Use [What The Font](https://www.myfonts.com/WhatTheFont/) |

---

@snap[north-west span-40]
#### Load fonts into CSS

@snapend

@snap[east span-70]
```css
@font-face {
	font-family: 'Gotham';
  font-weight: normal;
  src: url("fonts/gotham-book.otf") format("opentype");
}
```
@snapend

---

@snap[west span-70]
## Same font, different style?
@snapend

Note:
Load them all in with the same name and specify the style, like weight bold and style italic

---

### Serving yourself

- Pro: You are in control
- Con: It's a hassle

---

@snap[west span-70]
## Web Font Services
@snapend

Note:
Google fonts example

---

@snap[north-west span-40]
#### Load fonts as per

@snapend

@snap[east span-70]
```html
<!-- Google font example -->
<link href="https://fonts.googleapis.com/css?family=Gotham" rel="stylesheet">
```
@snapend

---

### Using a third party

- Pro: Less hassle
- Con: You are not in control

---

@snap[north-west span-40]
#### Same CSS

@snapend

@snap[east span-70]
```css
body {
	font-family: 'Gotham', "Arial", sans-serif;
}
```
@snapend

---

> Don't forget a system backup & keyword!

---
@snap[north-west span-40]
#### Styling

Go mad!
@snapend

@snap[east span-70]
```css
body {
	font-family: 'Gotham', "Arial", sans-serif;
	font-size: 1em;
	color: #666;
	text-align: right;

	line-height: 1.6;
	letter-spacing: 1px;
	text-decoration: underline;
	text-transform: uppercase;
	text-shadow: 1px 1px 1px black;
}
```
@snapend

---
@snap[north-west span-40]
#### Worth a mention

Go mad!
@snapend

@snap[east span-70]
```css
body {
	text-indent: 2em;
	text-overflow: fade(10px);

	word-spacing: 5px;

	word-break: break-all;
	overflow-wrap: break-word;
	white-space: nowrap;

}
```
@snapend

---

### It's actually a lot more complicated than that

[https://css-tricks.com/fout-foit-foft/](https://css-tricks.com/fout-foit-foft/)

[https://css-tricks.com/snippets/css/system-font-stack/](https://css-tricks.com/snippets/css/system-font-stack/)

---



# Web Fonts

---

#### Font Family

CSS property used for changing the font on a web page

Write font family with a single value
```css
h1 {
    font-family: 'Helvetica';
}
```

This finds a font file matching that name.

Talk about quotation marks. We use them if the font has spaces between it's name so best practice to always use them.

##### Font stack

Write font family with a font stack.
```css
h1 {
    font-family: 'Helvetica', "Arial", sans-serif;
}
```
Remove Helvetica to show the effects of a font-stack.

Talk about how the fallback works, font is unavailable e.g. our website is unable to request the font file so browser will back to the next available font

##### Child elements
Font family affects child elements

Move font-family declaration to body, see how it now affects it's child elements.

```css
body {
    font-family: 'Helvetica', "Arial", sans-serif;
}
```

---

#### Styling

Go mad!


```css
body {
    font-family: 'Raleway', "Arial", sans-serif;
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

- Worth a mention


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

---

## But what if the user doesn't have that font file?


Fonts that come installed on your system - system fonts - websites usually have different fonts

---

>You are responsible for making sure a user can see a custom font

---

### You need

- Font files
- Find those fonts:
    - Ask the designer
    - Google
    - [What The Font](https://www.myfonts.com/WhatTheFont/)

---

#### Load fonts into CSS



```css
@font-face {
    font-family: 'Raleway';
  font-weight: normal;
  src: url("fonts/raleway.otf") format("opentype");
}
```


---

## Same font, different style?


Load them all in with the same name and specify the style, like weight bold and style italic

---

### Serving yourself

- Pro: You are in control
- Con: It's a hassle

---

## Web Font Services


Google fonts example

---

#### Load fonts as per



```html
<!-- Google font example -->
<link href="https://fonts.googleapis.com/css?family=Raleway" rel="stylesheet">
```


---

### Using a third party

- Pro: Less hassle
- Con: You are not in control

---

#### Same CSS



```css
body {
    font-family: 'Raleway', "Arial", sans-serif;
}
```


---

> Don't forget a system backup & keyword!

---


---

### It's actually a lot more complicated than that

[https://css-tricks.com/fout-foit-foft/](https://css-tricks.com/fout-foit-foft/)

[https://css-tricks.com/snippets/css/system-font-stack/](https://css-tricks.com/snippets/css/system-font-stack/)

---

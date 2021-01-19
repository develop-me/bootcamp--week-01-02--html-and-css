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

#### Font Styling - common propertiees

Demonstrate the common CSS properties used when styling fonts.

##### Basic font styling

Ensure that you have a `<h1>` and `<p>` in your markup when demonstrating.

Add a font size to the body, explain how 16px is the default body font size.

Each element has it's own starting font style, inspect the `<h1>` and look at user agent styling.

```css
h1 {
    /* It's possible that color values haven't been mentioned yet, stick to hex */
    color: #666;

    /* It's possible that units haven't been mentioned yet, stick to pixels */
    font-size: 32px;

    /* Font weight can accept keywords or specific weight values, 100-900 */
    font-weight: bold;

    /* left,right,center */
    text-align: center;
}
```

```css
p {
    /* Spacing between lines of text, note that this not the same as margin spacing which is between elements */
    /* Demonstrate incrementing the value in DevTools */
    line-height: 1.6;
}

h1 {
    /* Often used in headings, can be used to increase or reduce space between letters */
    letter-spacing: 1px;

    /* https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration */
    /* Accepts multiple keywords, underline is the most common */
    text-decoration: underline;

    /* https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform */
    text-transform: uppercase;

    /* offset-x | offset-y | blur-radius | color */
    /* blur-radius is optional  */
    /* color is optional  */
    text-shadow: 1px 1px 1px black;

    /* Accepts positive and negative values */
    text-indent: 2em;
}
```

##### Less commonly used font styles

```css
body {
    /* How the browser handles text that spills outside of it's element */
    /* clip, ellipsis, */
    /* requires both of the below properties set
        white-space: nowrap;
        overflow: hidden;
     */
    text-overflow: ellipsis;

    word-spacing: 5px;

    /* Determines how an element should handle words that would otherwise spill outside of the it's boundary */
    word-break: break-all;

    /* whether the browser should insert line breaks within an otherwise unbreakable string */
    /* normal, anywhere, break-word */
    overflow-wrap: break-word;

    /* https://developer.mozilla.org/en-US/docs/Web/CSS/white-space */
    white-space: nowrap;
}
```

---

## But what if the user doesn't have that font file?

*Create an article with some lorem ipsum content for the demonstration. Already have a font downloaded to import*

Fonts that come installed on your system - system fonts. Talk about Helvetica, Arial.

Websites usually have different fonts, web fonts. Talk about Google Fonts briefly.

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

```css
@font-face {
    font-family: 'Raleway';
    font-weight: bold;
    src: url("fonts/raleway-bold.otf") format("opentype");
}
```

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
- Con: You are not in control, the third party server can go down (font stack fallback)

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

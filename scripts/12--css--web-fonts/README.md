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

#### Font Styling - common propertiees

Demonstrate the common CSS properties used when styling fonts.

##### Basic font styling

Ensure that you have a `<h1>` and `<p>` in your markup when demonstrating.

Add a font size to the body, explain how 16px is the default body font size.

Each element has it's own starting font style, inspect the `<h1>` and look at user agent styling.

```css
h1 {
    /* Can accept any of CSS' possible color values */
    color: #666;

    /* It's possible that units haven't been mentioned yet, stick to pixels */
    /* Can accept percentages, length values and keywords */
    font-size: 32px;

    /* Font weight can accept keywords or specific weight values, 100-900 */
    /* Not all of the fonts that you are working with will have a bold, 500 etc */
    font-weight: bold;

    /* left,right,center */
    text-align: center;
}
```

```css
p {
    /* Spacing between lines of text, note that this not the same as margin spacing which is between elements */
    /* Demonstrate incrementing the value in DevTools */
    /* Number below is a multiplier of the font-size */
    /* e.g. font size of 16px * 1.5 = 24px */
    line-height: 1.5;
    /* we can also explicitly set line height with px, rem etc */
    /* multiplier is good as it is then relative to the font size */
}

/* https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration */
.underline {
    text-decoration: underline;
}

h2 {
    /* Apply to the h1 */
    letter-spacing: 1px;
    /* Often used in headings, can be used to increase or reduce space between letters */

    /* Accepts multiple keywords, underline is the most common */
    /* https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration */

    /* Apply to the <h1> */
    text-transform: uppercase;
    /* https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform */

    /* Apply to the <h1> */
    text-shadow: 1px 1px 1px black;
    /* offset-x | offset-y | blur-radius | color */
    /* blur-radius is optional  */
    /* color is optional  */


}
p {
    /* Indent the <p> */
    text-indent: 2em;
    /* Accepts positive and negative values */
}
```

##### Less commonly used font styles

For this demonstration, it helps to add some base styling before (or during if it helps demonstrate the concept) the lesson.

```css
p {
    border: 1px solid red;
    width: 200px;
    overflow: hidden;
}
```

```css
body {
    /* https://developer.mozilla.org/en-US/docs/Web/CSS/white-space */
    /* pre - preserve any whitespace found in your elements contents */
    /*
    normal
        Sequences of white space are collapsed. Newline characters in the source are handled the same as other white space. Lines are broken as necessary to fill line boxes.
    nowrap
        Collapses white space as for normal, but suppresses line breaks (text wrapping) within the source.
    pre
        Sequences of white space are preserved. Lines are only broken at newline characters in the source and at <br> elements.
    pre-wrap
        Sequences of white space are preserved. Lines are broken at newline characters, at <br>, and as necessary to fill line boxes.
     */
    white-space: nowrap;

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
}
```

---
## But what if the user doesn't have that font file?

*Create an article with some lorem ipsum content for the demonstration. Already have a font downloaded to import*

Fonts that come installed on your system - system fonts. Talk about Helvetica, Arial.

*Show fonts installed on your system, perhaps using Font Book?*

Websites usually have different fonts, web fonts.

---

>You are responsible for making sure a user can see a custom font

---

### Third Party Web Fonts

#### You need

- Font files
- Find those fonts:
    - Ask the designer
    - Google
    - [What The Font](https://www.myfonts.com/WhatTheFont/)

---

#### Web Font Services

Google fonts example

---

#### Load fonts as per

```html
<!-- Google font example -->
{# Establish network connection early #}
<link rel="preconnect" href="https://fonts.gstatic.com">
{# Request specific font #}
<link href="https://fonts.googleapis.com/css2?family=Nunito:ital@1&display=swap" rel="stylesheet">
```

```css
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital@1&display=swap');
```

---

#### Pros/Cons - Using a third party
Pro: Less hassle
Con: You are not in control, the third party server can go down (font stack fallback)

---

### Hosting your own

Ensure that you already have a font downloaded and saved in an appropriate folder within your workspace. Demonstrate the file structure.

#### Load fonts into CSS

```css
@font-face {
    font-family: 'Raleway';
    font-weight: normal;
    src: url("fonts/raleway.otf") format("opentype");
}
```

---

#### Same font, different style?

Load them all in with the same name and specify the style, like weight bold and style italic

```css
@font-face {
    font-family: 'Raleway';
    font-weight: bold;
    src: url("fonts/raleway-bold.otf") format("opentype");
}
```

---

#### Pros/Cons - Serving yourself

- Pro: You are in control
- Con: It's a hassle

---
### Font Family for Web Fonts

Same as a system font.

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

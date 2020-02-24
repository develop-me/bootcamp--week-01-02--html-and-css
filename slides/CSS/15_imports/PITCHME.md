# CSS Imports

---

Wouldn't it be great if you could separate out your CSS into smaller files?

But annoying to include them all in your HTML?

---

### Imports

We import all smaller CSS files into one file and use **that** one file in our HTML

CSS knows to go and get all the CSS in the other files

----

@snap[north-west span-40]
#### @import example

In your main css file
@snapend

@snap[east span-70]
```css
@import 'reset.css';
@import 'settings.css';
@import 'typography.css';
@import 'buttons.css';
...
```
@snapend

---

How you break up and organise your CSS files is up to you & very much a learning process. Think about your components, having a CSS file for each is a good place to start.

---

#### Exercise:

### Create a place for your project files & set up your CSS to have the ability of multiple files

Note:
- index.html
- styles
- assets (or images/fonts)

---

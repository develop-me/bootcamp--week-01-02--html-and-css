# CSS Grid

---

### Designers have been using grids for a very long time

![New York Times Grid](day07/01CSSgrid/newsGrid.png)

Note: In print - magazine and newspapera

---

### This transferred over to web design

Specifically when we were working with fix width sites.

Note: we didn't have flexbox or grid back then

---

### So we started it with CSS

![Bootstrap Grid](day07/01CSSgrid/bootGrid.png)

---

- Usually 12 columns
- Put classes on your sectioning elements
- Span the number of columns you specify

---

### There are loads

- Of CSS grid systems
- Included in frameworks
- Just have a google!

---

## But...

---

## CSS Grid is here

---

- Not tied into a system
- No addons needed
- No added classes

---

### Used for laying out a page

- Popping content in the right place
- On 2 axis
- It's DOM dependent

---

#### How to use

```css
.page__home {
    display: grid;
}
```

---

#### Specify the amount of cols & rows

```css
.page__home {
    display: grid;
    grid-template-rows: repeat(3, auto);
    grid-template-columns: 20vw 1fr 1fr 10vw;
}
```

---

#### How do we get things in places

We can name the areas we have created

```css
.page__home {
    display: grid;
    grid-template-rows: 20vh 1fr 1fr 16vh;
    grid-template-columns: repeat(3, 1fr);
    grid-template-areas:
        "top top top"
        "middle middle side"
        "middle middle ."
        ". bottom ."
    ;
}
```

---

### Then we can reference those names when we're styling the child sections

```css
.header-main {
    grid-area: top;
}
```

---

#### Or

Grids have number lines automatically, we can use those

```css
.header-main {
    grid-row-start: 1;
    grid-row-end: 2;
    grid-column-start: 1;
    grid-column-end: 4;
}
```

---

#### Shorthand

```css
.header-main {
    grid-row: 1 / 2;
    grid-column: 1 / 4;
}
```

```css
.header-main {
    grid-area: 1 / 1 / 2 / 4;
}
```

---


# CSS Variables

#### AKA Custom Properties

---

#### Another day, another CSS declaration



```css
p {
    color: #00e6b8;
}
h1, h2, h3 {
    color: #00e6b8;
}
button {
    background-color: #00e6b8;
}
input {
    border-color: #00e6b8;
}
```


---

Wouldn't it be nice if we didn't have to look up the colour everytime we use it?

What if the designer changes the colour?

---
#### What if?



```css
:root {
    --devme-teal: #00e6b8;
}

p {
    color: var(--devme-teal);
}
h1, h2, h3 {
    color: var(--devme-teal);
}
button {
    background-color: var(--devme-teal);
}
input {
    border-color: var(--devme-teal);
}
```


---

#### Any CSS values



```css

:root {
    --brand-font: Helvetica, sans-serif;
    --brand-colour: #00e6b8;
    --content-padding:    1rem;
}

```

---

#### Exercise

### Create a settings.css file and create some variables to use in your CSS. Don't forget to add it to your main CSS

---

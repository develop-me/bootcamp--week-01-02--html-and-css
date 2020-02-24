# CSS Variables

#### AKA Custom Properties

---

@snap[north-west span-40]
#### Another day, another CSS declaration

@snapend

@snap[east span-70]
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
@snapend

---

Wouldn't it be nice if we didn't have to look up the colour everytime we use it?

What if the designer changes the colour?

---
@snap[north-west span-40]
#### What if?

@snapend

@snap[east span-70]
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
@snapend

---

@snap[north-west span-40]
#### Any CSS values

@snapend

@snap[east span-70]
```css

:root {
	--brand-font: Helvetica, sans-serif;
	--brand-colour: #00e6b8;
	--content-padding:	1rem;
}

```
@snapend
---

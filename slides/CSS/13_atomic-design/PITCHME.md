# CSS Methodologies

---

### Some things to know

- OOCSS
- Atomic Design
- BEM
- SMACSS

---

# OOCSS: Object Orientated CSS

---

Encourages reuseable, scalable CSS

Example: button used on site, regardless of code surrounding it

---

### Separates structure from skin

---

```css
button {
	width: 100px;
	margin: 0px auto;
}
a.button {
	display: block;
	width: 200px;
}
.skin {
	background-color: green;
	border: 1px solid blue;
}
```
---

# Atomic Design

---

### Way of thinking about structure:

**Atoms:** Elements (input, p, button etc...)

**Molecules:** Set of elements (search form)

**Organism:** Set of Molecules (site header)

**Templates:** Set of Organisms (repeated)

**Pages:** Final site

---

# BEM (Block Element Modifier)

---

### Class naming convention

```css
/* This is the Block */
.block {}

/* This is an element, that helps to form the block as a whole */
.block__element {}

/* This modifies the element or a block*/
.block--modifier {}
```

---

### Example

```
<ul class="menu">
  <li class="menu__item">
    <a class="menu__link">
      <span class="menu__text"></span>
    </a>
  </li>
</ul>

.menu {}
.menu__item {}
.menu__link {}
.menu__text {}
```

---

# SMACSS (Scalable and Modular Architecture for CSS)

---

Way of structuring/organising CSS with conventions

- Base rules
- Layout rules
- Module rules
- State rules
- Theme rules

---

### Further reading

- [http://oocss.org/](http://oocss.org/)
- [http://atomicdesign.bradfrost.com/](http://atomicdesign.bradfrost.com/)
- [http://getbem.com/](http://getbem.com/)
- [https://smacss.com/](https://smacss.com/)









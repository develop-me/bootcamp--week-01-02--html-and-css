# BEM

---
@snap[north-west span-40]
### BEM (Block Element Modifier)

Class naming convention

@snapend

@snap[east span-70]
```css
/* This is the Block */
.block {}

/* This is an element, that helps to form the block as a whole */
.block__element {}

/* This modifies the element or a block*/
.block--modifier {}
```
@snapend

---

@snap[north-west span-40]

Modifications could be `card--noimage`

@snapend

@snap[east span-70]
```html
<article class="card">

	<header class="card__head">
		<h2 class="card__head__text">Card heading</h2>
	</header>

	<figure class="card__img">
		<img src="" alt="" />
	</figure>

	<p class="card__blurb">Some text here</p>

	<a href="" class="card__link">A link</a>

</article>
```
@snapend

---

### It may seem long winded

But we have already seen the benefits of the button class, you can use it on any element and it will adopt the styles.

It also helps other developers understand what CSS is doing what

---

- [http://getbem.com/](http://getbem.com/)









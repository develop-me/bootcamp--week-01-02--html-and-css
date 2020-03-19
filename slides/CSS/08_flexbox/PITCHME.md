# CSS Flexbox

---

### Is used to distribute items along an axis

The browser is in control of the distribution

---

@snap[north-west span-40]
#### Add to container (parent)

All direct children affected

@snapend

@snap[east span-70]
```css
section {
	display: flex;
}
```
@snapend

---

@snap[north-west span-40]
#### You can choose across or down

@snapend

@snap[east span-70]
```css
section {
	display: flex;
	flex-direction: row | row-reverse | column | column-reverse;
}
```
@snapend

---

@snap[north-west span-40]
#### You can choose where on the line you want the items

@snapend

@snap[east span-70]
```css
section {
	display: flex;
	flex-direction: row | row-reverse | column | column-reverse;
	justify-content: flex-start | flex-end | center | space-around | space-between | space-evenly;
}
```
@snapend

@snap[north-west span-40]
#### Whether they wrap

@snapend

@snap[east span-70]
```css
section {
	display: flex;
	flex-direction: row | row-reverse | column | column-reverse;
	justify-content: flex-start | flex-end | center | space-around | space-between | space-evenly;
	flex-wrap: wrap;
}
```
@snapend

---

@snapend

@snap[north-west span-40]
#### Where they are on cross axis

On line and container
@snapend

@snap[east span-70]
```css
section {
	display: flex;
	flex-direction: row | row-reverse | column | column-reverse;
	justify-content: flex-start | flex-end | center | space-around | space-between | space-evenly;
	flex-wrap: wrap;
	align-items: /*on cross axis*/;
	align-content: /*cross axis space in container*/;
}
```
@snapend

---

@snapend

@snap[north-west span-40]
#### The order

Everything is 0 by default
@snapend

@snap[east span-70]
```css
.item {
	order: 2;
}

.item {
	order: -1;
}
```
@snapend

---

@snapend

@snap[north-west span-40]
#### Distribution of item space

Everything is 0 by default
@snapend

@snap[east span-70]
```css
.item {
	flex-grow: 1;
}

.item {
	flex-shrink: 1;
}
```
@snapend

---

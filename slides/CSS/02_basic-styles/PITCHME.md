# CSS

---

## Cascading Style Sheets

---

## Style
our page

---

- Select the HTML element we want to style
- In a variety of ways |
- And add defined properties |

---

### About 438 properties & counting

Maintained list here: [https://meiert.com/en/indices/css-properties/](https://meiert.com/en/indices/css-properties/)

---

Give these properties a value

---

```
selector {
	property: value;
}
```

---

Every character makes a difference

---

```
selector {
	property: value;
}
```

---

```
body {
	background-color: red;
}
```

---

```
p {
	font-size: 1em;
}
```

---

```
.myclass {
	display: block;
	width: 50%;
	padding: 20px;
}
```

---

## Selectors can be:

- element
- class
- id
- complex selectors

---

## Let's look at some basic styles

---

- `background`
- `border`
- `box-shadow`
- `border-radius`

---

### There's lots!

```css
.myClass {
	background-color: transparent;
	background-image: url('myimage.png');
	background-repeat: no-repeat;
	background-position: top left;
}
```
---
### `background` is shorthand

```css
.myClass {
	background: transparent url('myimage.png') no-repeat top left;
}
```

This is common - lot's of properties have shorthand

---

```css
\* scrolling *\
background-attachment: scroll;

\* background bounds *\
background-clip: padding-box;
```

---

### Let's have a go

---

- Copy the first lesson from yesterday
- Make sure it has the correct metadata
- Create a `main.css` file in the same folder
- Style something with a background

---

You can have a gradient as a background image

```css
background-image: linear-gradient(0deg, yellowgreen, palegreen);
```

---

## `border` also shorthand

---

```
border: 1px solid red;

border-width: 1px;
border-style: solid;
border-color: red;
```

---

## `box-shadow` is not shorthand

```
box-shadow: 1px 1px 1px 0px grey;
```

---

## `border-radius` is
you will get used to it 🤓

---

```
border-radius: 10px;

border-top-left-radius: 10px;
border-top-right-radius: 10px;
border-bottom-right-radius: 10px;
border-bottom-left-radius: 10px;
```

---

```
border-radius: 10px 20px 30px 40px;

border-radius: 20px 40px;

border-radius: 5px 0px 30px;
```

---

### Selectors (again)

- element
- class
- id

---

### Style two the same: comma

```
.header-main, section {
	background-color: lightgreen;
}
```

---

### Target a child: space

```
article p {
	border-bottom: 2px solid grey;
}
```

---

### Exercise!

- Use background
- Use border
- Use box-shadow
- Use border-radius

---
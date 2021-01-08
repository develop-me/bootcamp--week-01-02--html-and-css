# CSS: Cascading Style Sheets

For styling the html. Style sheets, we'll cover the cascade more as we go through
---

### We do this by

- Selecting the HTML element we want to style
- In a variety of ways
- And add defined properties
- Give these properties a value

About 438 properties & counting

Maintained list here: [https://meiert.com/en/indices/css-properties/](https://meiert.com/en/indices/css-properties/)

---

#### Let's take a look

A standalone piece of content (always has header)


```css
body {
    background-color: red;
}

selector {
    property: value;
}
```


Every character makes a difference

---

#### Selectors

- elements
- classes
- ids

Explain all - we tend to use classes. Only one id per page

---
#### Style two the same: comma



```css
.header-main, section {
    background-color: lightgreen;
}
```


---
#### Target a child: space



```css
article p {
    border-bottom: 2px solid grey;
}
```



---

#### Where CSS?

- inline
- in a `<style>` element
- in a separate file

Show all. We'll be putting it in a file. &lt;link rel="stylesheet" href="css/main.css">

---
## Whitespace matters in values


But no where else

---

#### Comments



```css
/* This is a comment */
```


---

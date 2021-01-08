# CSS Flexbox

---

### Is used to distribute items along an axis

The browser is in control of the distribution

---

#### Add to container (parent)

All direct children affected



```css
section {
    display: flex;
}
```


---

#### You can choose across or down



```css
section {
    display: flex;
    flex-direction: row | row-reverse | column | column-reverse;
}
```


---

#### You can choose where on the line you want the items



```css
section {
    display: flex;
    flex-direction: row | row-reverse | column | column-reverse;
    justify-content: flex-start | flex-end | center | space-around | space-between | space-evenly;
}
```


#### Whether they wrap



```css
section {
    display: flex;
    flex-direction: row | row-reverse | column | column-reverse;
    justify-content: flex-start | flex-end | center | space-around | space-between | space-evenly;
    flex-wrap: wrap;
}
```


---



#### Where they are on cross axis

On line and container


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


---



#### The order

Everything is 0 by default


```css
.item {
    order: 2;
}

.item {
    order: -1;
}
```


---



#### Distribution of item space

Everything is 0 by default


```css
.item {
    flex-grow: 1;
}

.item {
    flex-shrink: 1;
}
```


---

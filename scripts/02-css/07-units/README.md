# CSS Sizing Units

---
#### Anything requiring a size



```css
article {
    width: 50%;
}
```


---

### Used as value

Heights, widths, padding, margins, media, borders, background size...

---
#### Pixels

Absolute/fixed



```css
article {
    margin: 10px;
}
```


Note: screens work in pixels

---
#### Percentage

Responsive, taken from parent



```css
article {
    width: 50%;
}
```



---
#### Viewport



```css
article {
    width: 50vw;
}
```


---
### Viewport

- 1vw = 1% of viewport width
- 1vh = 1% of viewport height
- 1vmin = 1vw or 1vh, whichever is smaller
- 1vmax = 1vw or 1vh, whichever is larger


---
#### em
Font measurement - relative to parent


```css
body {font-size: 16px;} /* default */
p {font-size: 1.2em;} /* 16 x 1.2 */
p a {font-size: 1.2em;} /* 16 x 1.2 x 1.2 */
```


---
#### rem
Like em but always relative to `root`



```css
body {font-size: 1rem;}
p {font-size: 1.2rem;}
p a {font-size: 1.2rem;}
```


---

### Others

- ex - height of ‘x’
- ch - width of ‘0’
- lh - equal to the line-height
- pt - 1/72“
- mm - mm
- cm - cm

---





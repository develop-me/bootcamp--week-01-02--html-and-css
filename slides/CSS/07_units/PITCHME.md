# CSS Sizing Units

---
@snap[north-west span-40]
#### Anything requiring a size

@snapend

@snap[east span-70]
```css
article {
	width: 50%;
}
```
@snapend

---

### Used as value

Heights, widths, padding, margins, media, borders, background size...

---
@snap[north-west span-40]
#### Pixels

Absolute/fixed

@snapend

@snap[east span-70]
```css
article {
	margin: 10px;
}
```
@snapend

Note: screens work in pixels

---
@snap[north-west span-40]
#### Percentage

Responsive, taken from parent

@snapend

@snap[east span-70]
```css
article {
	width: 50%;
}
```
@snapend


---
@snap[north-west span-40]
#### Viewport

@snapend

@snap[east span-70]
```css
article {
	width: 50vw;
}
```
@snapend

---
### Viewport

- 1vw = 1% of viewport width |
- 1vh = 1% of viewport height |
- 1vmin = 1vw or 1vh, whichever is smaller |
- 1vmax = 1vw or 1vh, whichever is larger |


---
@snap[north-west span-40]
#### em
Font measurement - relative to parent
@snapend

@snap[east span-70]
```css
body {font-size: 16px;} /* default */
p {font-size: 1.2em;} /* 16 x 1.2 */
p a {font-size: 1.2em;} /* 16 x 1.2 x 1.2 */
```
@snapend

---
@snap[north-west span-40]
#### rem
Like em but always relative to `root`

@snapend

@snap[east span-70]
```css
body {font-size: 1rem;}
p {font-size: 1.2rem;}
p a {font-size: 1.2rem;}
```
@snapend

---

### Others

- ex - height of ‘x’
- ch - width of ‘0’
- lh - equal to the line-height
- pt - 1/72“
- mm - mm
- cm - cm

---





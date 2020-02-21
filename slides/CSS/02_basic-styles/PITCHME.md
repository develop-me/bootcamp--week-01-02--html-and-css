# Backgrounds & Borders

---

@snap[north-west span-40]
#### Backgrounds

@snapend

@snap[east span-70]
```css
.myClass {
	background-color: transparent;
	background-image: url('myimage.png');
	background-repeat: no-repeat;
	background-position: top left;
	background-size: 100px 200px;
}
```
@snapend

---

@snap[north-west span-40]
#### Shorthand

@snapend

@snap[east span-70]
```css
.myClass {
	background: transparent url('myimage.png') no-repeat top left;
}
```
@snapend

Note:
This is common - lot's of properties have shorthand

---

@snap[north-west span-40]
#### Border

@snapend

@snap[east span-70]
```css
border: 1px solid red;

border-width: 1px;
border-style: solid;
border-color: red;
```
@snapend

Note:
You can also have border right, left etc...

---

@snap[north-west span-40]
#### Box shadow

Not shorthand
@snapend

@snap[east span-70]
```css
box-shadow: 1px 1px 1px 0px grey;
```
@snapend

Note:
hor, vert, blur, spread, colour

---

@snap[north-west span-40]
#### Border Radius
Rounded corners
@snapend

@snap[east span-70]
```css
border-radius: 10px;

border-top-left-radius: 10px;
border-top-right-radius: 10px;
border-bottom-right-radius: 10px;
border-bottom-left-radius: 10px;
```
@snapend

Note:
If they are ready go through shorthand

---
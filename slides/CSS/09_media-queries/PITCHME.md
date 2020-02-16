# Responsive & adaptive design

---

![Lots and lots of devices](day02/04responsive/devices.png)

---

## Responsive

Responding to the environment

Making the webpage/app resize to it's device for instance

---

## Adaptive

Adapting to the device

Serving a different set of files for different set of devices or connections

Note:
I'm sure you seen 'mobile' sites - this is adaptive. We'll be looking into responsive on this course as it's uses a specific coding technique

---

### Designs that work in all environments:

- Screens
- Inside/outside
- Noisy/quiet
- Fibre/2G

---

<video src="https://github.com/develop-me/fellowship-wk1-beg-html-css/blob/master/day02/04responsive/guardian.mp4"></video>

---

### How?

- Use relative not absolute CSS units
- CSS Media Queries |
- JavaScript feature and device detection |
- Speedtesting is hard |

---

### Media queries

Different types of media, like print

```css
@media print {

	* {
		background-color: transparent;
	}

}
```
---

### Breakpoints (viewport width)

```css
/* phone */
@media only screen and (max-width: 500px) {

	#left-column {
		display: none;
	}

}
```

---

```css
/* Extra small devices (phones, less than 768px) */
@media (max-width: 767px) { ... }

/* Small devices (tablets, 768px and up) */
@media (min-width: 768px) and (max-width: 991px) { ... }

/* Medium devices (desktops, 992px and up) */
@media (min-width: 992px) and (max-width: 1199px) { ... }

/* Large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) { ... }
```
---

## Targeting Devices

---

### JavaScript libraries to detect:

- device type
- touchscreen or desktop
- operating system
- browser

Can add class to body with JavaScript:

```
<body class=“touchscreen tablet windows8 w1024”>
```
---

### Can even detect orientation

```
<body class=“dim-short-600 dim-long-1024 portrait”>
```
```
<body class=“dim-short-600 dim-long-1024 landscape”>
```
https://modernizr.com/

---

### Use CSS where possible

Cleaner, faster and easier to maintain using CSS-only approach and media queries.

New devices come out all the time, and with 1000s of devices out there, unlikely to be able to accurately determine all types.

---

## Planning responsive layout

---

### Consider hierarchy and navigation

- What content is most important? What should come first?
- How can we navigate?
- Is some content worth losing for a simplified mobile experience? E.g. video, slideshow.

---

### Exercise

Add responsive CSS to your layout

---

### Further reading

- [https://responsivedesign.is/](https://responsivedesign.is/)
- [https://en.wikipedia.org/wiki/Responsive_web_design](https://en.wikipedia.org/wiki/Responsive_web_design)

---


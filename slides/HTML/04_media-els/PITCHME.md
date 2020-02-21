# Media Elements

Found in html.pdf, 2.3

---

@snap[north-west span-40]
#### Video

Include a video
@snapend

@snap[east span-70]
```html
<video src="myvideo.mp4"
	poster="firstimage.jpg"
	controls></video>
```
@snapend


---

@snap[north-west span-40]
#### Audio

Include an audio track
@snapend

@snap[east span-70]
```html
<audio src="myaudio.mp3" controls></audio>
```
@snapend

---

@snap[north-west span-40]
#### Source

Add inside audio or video to load different file types
@snapend

@snap[east span-70]
```html
<source src="/media/examples/flower.webm" type="video/webm">

<source src="/media/examples/flower.mp4" type="video/mp4">
```
@snapend

---

@snap[north-west span-40]
#### Picture

Use to load different image sizes and types (with source)
@snapend

@snap[east span-70]
```html
<picture>
    <source srcset="/media/examples/surfer-240-200.jpg"
            media="(min-width: 800px)">
    <img src="/media/examples/painted-hand-298-332.jpg" />
</picture>
```
@snapend

---

@snap[north-west span-40]
#### Figure

Usually a figure is an image, illustration, diagram, code snippet.
@snapend

@snap[east span-70]
```html
<figure>
    <img src="/media/examples/elephant-660-480.jpg"
         alt="Elephant at sunset">
    <figcaption>An elephant at sunset</figcaption>
</figure>
```
@snapend

---

@snap[north-west span-40]
#### Figcaption

A caption or legend describing the rest of the figure contents
@snapend

@snap[east span-70]
```html
<figcaption>An elephant at sunset</figcaption>
```
@snapend

---

# Media Elements

Found in html.pdf, 2.3

---

#### Video

Include a video


```html
<video src="myvideo.mp4"
    poster="firstimage.jpg"
    controls></video>
```



---

#### Audio

Include an audio track


```html
<audio src="myaudio.mp3" controls></audio>
```


---

#### Source

Add inside audio or video to load different file types


```html
<source src="/media/examples/flower.webm" type="video/webm">

<source src="/media/examples/flower.mp4" type="video/mp4">
```


---

#### Picture

Use to load different image sizes and types (with source)


```html
<picture>
    <source srcset="/media/examples/surfer-240-200.jpg"
            media="(min-width: 800px)">
    <img src="/media/examples/painted-hand-298-332.jpg" />
</picture>
```


---

#### Figure

Usually a figure is an image, illustration, diagram, code snippet.


```html
<figure>
    <img src="/media/examples/elephant-660-480.jpg"
         alt="Elephant at sunset">
    <figcaption>An elephant at sunset</figcaption>
</figure>
```


---

#### Figcaption

A caption or legend describing the rest of the figure contents


```html
<figcaption>An elephant at sunset</figcaption>
```


---

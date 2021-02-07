# Media Elements

Found in html.pdf, 2.3

Files to include as source elements can be found within this scripts folder.

---

#### Video

Include a video


```html
<video src="cat.mp4"
    poster="penguin.jpg"
    controls></video>
```



---

#### Audio

Include an audio track


```html
<audio src="bird.mp3" controls></audio>
```


---

#### Source

Add inside audio or video to load different file types.

Can refer to the this browser support table as to why we do this -> https://caniuse.com/?search=video%20format

Would typically provide the same video in multiple formats here, but this is to illustrate the point.

Use IE11 in a CBT tool to show cat video.

- WEBM - has a decent level of browser support, not in IE11
- MP4 very well supported


```html
<source src="css.webm" type="video/webm">

<source src="cat.mp4" type="video/mp4">
```


---

#### Picture

Use to load different image sizes and types (with source)


```html
<picture>
    <source srcset="penguin.jpg"
            media="(min-width: 400px)">
    <source srcset="turtle.jpg"
            media="(min-width: 800px)">
    <img src="snake.jpg" />
</picture>
```


---

#### Figure

Usually a figure is an image, illustration, diagram, code snippet.


```html
<figure>
    <img src="penguin.jpg"
         alt="Penguin sat on rock covered in snow">
</figure>
```


---

#### Figcaption

A caption or legend describing the rest of the figure contents


```html
<figcaption>Penguin sat on rock covered in snow</figcaption>
```

---

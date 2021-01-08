# HTML Introduction

---

### HTML is a data structure

- Hypertext Markup Language (sometimes referred to as just 'markup' or 'marking something up')
- Based on XML
- Gives the browser (environment) data (information)
- Content layer
    - CSS: Style layer
    - JavaScript: Interaction layer

---

Let's have a look at some HTML


```html
<p class="lede">Here is some text</p>
```


Element, attribute, contents
Open angle brackets, write element, write any attributes, close angle bracket, write content, open angle brackets, FORWARD SLASH, write element again

---

Another example: Self closing & multiple attributes


```html
<img src="myimage.jpg" alt="A photo of a girl holding a book" />
```


Sometimes we self close elements - rare
Let's talk about attributes. There are attributes that you must put on elements, that you can and those that you can define yourself.
There are all attr equals quotes parameter
You can have more than one per element and we seperate them with a space

---
You can put elements inside of elements


```html
<p class="lede">
    Here is some text
    <img src="myimage.jpg" alt="A photo of a girl holding a book" />
</p>
```


We add a tab to the inside element when we do this, so we can easily read it.
When we put an element inside another element the one inside is called the child and the one containing the other element is called the parent.
We can put as many elements inside as many elements as we like!

---
## Whitespace


This is what we call the spaces in code, like the regular space or tabs at the beginning.
Spaces matter when you write HTML elements because you want to make sure attributes don't merge into each other or the element.

---

Comments are parts of a code file that are ignored by the program running it.


```html
&lt;!-- this is an HTML comment -->
```


Comments are useful to describe what the code is doing, or to remind yourself of things. They can even be used for documentation.

---

HTML document structure


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title></title>
</head>
<body>
    <!--write the content here -->
</body>
</html>
```




There's a declaration at the top, then everything is inside \texttt{html} tags. The next section descirbes which we would write in the \texttt{head} element and we add all the content to be shown inside the \texttt{body} element. There can only be one of each of these per HTML document

---

#### Exercise:

### Let's create an HTML document together

Create a new file and add in the minimum structure

---

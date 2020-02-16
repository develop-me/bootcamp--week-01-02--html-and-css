# Lesson 01: Basic HTML

---

## HTML is a data structure

- Hypertext Markup Language (sometimes referred to as just 'markup' or 'marking something up') |
- Based on XML |
- Gives the browser (environment) data (information) |
- Content layer |
	- CSS: Style layer
	- JavaScript: Interaction layer

---

## Let's have a look at some HTML

```
<!DOCTYPE html>
<html lang="en">
<head>
	<title></title>
</head>
<body>

</body>
</html>
```

---

## A closer look

```html
<html lang="en">
```

- open angle bracket |
- element |
- attribute |
- double quotes |
- param |

---

- close quotes |
- more attributes? |
- close angle bracket |
- content |

---

```html
<p class="article" id="about-me">Some amazing things here</p>
```

- open angle bracket |
- forward slash |
- element |
- close angle bracket |

---

## Your turn

```html
<a href="http://www.google.com">Google</a>
```

---

## And again

```html
<input type="text" name="firstname" />
```

---

## Let's have a go

DEMO

Let's look around Sublime...

Note:
Look around Sublime
Start a basic html file with the whole class

---

## There's a finite amount of elements

[https://developer.mozilla.org/en-US/docs/Web/HTML/Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

Note:
I'm not going to teach them all to you - I'm going to go over the ones you are going to use on a day to day basis

---

## Why is it important?

You're describing content.

The browser does magic things!

Note:
We'll go over this in more detail later, but suffice to say there's loads of benefits to using the right element for the right content.

---

## HTML Sectioning Elements

- `<body>` Contains all content (Can only be one)
- `<header>`, `<footer>`, `<article>`, `<aside>`, `<nav>`, `<main>`
- `<div>`, `<section>`

Note:
article: a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include: a forum post, a magazine or newspaper article, or a blog entry.
aside: a portion of a document whose content is only indirectly related to the document's main content.
section: a standalone section — which doesn't have a more specific semantic element to represent it
div: generic container for flow content. It has no effect on the content or layout until styled using CSS

---

## Some HTML Content Elements

- `<h1`...`<h#>`
- `<p>`
- `<ul>`,`<ol>`,`<dl>`
- `<a>` needs `href` attr
- `<blockquote>`, should have a `cite` attr, `<q>`, `<cite>`
---

- `<details>`, `<summary>`
- `<img>` needs a `src` *and* an `alt` attr
- `<button>`

---

## The data structure

- Tree structure
- Parents and children

```
<article>
	<header>
		<h1>My Website</h1>
	</header>
</article>
```

---

## Your turn

- Exercise one


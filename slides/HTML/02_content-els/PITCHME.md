# Content Elements

Found in html.pdf, 2.1

---

@snap[north-west span-40]
#### Headings

Contain heading text. Can have multiple per document, weight of heading not order.
@snapend

@snap[east span-70]
```html
<h1>Heading level 1</h1>
<h2>Heading level 2</h2>
...
<h6>Heading level 6</h6>
```
@snapend

---

@snap[north-west span-40]
#### Paragraphs

For all lines & blocks of text
@snapend

@snap[east span-70]
```html
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at justo egestas, imperdiet nulla vitae, ultrices ante.</p>

```
@snapend

---

@snap[north-west span-40]
#### Lists

ordered, unordered & description
List items can only be the direct children of ol & ul
@snapend

@snap[east span-70]
```html
<ol>
	<li>First list item</li>
	<li>List item two</li>
	<li>Another list item</li>
</ol>

<ul>
	<li>First list item</li>
	<li>List item two</li>
	<li>Another list item</li>
</ul>

<dl>
	<dt>Description term</dt>
	<dd>Description definition</dd>

	<dt>Description term</dt>
	<dd>Description definition</dd>
	<dd>Another definition</dd>
</dl>

```
@snapend

---

@snap[north-west span-40]
#### Anchors

aka links: These go places
@snapend

@snap[east span-70]
```html
<a href="http://webaddress.com">Taking me some place else</a>
```
@snapend

---

@snap[north-west span-40]
#### Buttons

NOT links
@snapend

@snap[east span-70]
```html
<button>Do a thing</button>
```
@snapend

---

@snap[north-west span-40]
#### Images

Invalid without attributes (remember your alts)
@snapend

@snap[east span-70]
```html
<img src="example.png" alt="A photo of a girl holding a book" />
```
@snapend

---
@snap[north-west span-40]
#### Quotes

Can use cite element or/and cite attribute
@snapend

@snap[east span-70]
```html
<blockquote cite="Someone, 2020">
	<p>Someone said this amazing thing</p>
	<cite>Someone, 2020</cite>
</blockquote>
```
@snapend

---

@snap[north-west span-40]
#### Details & Summary

@snapend

@snap[east span-70]
```html
<details>
	<summary>How do you do a thing?</summary>
	<p>This is how you do a thing</p>
</details>
```
@snapend

---

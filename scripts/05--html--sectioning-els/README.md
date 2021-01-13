# Sectioning Elements

Found in html.pdf, 2.2

---

## Types

- Header
- Footer
- Main
- Aside
- Nav
- Article
- Section
- Div


#### Header

- Header of the part of the document:


    ```html
    <header>
        <h1>Heading level 1</h1>
    </header>
    ```



---

#### Footer

Footer of the part of the document


```html
<footer>
    <p>Copyright DevMe</p>
</footer>
```


---

#### Main

Main unique content, can only be one per page


```html
<main> ... </main>
```


---

#### Aside

Related, but not main, content.


```html
<aside>...</aside>
```

aside: a portion of a document whose content is only indirectly related to the document's main content.

---

#### Nav

Site related navigation


```html
<nav>
    <ul>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
</nav>

<nav>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
</nav>
```


---

#### Article

A standalone piece of content (always has header)


```html
<article>...</article>
```

- article: a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include: a forum post, a magazine or newspaper article, or a blog entry.


---
#### Section

Part of a piece of content


```html
<section>...</section>
```

section: a standalone section — which doesn't have a more specific semantic element to represent it

---

#### Div

For design purposes only


```html
<div>...</div>
```

div: generic container for flow content. It has no effect on the content or layout until styled using CSS

---

# Content Elements

Found in html.pdf, 2.1

---

#### Headings

- Contain heading text.
- Can have multiple per document, weight of heading not order.


```html
<h1>Heading level 1</h1>
<h2>Heading level 2</h2>
...
<h6>Heading level 6</h6>
```


---

#### Paragraphs

- For all lines & blocks of text


```html
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas at justo egestas, imperdiet nulla vitae, ultrices ante.</p>

```


---

#### Lists

- Ordered, unordered & description
- List items can only be the direct children of `ol` & `ul`:


    ```html
    <ol>
        <li>First list item</li>
        <li>List item two</li>
        <li>Another list item</li>
    </ol>
    ```

    ```html
    <ul>
        <li>First list item</li>
        <li>List item two</li>
        <li>Another list item</li>
    </ul>
    ```

    ```html
    <dl>
        <dt>Description term</dt>
        <dd>Description definition</dd>

        <dt>Description term</dt>
        <dd>Description definition</dd>
        <dd>Another definition</dd>
    </dl>

    ```


---

#### Anchors

aka links: These go places


```html
<a href="http://webaddress.com">Taking me some place else</a>
```


---

#### Buttons

NOT links


```html
<button>Do a thing</button>
```


---

#### Images

Invalid without attributes (remember your alts)


```html
<img src="example.png" alt="A photo of a girl holding a book" />
```


---
#### Quotes

Can use cite element or/and cite attribute


```html
<blockquote cite="Someone, 2020">
    <p>Someone said this amazing thing</p>
    <cite>Someone, 2020</cite>
</blockquote>
```


---

#### Details & Summary



```html
<details>
    <summary>How do you do a thing?</summary>
    <p>This is how you do a thing</p>
</details>
```


---

#### Tables

Display data


```html
<table>
    <tr>
        <th>Dessert</th>
        <th>Calories</th>
        <th>Fat</th>
        <th>Carbs</th>
    </tr>
    <tr>
        <td>Frozen yogurt</td>
        <td>159</td>
        <td>6.0</td>
        <td>24</td>
    </tr>
    <tr>
        <td>Ice cream sandwich</td>
        <td>237</td>
        <td>9.0</td>
        <td>37</td>
    </tr>
    <tr>
        <td>Eclair</td>
        <td>262</td>
        <td>16.0</td>
        <td>24</td>
    </tr>
</table>
```


---

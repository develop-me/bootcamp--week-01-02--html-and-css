# Text Elements

---

#### Important & Emphasis



```html
<strong>This is important</strong>

<em>This is emphasised</em>
```

The HTML Strong Importance Element (`<strong>`) indicates that its contents have strong importance, seriousness, or urgency. Browsers typically render the contents in bold type.

The HTML `<em>` element marks text that has stress emphasis.


---

#### Styling

No _semantic_ value



```html
<b>This is bold</b>

<i>This is italic</i>
```


---

#### Span

Like a div for text



```html
<span>This text has an element around it</span>
```

A span is an element devoid of any meaning. It is simply there for us to be able to divide things up for styling or scripting purposes, but other than that it doesn't add any semantic meaning to the page.

It is an inline element meaning that when it comes in the middle of other inline elements or inside some text it does not cause there to be a new line.

We might want to use a span to style a particular word or part of a word in some text without adding any other meaning to the word.


---

#### Sup & Sub



```html
<sup>This is small and raised</sup>

<sub>This is small and lowered</sub>
```

The sup and sub elements are used for adding superscript and subscript in HTML. This is useful for chemical and mathematical notation, but also for some more everyday uses. Let's take a look at some examples

CO<sub>2</sub>
H<sub>2</sub>O
January 1<sup>st</sup>


---

#### Time

Any date or/and time



```html
<time datetime="2020-07-21">21st July</time>

```

The `<time>` element is used for displaying a date or a time and it's useful because we can use it to help machines understand the time. This gives us better search engine results and allows for features like reminders and calendars to more easily interact with your HTML.

The way we do this is by adding a `datetime` attribute in a machine readable format.

What that generally means is the date in the order YYYY-MM-DD and the time in a 24 hour clock. There are a few different ways this can end up being formatted, but in general it's enough to just have a space betwen the date and the time.


---

#### Inline quote



```html
<q>Someone said this</q>

```

The inline quote can be used to indicate that some text is a quotation. It's an inline element meaning it won't break the quote down onto a new line. When selecting the text of an inline quote you may notice that the quotation marks that have been added are not selectable. That's because they're not part of the content, but they're something that has been added by the `<q>` tag.

---

#### Code



```html
<code>Inline</code>

<pre><code>
    A block of code
</code></pre>
```

A `<code>` element is used to indicate that the contents should be read as code. It also styles its contents with a monospace font.

This is fine for single lines of code, but when we try to put a multi line snippet of code in there, all of the lines are collapsed onto one line.

To address this, we can wrap it in a `<pre>` element which will preserve any whitespace. Pay close attention to the whitespace you have, because if you have too much, your code may display further across the screen than you want it to.

---

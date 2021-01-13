# CSS Specificity

---

Specificity determines, which CSS rule is applied by the browsers.

It’s usually the reason why your CSS-rules don’t apply to some elements, although you think they should.

---

### Rules

Every selector has its place in the specificity hierarchy.

1. Inline styles
2. IDs
3. Classes, attributes & pseudo classes
4. Elements & pseudo elements

If two selectors apply to the same element, the one with higher specificity wins.

---

Order is important - latest rule still applies...

Unless specificity value is higher

```
<div id=”thing”>Content Here</div>

#thing {background-color: red;}
div {background-color: blue;}
```

---

### Devtools is your friend

Also specificity calculator:

[https://specificity.keegan.st/
](https://specificity.keegan.st/
)




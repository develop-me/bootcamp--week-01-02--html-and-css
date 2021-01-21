# Metadata

---

## All the stuff in the `<head>`



```html
<head>
    <meta charset="utf-8">
    <meta http-equiv="x-ua-compatible" content="ie=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title></title>
    <meta name="description" content="">

    <link rel="apple-touch-icon" href="icon.png">
    <!-- Place favicon.ico in the root directory -->

    <link rel="stylesheet" href="css/main.css">
</head>
```

## HTML5 Boilerplate

Opinionated project structure.

Save time and effort setting up a project.

Mobile friendly and includes the typical code that you include in most responsive and adaptive websites.

https://html5boilerplate.com/

Things to cover:

- File structure
- index.html
    - DOCTYPE
    - `<html lang="">`
    - `<head>`
        - Mainly viewport, title etc
        - Talk about other meta tags used for SEO, PWA


Fill in some of the missing tags/attributes.

---

#### Character Set

Content is composed of a sequence of characters.

Characters represent letters of the alphabet, punctuation, etc. But content is stored in a computer as a sequence of bytes, which are numeric values.

The way that the sequence of bytes is converted to characters depends on what key was used to encode the text

With a web page, it depends on which character set we're using.

A HTML document requires a charset value, so that the browser understand to read the document.

We use `utf-8` as this has multi-lingual support and provides backwards compatibility to more limited character sets such as ASCII.


```html
<meta charset="utf-8">
```

---

#### Title & Description



```html
<title>Website page title</title>

<meta name="description" content="">
```



---

#### Icons

There are lots of these


```html
<link rel="apple-touch-icon" href="apple-touch-icon.png">
<!-- Place favicon.ico in the root directory -->
```


---

#### Include Files

##### Link tag common usages

**CSS**
Can be a link to CSS we host or a URL to an external resource.
```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

<link rel="stylesheet" href="css/main.css">
```

**Favicons**
Icon displayed in browser tab.
```html
<link rel="icon" href="favicon.ico">
```

**Application icons iOS/Android**
```html
<link rel="apple-touch-icon-precomposed" sizes="114x114"
      href="apple-icon-114.png" type="image/png">
```

##### Link attributes

- `href` - path to resource
- `rel` - relationship between resource and our HTML document
- `media` - accepts a CSS media query

##### Script tag common usages

**JS**
Can be a link to JS we host or a URL to an external resource.

Inline JS.

Can also be used with other languages, WebGL and JSON.

```html
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>

<script src="js/main.js"></script>

<script>
    console.log('Hello World!');
</script>
```

---

#### Use IE Edge if available

Should be as high as possible in the document head.

From Microsoft:
"If you are using the X-UA-Compatible META tag you want to place it as close to the top of the page's HEAD as possible. Internet Explorer begins interpreting markup using the latest version. When Internet Explorer encounters the X-UA-Compatible META tag it starts over using the designated version's engine. This is a performance hit because the browser must stop and restart analyzing the content."

Options are:
- `IE=edge`
- `IE=11`
- `IE=EmulateIE11`
- `IE=10`
- `IE=EmulateIE10`
- `IE=9`
- `IE=EmulateIE9`
- `IE=8`
- `IE=EmulateIE8`
- `IE=7`
- `IE=EmulateIE7`
- `IE=5`

```html
<meta http-equiv="x-ua-compatible" content="ie=edge">
```

---

#### Ignore retina screens



```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

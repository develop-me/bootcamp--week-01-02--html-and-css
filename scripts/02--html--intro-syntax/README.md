# HTML Introduction

---

### HTML is a data structure

- HyperText Markup Language (sometimes referred to as just 'markup' or 'marking something up')
- Based on XML
- Gives the browser (environment) data (information)
- Content layer
    - CSS: Style layer
    - JavaScript: Interaction layer

- Show some HTML (in VS Code/Browser)

    ```html
    <p class="lede">Here is some text</p>
    ```

- Element, attribute, contents
- Open angle brackets, write element, write any attributes, close angle bracket, write content, open angle brackets, FORWARD SLASH, write element again

- Another example: Self closing & multiple attributes:

    ```html
    <img src="myimage.jpg" alt="A photo of a girl holding a book" />
    ```

- Sometimes we self close elements - rare
- Let's talk about attributes. There are attributes that you must put on elements, that you can and those that you can define yourself.
- There are all: attr, equals, quotes, value
- You can have more than one per element and we separate them with a space

---

- You can put elements inside of elements:

    ```html
    <p class="lede">
        Here is some text
        <img src="myimage.jpg" alt="A photo of a girl holding a book" />
    </p>
    ```

- We add indentation (tab key/VS Code shortcuts) to the inside element when we do this, so we can easily read it.
- When we put an element inside another element the one inside is called the child and the one containing the other element is called the parent.
- We can put as many elements inside as many elements as we like!

---

## Whitespace

- sometimes it's important to think about the whitespace in your HTML, that is to say how you format your file.
- whitespace in content: multiple spaces condensed down to only 1
- whitespace between attributes doesn't make a difference but it's best for neatness to put 1 space between each attribute
- whitespace after tag name is necessary or else the tag name and the first attribute get joined together
- cannot put whitespace between the tag opening angle bracket and the tag name
- new line characters: all elements could go on the same line, but it's hard to read
- when there are very many attributes on an element, you can put each one on a new line so that they're easier to keep track of. Indent them one level further in than the tag open and close angle brackets.

---

## Comments

- Comments are something used to put some text in a file that is ignored
- Comments are useful to describe what the code is doing, or to remind yourself of things.
- They can even be used for documentation.
- Use `cmd` or `ctrl` + `/` to insert single line comment
- Use `opt` or `alt` + `shift` + `a` to insert or remove a mulitiline comment

---

- HTML document structure:

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


- doctype declaration
- html element
- head element
- body element
- only one of these
- what the head is for (additional information, fetching resources, etc.)
- what the body is for (elements that display on the page)
- what not to do (multiple head/body tags, things outside body, html)
- indentation of the head and body tags

---

## Group Exercise

Create a new file and add in the minimum structure

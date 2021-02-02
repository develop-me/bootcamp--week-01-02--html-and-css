# HTML Forms

---

#### Introduction

- Forms are for submitting data. They allow the user to interact with your website.
- This data is then processed and perhaps stored on the site's server
- Therefore we can't do everything we want to with a form just in HTML and CSS
- Even typing into Ecosia/Google search is using a form

#### form tag

- `<form>`
- Formally and semantically defines your form, like a <section> or <article>
- Attributes
    - **action**
        - defines the location (URL) where the form's collected data should be sent when it is submitted.
        - if empty defaults to same page
    - **method**
        - defines which HTTP method to send the data with
        - default is `GET`
        - also `POST`

#### label tag

- `<label>`
- Important for accessibility. Always include a label for each input.
- the `for` attribute is important as it connects the label to the `id` of the associated input
- this enables screenreaders to read the label when an input is selected

```html
<label for="firstName">First Name</label>
<input type="text" name="name" id="firstName" />
```

#### input tag

- `<input>`
- self-closing tag
- can be nested in the label so that their association is implicit but it is best practice to still use the `for` attribute on the label 

Important attributes:

- `id` - to connect to the label
- `name` - important for submitting data. Used as part of a name/value pair.
- `value` - add a default value for the input
- `placeholder` - add a placeholder for the input. Better to do this than add a default value for UX purposes (don't have to delete it to type)
- `type`
    - the most important attribute
    - defaults to `text`
    - lots of different types ([see MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Input))

```html
<label for="city">Country</label>
<input type="text" name="city" id="city" placeholder="United Kingdom" value="" />
```


- Text types
    - `password`: hides input
    - `email`
    - `url`
    - `tel`

- Numbers and Dates
    - number
    - range

    ```html
    <label for="inrange">Range</label>
    <input type="range" name="rangein" id="inrange" min="0" max="10" step="1" />
    ```

    - date
    - datetime-local
    - month
    - time
    - week

- Checkboxes and Radio Buttons
    - checkbox

    ```html
    <label for="incheck">Checkbox</label>
    <input type="checkbox" name="checkin" id="incheck" checked />
    ```

    - radio: same name, only one can be selected

    ```html
    <div>
        <label for="inradio">Radio</label>
        <input type="radio" name="radioin" value="optone" id="inradio" /><span>Option one</span>
        <input type="radio" name="radioin" value="optwo" /><span>Option Two</span>
    </div>
    ```

- Misc. inputs
    - file: for selecting files
    - search: rounded corners/clear field button
    - color

- Hidden inputs
    - Data that needs submitting but not show to user

- Select

    ```html
    <label for="dropdown">Select</label>
    <select id="dropdown" name="dropdown">
        <option value="opone">opt one</option>
        <option selected value="optwo">opt two</option>
        <option value="opthr">opt three</option>
    </select>
    ```

    - also `<optgroup>` for grouping options
    - more advanced fake select boxes using JS

- Text Area

    ```html
    <label for="message">Textarea</label>
    <textarea id="message" name="message"></textarea>
    ```

    - "value"
        - goes *between* tags
        - careful: *all* whitespace between tags is included

- Fieldset & Legends
    - For grouping inputs that are related

    ```html
    <fieldset>
      <legend>About You</legend>

      <label for="first-name">First Name</label>
      <input type="text" name="first-name" id="first-name" />

      <label for="last-name">Last Name</label>
      <input type="text" name="last-name" id="last-name" />

      <!-- more related inputs -->
    </fieldset>

    <fieldset>
      <legend>Your Purchases</legend>

      <!-- related inputs -->
    </fieldset>
    ```

- Submitting
    - `<button type="...">`
        - `submit`: submits forms
        - `reset`: clears form (generally not that useful)
        - `button`: creates a button that doesn't do anything - text is the `value` attribute

    - Or with: `<input type="...">`
        - `submit`: submits forms
        - `reset`: clears form (generally not that useful)
        - `button`: creates a button that doesn't do anything - text is the `value` attribute

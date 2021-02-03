# HTML Forms

---

#### Introduction

- Forms are for submitting data. They allow the user to interact with your website.
- This data is then processed and perhaps stored on the site's server
- Therefore we can't do everything we want to with a form just in HTML and CSS
- Even typing into Ecosia/Google search is using a form

#### Form tag

- `<form>`
- formally and semantically defines your form, like a `<section>` or `<article>`
- important attributes
    - **action**
        - defines the location (URL) where the form's collected data should be sent when it is submitted.
        - if empty defaults to same page
    - **method**
        - defines which HTTP method to send the data with
        - default is `GET`
        - also `POST`

#### Label tag

- `<label>`
- important for accessibility. Always include a label for each input.
- the `for` attribute is important as it connects the label to the `id` of the associated input
- this enables screenreaders to read the label when an input is selected

```html
<label for="firstName">First Name</label>
<input type="text" name="name" id="firstName" />
```

#### Input tag

- `<input>`
- self-closing tag
- can be nested in the label so that their association is implicit but it is best practice to still use the `for` attribute on the label

Important attributes:

- `id` - to connect to the label
- `name` - important for submitting data
- `value` - add a default value for the input
- `placeholder` - add a placeholder for the input. Better to do this than add a default value for UX purposes (don't have to delete it to type)
- `required` - makes a field required
- `type`
    - the most important attribute
    - defaults to `text`
    - lots of different types ([see MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Input))

```html
<label for="city">Country</label>
<input type="text" name="city" id="city" placeholder="United Kingdom" value="" />
```

#### Input Types

- Text Types
    - `password`: hides input
    - `email`
    - `url`
    - `tel`

- Numbers and Dates
    - `number`
    - `range`

    ```html
    <label for="inrange">Range</label>
    <input type="range" name="rangein" id="inrange" min="0" max="10" step="1" />
    ```

    - `date`
    - `datetime-local`
    - `month`
    - `time`
    - `week`

- Checkboxes and Radio Buttons
    - `checkbox`

    ```html
    <label for="incheck">Checkbox</label>
    <input type="checkbox" name="checkin" id="incheck" checked />
    ```

    - `radio`: same name, only one can be selected

    ```html
    <div>
        <label for="inradio">Radio</label>
        <input type="radio" name="radioin" value="optone" id="inradio" /><span>Option one</span>
        <input type="radio" name="radioin" value="optwo" /><span>Option Two</span>
    </div>
    ```

- Miscellaneous types
    - `file`: for selecting files
    - `search`: rounded corners/clear field button
    - `color`
    - `hidden`: data that needs submitting but not show to user

#### Select tag

- `<select>`
- creates a dropdown menu

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

#### Textarea tag

- `<textarea>`
- not self-closing
- can enter multi-line text for eg. a comment
- uses all the same attributes as `<input>`
- however `value` goes *between* tags
- careful: *all* whitespace between tags is included

```html
<label for="message">Text Area</label>
<textarea id="message" name="message"></textarea>
```

#### Fieldset & Legends

- `<fieldset>` and `<legend>`
- For grouping inputs that are related
- Great for custom styling and for disabling a group of inputs at once
- do not have to be nested inside the form element if `form` attribute is used

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

#### Submitting

You can submit using either a `<button>` or an `<input>`
- various `type` attributes to be aware of apply to both
    - `submit`: submits forms according to `action` attribute on form element
    - `reset`: clears form (generally not that useful)
    - `button`: creates a button that doesn't do anything - great for custom functionality

If using an `<input>` you can use the `value` attribute to add custom button text.
# HTML Forms

---

- Concept
    - Submitting data
- Limitations of HTML & CSS:
    - Need server-side code or JS
- The Form tag
    - action
        - empty (same page)
        - different URL
    - method
        - `POST`
        - `GET`
- Input & labels
    - name: used server-side as key of the value
    - `<label>`: accessibility
    - id: for label

    ```html
    <label for="intext">First Name</label>
    <input type="text" name="textin" id="intext" />
    ```

    - value: default values

    ```html
    <label for="city">Country</label>
    <input type="text" name="city" id="city" value="United Kingdom" />
    ```

    - `placeholder`
        - gives example input/more info
        - better then pre-populating value (bad UX to have to delete it)

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

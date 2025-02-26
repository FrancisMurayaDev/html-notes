# HTML Forms

- used to collect user input.
- The user input is sent to a server for processing.

- Forms are created using the `<form> </form>` tag.

```html
<form>
  <!--Form Elements Go here-->
</form>
```

## HTML form Elements

### 1. `<input>` element.

- Create a field for users to input data.
- It has `type` attribute which defines the type of input.

```html
<form>
  <p>What is your name</p>
  <input type="text" />
</form>
```

<form>
    <p>What is your name</p>
    <input type="text">
</form>

### 2. `<label></label>` element.

- Defines the label for an input element.
- When a user clicks on a label associated with an input, the input get focused.
- For this to work, the label has a `for` attribute which we pass a value, to the associated input, we pass an `id` value matching that of the label `for` attribute.

```html
<form>
  <label for="first-name">first name</label>
  <input type="text" id="first-name" />

  <label for="lastname">last name</label>
  <input type="text" id="lastname" />
</form>
```

<form>
    <label for="first-name">first name</label>
    <input type="text" id="first-name">

<label for="lastname">last name</label>
<input type="text" id="lastname">

</form>

### 3. `<select></select>` Element

Used to create a drop-down list.

Used together with `<option></option>` elements to define the options available.

```html
<form>
  <label for="county">Select your county:</label>
  <select id="county">
    <option>Nairobi</option>
    <option>Nakuru</option>
    <option>Mombasa</option>
    <option>Eldoret</option>
    <option>Kirinyaga</option>
    <option>Murang'a</option>
  </select>
</form>
```

<form>
    <label for="county">Select your county:</label>
    <select id="county">
        <option>Nairobi</option>
        <option>Nakuru</option>
        <option>Mombasa</option>
        <option>Eldoret</option>
        <option>Kirinyaga</option>
        <option>Murang'a</option>
    </select>
</form>

### 4. `<textarea></textarea>` element

Used for multiline text input.

- Allows larger text and spans multiple lines.

```html
<form>
  <label for="about-user">Tell us about yourself:</label>
  <textarea id="about-user"></textarea>
</form>
```

<form>
    <label for="about-user">Tell us about yourself:</label>
    <textarea id="about-user"></textarea>
</form>

### 5. `<fieldset></fieldset>` and `<legend></legend>` elements.

- Fieldset - used to group related elements. Visually groups content inside a form with border around.

- Legend element - defines the caption for the fieldset.

```html
<form>
  <fieldset>
    <legend>Personal information</legend>
    <label for="firstname">first name</label>
    <input type="text" id="firstname" />
    <label for="lastname">last name</label>
    <input type="text" id="lastname" />
  </fieldset>
  <fieldset>
    <legend>next of kin information</legend>
    <label for="fullname">full name</label>
    <input type="text" id="fullname" />
    <label for="school">school</label>
    <input type="text" id="school" />
  </fieldset>
</form>
```

<form>
    <fieldset>
        <legend>Personal information</legend>
        <label for="firstname">first name</label>
        <input type="text" id="firstname">
        <label for="lastname">last name</label>
        <input type="text" id="lastname">
    </fieldset>
    <fieldset>
      <legend>next of kin information</legend>
        <label for="fullname">full name</label>
        <input type="text" id="fullname">
        <label for="school">school</label>
        <input type="text" id="school">
    </fieldset>
</form>

### 6. `<datalist></datalist>` element.

- Provide a list of predefined options of an input element. 
- Allows users to either type a value or select a value from a list. 

```html
<label for="browser">what browser do you use:</label>
<input list="browsers" id="browser">
<datalist id="browsers">
    <option value="Chrome">
    <option value="Firefox">
    <option value="Safari">
    <option value="Edge">
</datalist>
```

<label for="browser">what browser do you use:</label>
<input list="browsers" id="browser">
<datalist id="browsers">
    <option value="Chrome">
    <option value="Firefox">
    <option value="Safari">
    <option value="Edge">
</datalist>
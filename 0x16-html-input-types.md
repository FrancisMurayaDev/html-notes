# HTML Form Input Types

HTML has different types for the input element.

These types are defined using the type attribute.

- They are:

## 1. Input Type Text `type="text"`

defines a single line text input field.

```html
<form>
  <label for="fname">first name</label>
  <input type="text" id="fname" />
</form>
```

<form>
    <label for="fname">first name</label>
    <input type="text" id="fname">
</form>

## 2. Input Type Number `type="number"`

Defines a number input field.

```html
<form>
  <label for="age">What is your age:</label>
  <input type="number" id="age" />
</form>
```

<form>
    <label for="age">What is your age:</label>
    <input type="number" id="age">
</form>

## 3. Input Type Email `type="email"`

Used for input types that should contain an email.

Depending on browser support, the email is automatically validated when submitted.

## 4. Input Type Password `type="password"`

Defines password field.
The browser will type what the user is typing with bullets or any other symbol.

```html
<form>
  <label for="password">type a password</label>
  <input type="password" id="password" />
</form>
```

<form>
    <label for="password">type a password</label>
    <input type="password" id="password">
</form>

## 5. Input Type Checkbox `type="checkbox"`

- Allow the user to select zero or more options of the provided choices.

```html
<form>
  <p>What languages do you program in:</p>

  <label for="python">python</label>
  <input type="checkbox" id="python" />

  <label for="javascript">javascript</label>
  <input type="checkbox" id="javascript" />

  <label for="C">C</label>
  <input type="checkbox" id="C" />

  <label for="c++">c++</label>
  <input type="checkbox" id="c++" />

  <label for="go">go</label>
  <input type="checkbox" id="go" />
</form>
```

## 6. Input Type Color `<input type="color"`

Used for color input, a color picker is shown in the input field.

```html
<form>
  <label for="favcolor">Select your favorite color:</label>
  <input type="color" id="favcolor" />
</form>
```

## 7. Input Type Date

Used for date input.

A date picker is displayed in the input field.

```html
<form>
  <label for="birthday">Birthday:</label>
  <input type="date" id="birthday" />
</form>
```

## 8. Input Type Time `type="time"`

Used for time input.

A time picker is displayed in the input field.

```html
<form>
    <label for="checkin">What is the checkin time:</label>
    <input type="time" id="checkin">
</form>
```
## 9. Input Type File  `type="file"`

Define a file select field for file uploads. 

```html
<form>
    <label for="profile-picture">Upload profile picture:</label>
    <input type="file" id="profile-picture">
</form>
```


## Input Restrictions

1. required - Specifies that the input field must be filled out

2. checked - Specifies that the input should be pre-selected when the page loads.

3. disabled - Specifies that the input should be disabled.

4. max - Specifies the maximum value for a number input field

5. min - Specifies the minimum value for a number input field.

6. maxlength - Specifies the maximum number of characters for an input field.

7. readonly - Specifies that the input field is readonly (cannot be changed).

## Input Attributes 

1. placeholder - Specifies a short hint that describes the expected value of an input field.

2. autofocus - Specifies that the input field should automatically get focus when the page loads.


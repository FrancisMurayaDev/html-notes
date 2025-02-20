# Lists

Used to group relatable items, presenting them in a structured format.

Lists are essential for organizing contents such as:

- Menus
- Navigation Links
- Grouped Data

There are 3 types of Lists:

## 1. Ordered Lists
 - Used to display items where order is important.
 - Items will appear numbered or lettered.
Ordered lists are defined using `<ol> </ol>` where `<li> <li>` tags are nested inside.

```html
<p>Here is a list of my favorite fruits:</p>
<ol>
    <li>Apples</li>
    <li>Oranges</li>
    <li>Bananas</li>
    <li>Pineapple</li>
</ol>
```


## 2. Unordered Lists

- Display a list of items where the order does not matter.
- Items appear bulleted. 

defined using `<ul> </ul>` with `<li></li>` tags nested inside.

```html
<p>Here is a list of my favorite fruits:</p>
<ul>
    <li>Apples</li>
    <li>Oranges</li>
    <li>Bananas</li>
    <li>Pineapple</li>
</ul>
```

## 3. Descriptive Lists

Description lists are used to describe a list of terms with their corresponding descriptions.

Defined using `<dl></dl>` tags, inside we nest `<dt></dt>` tags for the term and `<dd></dd>` for description.

```html
<dl>
    <dt>HTML</dt>
    <dd>The language that defines the structure of our webpages</dd>
    <dt>CSS</dt>
    <dd>The language that styles our webpages</dd>
    <dt>JavaScript</dt>
    <dd>The language that adds functionality to our webpages</dd>
</dl>
```


Lists are also Nested.



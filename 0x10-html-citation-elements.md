Elements specifically for:
- Providing citations
- Abbreviating words
- Defining contact information
- Handling bidirectional text

1. `<blockquote></blockquote>` for block quotations.
Represents a section that has been quoted from another source of text.

Displayed as a block of text that is indented from the rest of the content.

```html
<p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci, quibusdam necessitatibus suscipit nisi expedita ex consequatur!
    Corporis, architecto iusto? Labore.
</p>
<blockquote cite="https://www.example.com/">
    This is a blockquote. It is typically used for longer quotations.
</blockquote>
<p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis laborum harum error sint dolores provident
    deleniti beatae magni ipsum voluptates?
</p>
```

<p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci, quibusdam necessitatibus suscipit nisi expedita ex consequatur!
    Corporis, architecto iusto? Labore.
</p>
<blockquote cite="https://www.example.com/">
    This is a blockquote. It is typically used for longer quotations.
</blockquote>
<p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis laborum harum error sint dolores provident
    deleniti beatae magni ipsum voluptates?
</p>

2. `<q></q> for inline quotes`
```html
<p>
    As the saying goes,
    <q cite="https://www.example.com">Actions speak louder than words</q>
    so we decided to do something
</p>
```

<p>
    As the saying goes,
    <q cite="https://www.example.com">Actions speak louder than words</q>
    so we decided to do something
</p>


3. `<abbr></abbr> for abbreviations`
```html
<p>
    The project repository <abbr title="Looks good to me">LGTM!</abbr>
</p>
```

<p>
    The project repository <abbr title="Looks good to me">LGTM!</abbr>
</p>

4. `<address></address>` for contact information.

```html
<p>Here's how you can reach us:</p>
<address>
    Send us an email to: info@company.com
</address>
<address>
    Call us: +254723190821
</address>

```
<p>Here's how you can reach us:</p>
<address>
    Send us an email to: info@company.com
</address>
<address>
    Call us: +254723190821
</address>


5. `<cite></cite>` for citations

Represents the title of a work (such as a book, article, movie, etc.) or a reference to a source.

```html
<p>One of my favorite books is <cite>Atomic Habits</cite> by James Clear.</p>
```

<p>One of my favorite books is <cite>Atomic Habits</cite> by James Clear.</p>


6. `<bdo></bdo>` for overriding text direction

Overrides the current text direction, allowing you to change the direction of text display from left-to-right (LTR) to right-to-left (RTL), or vice versa.

```html
<p>
    The word
    <bdo dir="rtl">Hello world!</bdo>
    is displayed in reverse and it is Hello world!
</p>
```

<p>
    The word
    <bdo dir="rtl">Hello world!</bdo>
    is displayed in reverse and it is Hello world!
</p>




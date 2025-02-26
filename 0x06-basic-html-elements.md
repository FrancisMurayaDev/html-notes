# Basic HTML Elements

## 1. Heading Element

Defined with `<h1>` upto `</h6>`tags.

```html
 <h1>This is heading 1</h1>
  <h2>This is heading 2</h2>
  <h3>This is Heading 3</h3>
  <h4>This is heading 4</h4>
  <h5>This is heading 5</h5>
  <h6>This is heading 6</h6>
  ```

  ## 2. Paragraph Element

  Defined with the `<p>` tag.


  ```html
  <p>This is a Paragraph</p>

    <p>What is HTML</p>

    <p>
      HTML, or HyperText Markup Language, is the standard language used to
      create and design web pages. It defines the structure and layout of a web
      page by using a variety of elements and tags.
    </p>

```
## 3. Links
 Links are defined with the anchor `<a></a>` tag.

 - Allows navigation from one page to another.
 - Navigation from one section of a webpage to another.

 The `href=""` attribute specifies specifies the destination link.

 ```html
 <a href="https://www.google.com/">Visit google</a>
<a href="https://www.facebook.com">Open facebook</a>
```

If we want the pages to open on a new tab, we add an attribute called `target` and set it to `_blank`

```html
<a href="https://www.google.com/" target="_blank">Visit google</a>
<a href="https://www.facebook.com" target="_blank">Open facebook</a>
```

## 4. Images
We add images in HTML by passing the `<img>` tag. It is a self closing tag.

It takes 2 attributes:

- `src` - specifies the path to the image.

- `alt` - specifies the value to be read by screen readers. 

If an image is not loaded correctly, the alt attribute is shown in place of the image. 

```html
<img src="kid.jpg" alt="a happy kid jumping on a bright sunny day">
```

For organization structure, images should be put in one folder. 

We can also add the `height` and `width` attributes to specify the height and width of the image in pixels. 

```html
<img src="./images/kid.jpg" width="240px" height="240px"
     alt="a happy kid jumping on a bright sunny day">
```
Specifying the `width` only makes the work easier.

## 5. Comments

A html comment is a piece of code ignored by the browser, it is not visually presented.

To write a comment we open `<!--` and we close with `-->`.
Shortcut for comments is:

`CTRL + /` KEY.
```html
<!-- This is a comment -->
 ```


 

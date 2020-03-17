# CSS Syntax

[![](/assets/css-syntax.gif)](https://www.w3schools.com/whatis/whatis_css.asp)

* Above is an example of the syntax to decorate `h1` Html tag and it will be applied to all `h1` elements
* It is called _**CSS Element Selector**_: an instruction to apply the style to tags based on their element name
* A different approach is to define a CSS class and to reference it explicitly
* ```
  CSS:
  .centeredHeader {
    color: green;
    font-size: 20pxl;
    margin: auto
  }

  Html:
  <h2 class="centeredHeader">The Cradle of Humankind</h2>
  ```
* It is the so-called _**CSS Class Selector**_ that applies the style on tags that specifically reference the class name
* Another approach is a style that applies the to any element that uses attribute id equal to the style class name:
* ```
  CSS:
  #italicText {
    color: red;
  }

  Html:
  <p id="italicText">A text rendered italic</p>
  ```
* This is the so-called _**CSS id Selector **_that applies the style based on the `id` attribute value
* There are more [CSS selectors](https://www.w3schools.com/css/css_selectors.asp), we will limit our quest to the three above for now...



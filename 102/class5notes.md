
# Class 5 Notes

## What is CSS

Source: [https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

* CSS = Cascading Style Sheets; allows you to control how HTML elements look in a browser

* It can be used for basic text styling like color, size, layout, and effects like animation.

* Example

'h1 {
    color: red;
    font-size: 5em;
}'

    - h1 is the selector - the element to be styled
    - then curly braces {}
    - inside the braces are declarations 
        1. form is property and value in pairs
        2. example, property is color and value is red
    - This example has two declarations: color and font-size

* CSS components are broken down into modules (ex. backgrounds and borders)

* CSS Specifications are developed by the CSS Working Group within the W3C

* Not all browsers have CSS implemented as a feature, so you will need to check implementation status


## How to Add CSS

Source: [https://www.w3schools.com/css/css_howto.asp](https://www.w3schools.com/css/css_howto.asp)

* There are 3 ways to insert a style sheet
    1. external css
    2. internal css
    3. inline css

1. External CSS
    * Changes the look of a site by changing one file
    * defined within the <link> element, inside the <head> section of HTML
    * ex. <link rel="stylesheet" href="mystyle.css">
    * can be written in any text editor, and must be saved with .css extension
    * external .css file shouldn't have HTML tags

2. Internal CSS
    * can be used if one single HTML page has a unique style
    * defined inside the <style> element, inside the head section

3. Inline CSS
    * used to apply a unique style for a single element
    * add the style attribute to the relevant element; style attribute can contain any CSS property

* Multiple Style Sheets: if some properties have been defined for the same selctor/element in different style sheets, the value from the last read style sheet will be used.

* Cascading Order: with more than one style specified for an HTML element, the following rules will apply:
    1. Inline style - inside HTML element
    2. External and internal style sheets (in the head section)
    3. Browser default


## CSS Color

Source: 
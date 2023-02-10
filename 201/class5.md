# 201 class 5 notes


**Why this matters**: This information matters because it includes important information about accessibility in web development, and includes more details about media features of HTML and CSS features.

------------------------------------

## HTML Media

Source: [https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

Source:[https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)

Source: [https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format)


**1. What is a real world use case for the `alt` attribute being used in a website?**

For accessibility, for example when the user is using a screen reader.

**2. How can you improve accessibility of images in an HTML document?** 

- Using accessible link text if the image is also a link.
- Using alternative text in the <img> element with the alt attribute.
- Add a longer text description in a <div> with an id attribute and then providing a "longdesc" attribute to the <img> element, pointing to the URL of the long description. [Source](https://wishdesk.com/blog/make-images-accessible)

**3. Provide an example of when the `figure` element would be useful in an HTML document.**

- When you have an image, illustration, diagram, code snippet, etc., that is referenced in the main flow of a document, but that can be moved to another part of the document or to an appendix without affecting the main flow.

**4. Describe the difference between a `gif` image and an `svg` image, pretend you are explaining to an elder in your community.**

- A gif image allows for simple animation, where you have a series of images that change with each frame. It looks like a short video.  
- An svg image is good for when you either don't know the size of the image you're using or the size may vary, because as an SVG file, it will scale to your desired size easily.

**5. What image type would you use to display a screenshot on your website and why?**

- Lossless PNG or WebP because in order to maintain quality and keep the image from looking fuzzy, you need a lossless format. 


------------------------------------

## Learn CSS

Source: [https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)

Source: [https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

**1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.**

- The foreground color will be anything in the foreground of the page - usually text, so the color of the text.
- The background color is the color of the background of the page.

- <color> property sets the color of the foreground content, usually text.
- <background-color> defines the background color. 

**2 Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?**

- To keep it simple, I'd add color to the background of the various sections of the page with 'background-color', color to the text using 'color' and color to areas like 'border' and 'margin' to create separation. I'd research accessible color palettes for greater accessibility - for example: [this page](https://venngage.com/tools/accessible-color-palette-generator)

**3. What should you consider when choosing fonts for an HTML document?**

- One important thing to consider is font availability - there's only a certain number of fonts available across all systems: "web safe fonts."

**4. What do `font-size`, `font-weight`, and `font-style` do to HTML text elements?**

- `font-size` sets the size of the font, and is inherited from a given element's parent element, which starts with the root element <html>, in which the default is 16px.

- `font-weight` sets how bold the text is. Some options are normal, bold, lighter, bolder, and numaric boldness values 100-900.

- `font-style` is used to turn italic text on or off. Options are normal, italic, or oblique.

**5. Describe two ways you could add spacing around the characters displayed in an `h1` element.**

- `letter-spacing` - will allow for variety in spacing between the letters in the text of the `h1`.

- `word-spacing` - will allow for variety in spacing between the words in the text of the `h1`.


------------------------------------
### Things I Want To Know More About:
Nothing at the moment!

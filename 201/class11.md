# 201 class 11 notes

**Why this matters**: This information matters because 

------------------------------------

## Video and Audio Content

Source:[https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

**1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.**

Initially, Flash and Silverlight (proprietary, plugin-based technologies) were the tools used to bring videos and audio online. They have been replaced over time because of security and accessibilty issues, with native HTML solutionas `<video>` and    `<audio>`and the ability of JavaScript APIs to controll these elements.

**2. Describe the use of the `src` and `controls` attributes in the `<video>` element.**

- The `src` source attribute contains the path to the video you want to embed. It works the same way as with <img> elements.

- The `controls` attribute  allows users to control video and audio playback (which is especially critical for people with epilepsy). You can either use the attribute to include the browser's own control interface, or you can build your own interface using JavaScript API. The minimum functionality the interface must include is a way to stop and start the media and to control the volume.


**3. Why is it important to have fallback content inside the `<video>` element?**

- Incase the browser accessing the page doesn't support the `video` element, fallback content can be displayed for older browsers.

**4. Write a very short story where `<audio>` and `<video>` are characters.**

Once upon a time, there were two elements who fell in love, though they came from different worlds. They decided to become parents, and their child was - of course - the world famous Beyoncé, who is the Queen of both of these media.[Source](https://badassyonce.wixsite.com/website) Just wait for the Renaissance visuals!


-----------------------

## A Complete Guide to Grid

Source: [https://css-tricks.com/snippets/css/complete-guide-grid/](https://css-tricks.com/snippets/css/complete-guide-grid/)

**1. How does Grid layout differ from Flex?**

Flexbox is one-directional/one-dimensional, whereas Grid is two dimensional.


**2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**

- Grid container: is the element on which `display: grid` is applied. It's the direct parent of all grid items.


- Grid items: are the direct descendants (children) of the grid container.


- Grid lines: are the dividing lines that make up the structure of the grid. They can be either vertical (as 'column grid lines') or horizontal (as 'row grid lines') and they reside on either side of a row or column.


------------------------

## Responsive Images

Source: [https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**

- bandwidth: mobile users don't want to waste bandwidth by downloading a large image intended for desktops when a small image would suffice.

- Raster images look grainy when displayed larger than their original size and high resolution screens need larger images to display nicely.

- On mobile, non-responsive images could take up too much space on the page and/or don't allow the user to actually see what's going on in the image properly.

**2. Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.**

- `srcset` defines the set of images the browser will be able to choose between and the size of each image. Each set of image information is separated by a comma and comes in the formula `image file name + space + image's intrinsic width in pixels`. For example: "elva-fairy-480w.jpg 480w, elva-fairy-800w.jpg 800w"

- `sizes` defines the set of media conditions (for example, screen widths) and indicates what image size is the best to choose, whenever certain media conditions are true. It comes as `media condition + space + width of the slot`. For example: "(max-width:600px) 480px, 800px"


**3. How is `srcset` more helpful for responsive images than CSS or JavaScript?**

- It saves bandwidth. Since browsers preload images before the parser loads or interprets CSS and JS, it woulnd't make sense to preload a large image that then gets adjusted or replaced in the CSS/JS stages.


------------------------------------
### Things I Want To Know More About:
Nothing at the moment!
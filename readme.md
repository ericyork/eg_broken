# THANK YOU FOR DOING THIS!
I've laid out everything you need to know to finish this project. Aside from *readme.md* (this file), there's an image of what the finished version of the page should look like (without color) named mockup.png——you might want to look at that first so you know what you're shooting for!

This file contains a list of all the tasks that remain, in basically the same order as they appear in the source code, so all you need to do is start at the top and work your way down. Remember that Google is your friend :)

## In /index.html
+ The page needs a better title. Think of one and change it to that.

+ The stylesheet needs to be hooked up to the page. In the head section, add a link to our external stylesheet: it's named style.css and it's located inside the /css folder.

+ One image still needs to be added. Inside the article element, there's a figure without an image. Add an image element that links to the dodo.jpg file inside the /img folder. Don't forget to use the alt attribute!

## In /css/style.css
+ Set the default font on the body to 'Gentium Book Basic' with a fallback to serif, so it will be inherited by the rest of the elements.

+ Use flex display to lay out the main menu in a horizontal row and use justify-content to distribute the links as space-between.

+ Use left and right auto margin to center both the header and article sections horizontally on the page.

+ Horizontally center the header h1 elements and use the font and text-transform properties to visually distinguish class .small from the other h1. Try to set it to 900-weight, Lato font (with a sans-serif fallback), in all caps. It should probably also be smaller in size.

+ Use float to position the article figure on the right-hand side of the text.

+ Use font to style the figcaption so that the size is smaller and the font is lighter-weight and visually distinct (a different font-family) from the body text.

+ Use auto margins, flex display, and justify-content to evenly distribute (space-evenly) the pagination buttons at the bottom of the page.

+ Add your name to the footer copyright.

+ Style the page with a suitable color scheme, either light or dark, so it doesn't look so plain. Consider using color for: navigation-bar background and text, footer background and text, page background, header background, body text, and pagination buttons, both normal and on hover.

## Bonus
I wrapped a span with the .dropcap class around the first letter of the article in /index.html, but never wrote the css for it. If you can, please use it to create a drop-cap effect (A big first letter at the start of the paragraph).

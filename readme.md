# THANK YOU FOR DOING THIS!
I've laid out everything you need to know to finish this project. Aside from *readme.md* (this file), there's an image of what the finished version of the page should look like (without color) named mockup.png——you might want to look at that first so you know what you're shooting for (and to start thinking about your color sheme).

This file contains a list of all the tasks that remain, in basically the same order as they appear in the source code, so all you need to do is start at the top and work your way down. Feel free to use any means at your disposal to solve the problems. This isn't a test, it's a learning experience.

## Troubleshooting
Your page will likely get messed up at some point. Here are some strategies that can help. 
+ **Save often**. Saving and committing changes often is the best way to get out of trouble: just revert to your most recent version.
+ **Use the Inspector**. Your browsers dev tools will have an [Inspector](https://firefox-source-docs.mozilla.org/devtools-user/page_inspector/how_to/open_the_inspector/index.html). Learn to use this important tool! It might look intimidating but you don't need to use all of it, just some of it. Being able to look at HTML and it's corresponding CSS is enough for now.
+ **Perform Debugging**. You can use debugging strategies (for [HTML](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Debugging_HTML) and [CSS](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Debugging_CSS) to solve issues. Steps typically include: 1) Proofread your code (especially punctuation!). 2) Use an HTML or CSS validator. 3) Isolate the problem code. 4) Compare to working versions. 5) Ask someone (including a forum or AI).

## In /index.html 
+ The page needs a real [page title](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title). Think of one and change the page title from eg_broken to that. Note: this is ***not*** the file name!

+ Another stylesheet needs to be linked to the index.html page. In the head section (the area between the opening <head> and closing </head> tags), add a link to the style.css stylesheet. You will use the [<link> tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link) and set the [href attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link#href) to point to the style.css file that's located inside the /css folder. You can build your link just like the one that's already in the <head> section, pointing to the CSS reset styles (in the modern-normalize.css file).

+ One image still needs to be added. Inside the article element, there's a figure without an image. Inside the [figure element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure), add an [image element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img) that links to the dodo.jpg file inside the /img folder. Don't forget to use the [alt attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#attributes) and make sure the file path is correct. Again, you can use the browser's inspector to check.

## In /css/style.css
+ Change the default font on the body from Arial to 'Gentium Book Plus' (with a fallback to serif), so it will be inherited by the rest of the elements. You should do this by selecting the body element and using the [font](https://developer.mozilla.org/en-US/docs/Web/CSS/font) or [font-family](https://developer.mozilla.org/en-US/docs/Web/CSS/font-family) properties.

+ Use the [display property](https://developer.mozilla.org/en-US/docs/Web/CSS/display) to set the display of the [nav element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav) to [flex](https://developer.mozilla.org/en-US/docs/Web/CSS/flex) to lay out the main menu in a horizontal row, and use the [justify-content property](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content) to distribute the links with [space-between](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content#space-between).

+ There's a weird bit of extra space above the nav, preventing the nav from being flush with the top of the browser window. Find out where that space is coming from and get rid of it. (Hint: use the browser's inspector and the layout panel to view box model of each element, starting at the top and moving down).

+ Use left and right [margin: auto](https://developer.mozilla.org/en-US/docs/Web/CSS/margin#more_examples) to center both the [header element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header) and [article elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article) horizontally on the page.

+ Horizontally center the header [h1 elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements) and use the font and text-transform properties to visually distinguish elements with the .small class from the other h1. Set it to 900-weight, Lato font (with a sans-serif fallback), in all caps. And make it noticeably smaller in size (but not too small).
 
+ Use the float property to position the article figure on the right-hand side of the text.

+ Use the font property to style the figcaption so that the size is smaller and the font is lighter-weight and visually distinct (a different font-family) from the body text. Remember, for any font to load, it has to be one the user has on their computer or it has to be linked in the HTML or loaded from somewhere.

+ Use auto margins, flex display, and justify-content to evenly distribute (space-evenly) the pagination buttons at the bottom of the page. You might also style the border of the buttons to be thicker or thinner, or have another appearance as you wish.

+ Add your name to the footer copyright.

+ Style the page with a suitable color scheme, either light or dark, so it doesn't look so plain. Consider using color for: navigation-bar background and text, footer background and text, page background, header background, body text, and pagination buttons, both normal and on hover.

## One more thing
+ I wrapped a span with the .dropcap class around the first letter of the article in /index.html, but never wrote the css for it. If you can, please use it to create a drop-cap effect (A big first letter at the start of the paragraph).

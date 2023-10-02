# Front End Bootcamp - Week 1 Code Refactor Challenge

## Description

The purpose of this project was to refactor a marketing website's existing sites code in order to make it more accessible for people using assistive technologies, whilst at the same time improving search engine optimisation. This widens the potential audience for the site and ensures nobody is left out from being able visit. As a bonus, it may also increase the amount of traffic to the site and have a positive impact on business.

The aim was to use semantic HTML5 elements and add `alt` attributes to all images and icons to describe their content, as well as optimising the structure of the code to make it more logical and sequential for those using technologies such as screen readers. 

In doing this I unconvered some inefficient and broken code, such as links not working, multiple CSS selectors for elements with identical style properties and heading attributes out of sequence. Many of the elements on the page were inside `<div>` containers, these are not semantic don't provide structural information for people with accessibility needs.

This project has enabled me to learn more about semantic HTML, further my CSS and Git knowledge, as well as the requirements and standards for those with accessibility needs. In my reading, I learned about ARIA landmarks to help assistive technology users navigate easily to various sections of a page and was able to implement these in my code. I also added comments to all CSS selectors and sections of HTML to ease future development of the site, which required me to read further to fully understand the code.

## Installation

N/A

## Usage

To use this web page, you can open index.html inside a browser. To see the refactored code, open the DevTools by pressing Command+Option+I (macOS) or Control+Shift+I (Windows). A console panel should open either below or to the side of the webpage in the browser. There you will see the refactored HTML and CSS code along with comments.

## Screenshot

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](assets/images/screenshot.png)

## Credits
### External Tutorials and Resources
* [Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp)
* [HTML Accessibility](https://www.w3schools.com/html/html_accessibility.asp)
* [Image `alt` attributes](https://www.w3schools.com/tags/att_img_alt.asp)
* [Making background images accessible (Stack Overflow answer)](https://stackoverflow.com/questions/48913759/how-to-add-alt-text-to-background-images-making-background-images-accessible/#48913760)
* [Using Using ARIA landmarks to identify regions of a page](https://www.w3.org/WAI/WCAG21/Techniques/aria/ARIA11)
* [DEV 1.10 – Provide native HTML 5 for elements and ARIA for landmarks](https://universaldesign.ie/technology-ict/web-accessibility-techniques1/developer-s-introduction-and-index/dev-1-provide-an-accessible-page-structure-and-layout/dev-1-10-%E2%80%93-provide-native-html-5-for-elements-and-aria-for-landmarks/)
* [Using HTML5 section element](https://www.w3.org/WAI/GL/wiki/Using_HTML5_section_element)
* [CSS Selector Reference](https://www.w3schools.com/cssref/css_selectors.php)


## License

MIT - See LICENSE file in repo.
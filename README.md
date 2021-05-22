# CWRU Cooding Bootcamp Challenge 1
##PURPOSE: Code Refactor Code to meet accessibility standards so the site is optimized for search engines.

## A marketing agency:
Wants a codebase that follows accessibility standards so the site is optimized for search engines

##Acceptance Criteria is as follows:

1. WHEN I view the source code
1.1 THEN I find semantic HTML elements
1.1.2 Action: Update and add semantic HTML elements if not present or incorrect
1.1.3 Ref: https://www.w3schools.com/html/html5_semantic_elements.asp
1.1.4 Ref: https://www.w3schools.com/html/html_accessibility.asp

2. WHEN I view the structure of the HTML elements
2.1 THEN I find that the elements follow a logical structure independent of styling and positioning
1.1.1 Action: Update HTML format and flow to ensure a logical structure
1.1.2 Ref: https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure
1.1.3 Ref: https://www.w3docs.com/snippets/html/html5-page-structure.html
 
3. WHEN I view the image elements
3.1 THEN I find accessible alt attributes
3.1.1 Action: Review all images and add or update atl tags with accessibility readers in mind and so images become indexable by search engines
3.1.2 Ref: https://www.w3.org/WAI/tutorials/images/
 
4. WHEN I view the heading attributes
4.1 THEN they fall in sequential order
4.1.1 Action: Review heading attributes update or change to ensure they fall in sequential order
4.1.2 Ref: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements
4.1.3 Ref: https://www.w3schools.com/html/html_headings.asp

5. WHEN I view the title element
5.1 THEN I find a concise, descriptive title
5.1.1 Action: Ensure title element has a  concise, descriptive title that describes the page's purpose for accessibility readers
5.1.2 Ref: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title#accessibility_concerns


Change log:
1 - Updated Title
2 - replaced div were semantic HTML elements exist
2.1 - header, nav, section for class=content, aside for class=benefits, footer
3 - Shift-Alt-F to reformt code - to easily ensure proper indention 
4 - Put loose hero div into a section
5 - update CSS to reapply formatting, styles to referece new semantic HTML elements in nav
6 - change h2 footer to h3 and updated CSS to reference h3 instead of h2
7 - fix broken link to "search-engine-optimization" by adding id=
8 - added blank line between sections in body for readibility
9 - added alt="" to visual decoration images to left aside section / benefits class
10 - decided to change divs in content section and aside section into article elements for readibility
11 - add aira lable to hero background image (ref:https://www.davidmacd.com/blog/alternate-text-for-css-background-images.html)
12 - add alt test to content article images
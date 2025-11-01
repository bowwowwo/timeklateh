Assignment Specification

    Download an archive containing an HTML document and an empty stylesheet from the assignment. It already includes a reference to a stylesheet, your homework should go into "style.css". Fill your first name, last name and student ID number in the comment in style.css. If this information is missing in submitted style.css, the grade for the homework will be reduced.
    Fill style.css with CSS rules that define the style of the given HTML document. The result should look as similar as possible to the screenshot available in the folder “screenshots” in the homework archive. The screen recording of the web page is available in the file “screen recording.mp4”. It demonstrates the dynamic elements of the page. The screenshot and screen recording were made with Chrome, screen resolution 1920x1080 without screen scaling.
    Submit only style.css file. Do not make any changes to the original html document. Before submission, validate the stylesheet in CSS validator: http://jigsaw.w3.org/css-validator/

Information about the styles

Some additional information about the styles of elements used follows. These are not the only properties that you should set, others can be identified without explanation.

General information

    The minimal width of the whole page is 600px. Maximal width is not limited.
    Two fonts are used to style the web page: Spectral and Chivo. These both are Google Web fonts (don’t forget to provide alternative fonts). Add the necessary @font-face or @import directive to your CSS to use Google fonts. Spectral is the main font. Chivo is used for headings, buttons, links and placeholder text in the search bar on top (use ::placeholder pseudo-element to define a selector for placeholder text).
    Determine the size of the font as similar to the provided screenshot as possible.
    The color of most texts is #333 or white. The color of drop-down menu items is #555. The color of the text in the footer is #aaa.
    The background colors used are #f2f2f2, white (for events section and drop-down menu items), #222 (for bottom section), black (for footer) and #7acb95 for links looking like buttons.
    The image concert-image.jpg should be used as a background of home-banner section. The div element with class background-overlay should cover the background image and should have background color rgba(0, 0, 0, 0.6).
    You should use display: flex or grid to split content into columns. Try to make columns wrap when the browser window becomes too narrow.
    Use position:absolute/relative combination to place background overlay and texts on the home-banner section.
    Use position:sticky for the header.
    Use cursor: pointer for all links.
    All images used in the document are in the folder “images”.
    Font awesome (https://fontawesome.com/) icons are used for social media icons. The link to font awesome CSS stylesheet is inserted in HTML.
    Pay attention to width and border radius of all borders used.
    For all elements of the page, pay attention to the case of letters.

User interaction

The screen recording in the file “screen recording.mp4” demonstrates changes to elements that occur when a user points a mouse cursor over them and when the window is resized:

    When a user points a mouse cursor over top menu items, the menu item changes text color to #7acb95 and the submenu becomes visible (https://www.w3schools.com/css/css_dropdowns.asp). Pay attention to border radius and shadow of the dropdown menu and bottom border of the sub-menu items.
    When a user points a mouse cursor over sub menu items, they change text color to white and background color to #7acb95.
    When a user points a mouse cursor over links in the bottom, they change text color to #7acb95.
    When a user points a mouse cursor over green buttons, they change background color to #63b87e.
    When a user points a mouse cursor over the event cards, they move up 5px (use translateY property for that) and their shadow becomes darker.
    Use 0.3 seconds transition for all the mentioned state changes.
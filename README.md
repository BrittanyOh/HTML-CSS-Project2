# HTML-CSS-Project2
Network &amp; Web Programming assignment to test understanding of basic HTML and CSS

CSCI 452/553: Network and Web Programming
HTML & CSS Assignment
------------------------------------------------------------------------------------------------
This assignment tests your understanding of basic HTML and CSS. You will create several files related to a recipe
web site for a fictional pie company named Granny's Pies. Create the following files:
<br> • index.html, the first of two web pages (with an optional CSS style sheet file); appearance is up to you
<br> • pie.html, the second of two web pages; must match a particular specified appearance recipe.css the style sheet for pie.html For full credit, your files must be uploaded to the web and must match the guidelines in this document.

## Index Page:
<br> The first part of your task is to create a front page for this web site, stored in a file named index.html. Your front page must contain a link to pie.html . The file must also be at least <b>20 lines long and must contain at least 8 different
categories HTML elements in its body </b> (For example, \<h1> and \<h2> would be considered in the same category). It
also may not significantly borrow content from your pie.html. Otherwise, this front page can have any appearance you
like. If you like, you may use an optional CSS file with this page named index.css and submit it with your other files.
Be creative!

## Pie Recipe Page:
<br> The second part is to recreate a specific web page of a recipe for lemon meringue pie, stored in a file named
pie.html. Unlike index.html, this page must exactly match the appearance specified in this document.
You must match in appearance the pie web page shown on the next page of this document. The width of the
screenshot below is based on a browser window width of 1024px; if your screen is a different size, the width of your
page may not exactly match. (Firefox's Web Developer Toolbar add -on can help you resize your browser to any dimension; you could use 1024x768 to compare the images.) Any line breaks shown are done automatically by the browser, except ones that are
clearly much narrower than the page width, such as the line "One 9-inch pie":

## Provided Output Text:
<br> You don't need to type in all of the text of the pie web page, only the HTML tags. There is a provided text file
named out.txt in the support file that you can copy and paste into your text editor to get started. Then you can add
the appropriate HTML tags to the file and save it as your .html page.

## Appearance and Behavior Details:
<table>
<li>The pie web page's title text should be Grandma's Lemon Meringue Pie .
<li>All headings on the page should use a foreground color of #A4A400 (red=164, green=164, blue=0) and a
background color of #F0F0F0 (red=240, green=240, blue=240).
<li>The font families for headings are: Lucida Sans Unicode, Helvetica, Arial, or any sans- serif font available on the system (in that order).
<li>The page's main heading is aligned to the center of the page body, and uses a 22pt bold font.
<li> Other headings on the page are left-aligned and appear in an 18pt normal font.
<li><b>All headings should be underlined.</b>
<li>The overall page's body should have a white background.
<li>Text in the body should have a foreground color of #404040 (red=64, green=64, blue=64) and use an 11pt font.
<li>The font families for page text are Georgia, Garamond, or any serif font available on the system.
<li>Any links on the page should use the color #A4A400 (red=164, green=164, blue=0), matching the color of the page headings.
<li> In the Ingredients list, the underlined words "tbsp" and "tsp" are abbreviations for "tablespoons" and "teaspoon"
respectively. When the user hovers the mouse over these abbreviations, the full word should appear as a tooltip.
<li>At the end of the Directions, the deleted word "cake" with a strike-out line through it is replaced by the word "pie".
<li>After the Links section there is a short copyright notice that appears as a section of pre-formatted text in a
monospace font. The text is spaced such that the last letter lines up on horizontally for each of the three lines.

## Appearance and Behavior Details (continued):
<br> The names of the four major steps of the recipe directions (such as "Preheat Oven") are strongly emphasized. The
quotations from the users appear in an italic font as indented blocks with background color #FFFFA8 (red=255,
green=255, blue=168). Some words in the last quote are bolded for emphasis.
<br> The picture of the pie and the W3C validator images at the bottom come from the following images, respectively:
<br>• pie.jpg (use an absolute URL to link to this image; don't link to a relative URL on your hard drive)
<br>• w3c-html.png
<br>• w3c-css.png
<br> The page bottom has four links. The "Home" link should go to your index.html page. Use a relative URL and assume
it is located on the same site and directory as pie.html. The "Search for other lemon meringue pie recipes" text, "W3C
HTML5" button, and "W3C CSS" button should link to the following web pages, respectively:
• http://www.google.com/search?q=lemon+meringue+pie+recipe&start=10
• validate-html.php (this is our custom W3C HTML validator)
• validate-css.php (this is our custom W3C CSS validator)
<br> All other decisions about styling on the page are left to the web browser. Any styles mentioned previously that are the
same as browser defaults do not have to be explicitly included in your CSS style sheet. The screenshot in this document
was taken on Windows XP using Firefox, which may differ from the appearance on your system.

## Extra Features:
<br> In addition to the previous required features, you must also complete the following additional requirements in your
pie page. These are features that may have not been covered in detail in lecture; you will have to explore your resources
such as your textbook, lecture slides, or online references to learn how to complete these features. If you want to
complete more than two of the extra features below, that is fine, but only two are required.
1. Background: Set the overall page to use a background image of: silverware.jpg
The image should repeat in both directions across the page and should not move when the page is scrolled.
2. Favicon: Set the page to have a "favorites icon" ("favicon"). Use: pie-icon.gif
3. Pie bullet: Set all bulleted lists of items on the page to use an image for their bullet icon rather than the
normal black circle. Use the following image: pie-icon.gif
4. Wide headings: Place 0.25em horizontal spacing between neighboring letters in all headings on the page.
5. Tight heading background: Make it so that the gray background behind the headings on the page is only
behind the text itself, not stretched across the entire width of the page. (Looks nice with extra feature #1.)
<br> As much as possible, you should implement these changes by modifying your CSS code rather than your HTML.
Some of the CSS properties necessary will not have been covered in class, so you must learn them yourself. Try using
the textbook or Google. There are some good HTML and CSS references such as the following sites:
• https://www.w3schools.com/tags/
• https://www.w3schools.com/cssref/
A screenshot of the expected output for the extra features is available at the last page.

## Implementation and Grading:
<br> For full credit, your pie.html page must pass the W3C HTML5 validator with no errors (a green bar). (Your page is fine
as long as you see the green bar and text "This document was successfully checked as HTML5!") Choose appropriate HTML tags
to match the structure of the content on the page. Do not express style information in HTML with inline styles or
presentational HTML tags such as b or font. You may not use any HTML tables in your pie.html page.
You only need to worry about your page's appearance in standards-compliant browsers such as Firefox or Chrome.
You will not be tested in Microsoft Internet Explorer or other browsers that do not comply to web standards.
Express all stylistic information on the page using CSS defined in recipe.css. For full credit, your style sheet must
successfully pass the W3C CSS validator. Part of your grade comes from expressing your CSS concisely and without
unnecessary or redundant styles. For example, if the page uses the same color or font family for multiple elements
on the page, you must group those elements into a single CSS rule, so that it would be possible to change the page's
color/font by modifying a single place in the CSS file. Outside of extra features, do not use HTML or CSS constructs
that have not been discussed in lecture or the slides, through Chapters 2-3 of the textbook.
Do not overuse HTML class and id attributes in your HTML unnecessarily. If there is already a suitable tag for
representing a given piece of content, favor the use of that tag rather than a less appropriate tag with a class or id
attached for styling purposes.

<br> Format your HTML and CSS nicely so that it is as readable as possible, similarly to the examples shown in class. Also
place a comment header in each file containing your name and section and a brief description of the assignment and
the file's contents. You must properly use whitespace and indent your HTML and CSS code following examples shown
in class. To keep line lengths manageable, do not place more than one block element on the same line or begin any
block element past the 100th character on a line. A reference solution has 135 lines of HTML and 45 lines of CSS,
though you do not need to match this exactly.
The majority of the points for this assignment will be for the pie.html and its recipe.css files. The index.html will also
be graded, but it will be worth fewer points. The main stylistic constraint on your index.html file is that it should pass
the W3C HTML5 and CSS validators. Beyond that it can contain any non-obscene content you like, even content that
uses material we have not yet learned in lecture. Please do not link to external resources (other than image files or
index.css or recipe.css) from your index.html page.
Part of your grade will also come from successfully uploading your files to the web. You should publish your web
pages on GitHub (github.io), so that it is possible to navigate to your page in a browser from anywhere.


## Submission:
• All development must be done with Github. Specifically, there must be at least one commit for every CSS
selector and every major HTML element. The Github repo must remain private before the deadline and
public after the deadline.
• Submit a single plain text file named repo.txt at
http://hucs.dynu.net/lij/courses/submit_hw.html
The text file should include only the URL of your Github repo.

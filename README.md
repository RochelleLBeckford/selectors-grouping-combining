# Practice: Creating a Webpage building upon HTML basics and understanding how to use CSS selectors and properties to bring styling with colors, fonts, sizing, layouts, and much more...

### Practce understanding CSS Grouping and Combining Selectors

-   [ ] Simple practice to gain a better understanding of the power of adding CSS Styling to a webpage and how it can make it uniquely beautiful
    -   [ ] CSS or Cascading Style Sheet, is a language that paints a website with colors, fonts, layouts, and animations.
    -   [ ] CSS is used to create stunning webpages.
    -   [ ] It can enhance the user experience, and can make a webpage unquie and stand out amongst the rest.
    -   [ ] It is absolutely beautiful to see a webpage come to life and become even more beautiful.

-   [ ] Syntax for these rules looks likee this:
    -   [ ] <img src="img/d-rule-syntax-diagram.png" width="650" alt="How the Syntax rules looks for CSS">
-   [ ] Every rule begins with a selector then followed by curly brackets { }.
    -   [ ] Inside the curly brackets, declarations are made of property:value pairs seperated by a colon.
    -   [ ] Each line will end with a semicolon ; .
    -   [ ] CSS files have as many rules as desired. Even most webpages commonly used could have several hundres of CSS rules for it.

-   [ ] CSS Selectors are used to determine which CSS elements are styled
-   [ ] The most common type of selectors is the following:
    -   [ ] Type Selectors:
        -   [ ] Selects all the matching elements on the webpage for styling
-   [ ] HTML elements can be selected by their HTML attributes
    -   [ ] Selecing an element by "class" is done by using a period ".", and can be used to style multiple elements with a matching "class" attribute
    -   [ ] Selecting an element by "id" is done by using a hashtag "#", and is used to style a single element with a matching "id" attribute.

-   [ ] Instead of selecting every element with a matching class only "div" elements that either have a class of "class-name" or an "id" of "id-name".
    -   [ ] This selection is known as "targeting"

-   [ ] CSS allows the same styling to be added to different elements
    -   [ ] When adding styling to the webpage, CSS may start to become repetitive and less readable.
    -   [ ] This is when it would be good to group styles together to avoid it
    -   [ ] This way allows for a single rule to multiple elements at once
        -   [ ] For instance:
        -   [ ] <img src="img/b-grouping.png" alt="An example of how to group elements to avoid repetative styling">
    -   [ ] There is a way to get more specific by using the ">" symbol to select child elements, such as only "li" elements under unordered list
        -   [ ] For instance:
        -   [ ] <img src="img/c-combining.png">


-   [ ] The &lt;br&gt; element:
           -  [ ] Creates a new line in your code and forces whatever comes after to start on a new line
       -  [ ] The &lt;hr&gt; element:
          -  [ ]  Adds a horizontal line or dividing line across the webpage
       -  [ ] Used to separate sections or different topics on a webpage

-   [ ]  The &lt;footer&gt; element:
    -   [ ]  This element tends to finish off the webpage as it is located at the very bottom of the webpage and is the last set of items that will be seen
    -   [ ] For instance:
        -   [ ] A footnote on the webpage
        -   [ ] Links to different sections of the webpage
        -   [ ] A copyright symbol for copyright information
            -   [ ] & copy; -> is the symbol for copyright
        -   [ ] A link to external sources using the "href" attribute of the &lt;a&gt; element for the links in the list item to external sources
            -   [ ] &lt;a href="/privacy"&gt;Privacy&lt;/a&gt;
                -   [ ] Use the target attribute to open the link path in a new tab instead of the current page
                -   [ ] <a href="/privacy" target="_blank">Privacy</a>
                -   [ ] When the user clicks one of these external links, they would be redirected to a new page with the informat ion

---

-   [ ] Encompass:
    -   [ ] HTML
    -   [ ] CSS
-   [ ] HTML:
    -   [ ] Will be the structure and skeleton of how the app will appear on the webpageWill be the structure and skeleton of how the app will appear on the webpage
-   [ ] CSS:
    -   [ ] Encompass the style of the app and give it some flair

# What I have learned from reading 4:
(all info acquired from HTML&CSS by Duckett)

### Process and Design
#### Important Questions to Keep in Mind
* **Who is the site for?**
    * Target audience (individuals): what are their demographics?
    * Target audience (companies): size, roles of individuals at that company who'd potentially use your product/service
    * Why they are coming:
        * content must be presented in a way that makes it clear to the target audience that the webpage and info therein is relevant to them
* wireframes:
    * an organized skeleton of what your webpage might look like
* visual hierarchy
    * helps users prioritize most important and key information from what they will skim by customizing size, color, style

### Structure of Webpages
* reflects hierarchy and flow of information
* HTML uses elements to describe struture of pages
    * Examples: 
          * **html**
          * **body**
          * **h1** ... largest header
          * **h6** ... smallest subheader

### HTML5 Layout
* Headers and Footers
    * header and footer elements can also be used within article and section
* Navigation
    * only major navigational blocks should be inside the **nav** element
        * Examples: Home, About, Contact
* Articles
    * article element for content that can be a standalone section
* Sections
    * section element: groups related content together; each section typically has its own heading
* Asides
    * When aside element used **inside** article element:
        * related to the article but not essential to overall meaning
    * When aside element used **outside** article element:
        * content related to entire page

* Linking Around Block-level Elements
    * a element allows you to turn entire block into a link

* Helping Older Browsers Understand:
    * older browsers that don't know new HTML5 elements will treat as inline
        * add CSS code which tells browser which elements to treat as block level elements:
            ```
            header, section, footer, aside, nav, article, figure, figcaption { display: block; }
            ```
        * add JavaScript code to style elements on earlier versions of IE:
            ```
            <!--[if lt IE 9]>
                <script src="http://htmls5shiv.googlecode.com/svn/trunk/html5.js"></script>
            <![endif]-->
            ```
### Extra Markup

* Doctypes
    * each webpage should begin with a !DOCTYPE declaration
        * tells browser which HTML version the page is using
        * Example:
            * HTML5: !DOCTYPE html
* Comments in HTML -- adding comments that won't be visible to user's browser
    * !-- comment goes here --
* Block Elements
    * Examples: h1, p, ul, li
* Inline Elements
    * Examples: a, b, em, img
* Escape Characters
    * If I want characters that are used in HTML code to appear on my page, I use escape characters
    * **Examples:**
        * &#60 for less-than sign
        * &#62 for greater-than sign
        * &#38 for ampersand



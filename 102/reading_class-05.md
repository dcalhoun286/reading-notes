# Notes for Read 05 - from HTML & CSS by Duckett

### **Introducing CSS**

#### **CSS allows for control of how each element (and contents in that element) is displayed**

* Block level elements & inline elements
* Style rules
    * selector (which element the rule applies to)
    * Declaration (how the elements should be styled), split into two parts
        * property: aspects of elemetn you want to change (e.g., color, font, width, height, botder)
        * values: the settigns you want to use for the chosen properties

#### **Using External CSS**

* &#60link&#62
    * href specifies the path to CSS file
    * type type of document being linked to (value should be text/css)
    * rel specifies relationship between the HTML page and the file it is linked to. Should be ```stylesheet``` when linking to a CSS file.

#### **Using Internal CSS**

* &#60style&#62
    * this element usually sits inside the &#60head&#62 element of the page
* When building a site with more tan one page, you should use an external CSS style sheet.
    * Allows all pages to use the same style rules (instead of repeating them in each page)
    * Keeps content separate from how page looks
    * Can change the styles used across all pages by altering just one file (rather than each individual page)

#### **CSS Selectors**

* allows you to target rules to specific elements in an HTML document
* Most commonly used selectors
    * page 238 of HTML&CSS (Duckett)

#### **How CSS Rules Cascade**

* **Last Rule**: if two selectors are identical, the latter will take precedence
* **Specificity**: if one selector is more specific than the others, the more specific rule will take precedence
* **Important**: You can add ! after any property value to indicate that it should be considered more important than other rules that apply to the same element

#### **Inheritance**

* If you specify the font-family or color properties on the &#60body&#62 element, they will apply to most child elements

### **Color**

#### **Foreground Color**

* Can specify any color in CSS in one of three ways:
    * **RGB Values** (red, green, blue)
        * Example:
            ```
            rgb(100,100,90)
            ```
    * **Hex Codes**: six-digit codes that represent the amount of red, green, blue in a color
        * Example:
            ```
            #ee3e80
            ```
    * **Color Names**: 147 predefined color names that are recognized by browsers
        * Example:
            ```
            DarkCyan
            ```

#### **Background Color**

* Reminder: CSS treats each HTML element as if it appears in a box; the ```background-color``` property sets the color of the background for that box

#### **Understanding Color**

* reference page 251 of HTML&CSS (Duckett)

#### **Contrast**

* There need sto be enough contrast for the text to be legible
    * Low contrast
        * Difficult to read
        * Particularly negatively affects those with visual impairments
        * Affects those with poor monitors and sunlight on their screens

#### **CSS3: Opacity** ( opacity, rgba)

* ```Opacity``` property affects element to which it is applied as well as child elements
    * Example:
    ```
    opacity: 0.5;
    ```
        * means 50 percent opacity

* ```rgba``` property only affects element on which it is applied (not child elements)
    * Example:
    ```
    rgba(0,0,0,0.5)
    ```
    * Not all browsers recognize RGBA colors
        * create a fallback by both specifying a color, and listing an RGBA value last

#### **CSS3: HSL & HSLA**

* reference page 256


### [Back to home](https://dcalhoun286.github.io/reading-notes/)
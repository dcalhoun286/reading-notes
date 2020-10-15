# **Reading 06a**

#### **How HTML, CSS, and JavaScript Fit Together**

* As much as possible, keep CSS (.css) and JavaScript (.js) content in separate files from HTML (.html) content
    * Keeping JavaScript separate allows the page to still work if the user can't load or run JavaScript 

#### **Progressive Enhancement**

* JavaScript is added last; enhances the usability and/or the experience of interacting with the site
* JavaScript can be reused on several pages (faster to load; easier to maintain)

#### **Creating a Basic JavaScript**


```
var today = new Date();
var hourNow = today.getHours();
var greeting;

if (hourNow > 18) {
        greeting = 'Good evening!';
}
    else if (hourNow > 12) {
        greeting = 'Good afternoon!'
}
    else if (hourNow > 0) {
        greeting = 'Good morning!';
}
    else {
        greeting = 'Welcome!';
    }
document.write('<h3>' + greeting + '</h3>');
```

#### **Linking to a JavaScript file from an HTML page**

```
<script src="NAME_OF_JS_FILE.js"></script>
```

#### **Statements**

* Each step in a script is known as a statement (should always end with a semicolon)

#### **Comments**

* Write comments to explain what your code does to make your code easier to read and understand


```
/* This comment is to explain what the script does */
```

* /* opens the comment
* */ closes the comment

#### **How to declare variables and assign them to a value**


```
quantity = 3;
```

* quantity is the variable name
* equals sign is the assignment operator
    * (different from double equals sign, which is comparison operator)
* 3 is the variable value

#### **Using a Variable to Store a Number**

* when assigning numbers to variables, they aren't always surrounded by quote marks

* can assign to variable then reference variable to calculate final total

#### **Using a variable to store a boolean**

Boolean variables can only have a value of ```true``` or ```false```

    * can be helpful for conditionals

#### **Shorthand for Creating Variables**

###### Multiple ways to declare variables:

```
var price = 5;
var quantity = 14;
var total = price * quantity;
```

```
var price, quantity, total;
price = 5;
quantity = 14;
total = price * quantity;
```

```
var price = 5, quantity = 14;
var total = price * quantity;
```

* Shorthand code can be harder to follow; better to spread code over a few lines when starting off

#### **Rules for Naming Variables**

* name must begin with a letter, dollar sign, or an underscore. *CANNOT* begin with a number
* name can contain letters, numbers, dollar sign, or an underscore. *CANNOT* use a dash or a period in a variable name
* *CANNOT* use keywords or reserved words. 
    * list of keywords and reserved words in JavaScript can be found online 
    
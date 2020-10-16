

#### **Writing a Script**

**General Steps:**

1. Define the goal
1. Design the script
1. Code each step

* View of tasks can be represented with a flowchart
    * Example on page 18 of *JavaScript and JQuery* (Duckett)

#### From Steps to Code

* **Vocabulary:** The words that computers understand
* **Syntax:** How you put those words together to create instructions computers can follow

#### **Expressions**

* **Multiple types**
    * Expressions that just assign a value to a variable
    * Expressions that use two or more values to return a single value

#### **Operators**

**Expressions rely on things called _operators_

* Operators:
    * addition **(+)**
    * subtraction **(-)**
    * division **(/)**
    * Multiplication **(*)**
    * Increment **(++)**
        - Adds one to the current number
    * Decrement **(--)**
        - Subtracts one from the current number
    * Modulus **(%)**
        - Divides two values and returns the remainder

#### **String Operator**

* use the plus symbol **(+)** to join multiple strings

#### **Declaring a Function**

```
function greeting(who) {
    var output = "hello," + who;
    return output;
}
```

* Declaring a function is naming it and telling the computer what it is going to do when it is called 

* Parameter (inside the parentheses) is the input


#### **Calling a Function**

```
greeting(NAME);

"Hello, NAME"
```

**Invoking the Function**

* Arguments (go inside the parentheses) are what we give to the function when we call it

* 

#### **Declaring Functions That Need Information**

* You can create a function the input of which is another function (that function might have a series of functions, and so on and so forth)

#### **Declaring Functions That Need Information**

* If a function needs specific informatin to perform its task, you indicate what it needs to know in parentheses (known as the parameters) after the function name.

**Example:**

```
function getArea(width, height) {
    return width * height;
}
```

#### **Calling Functions That Need Information**

* When calling a function with parameters, the information inside the parentheses are called **arguments**, which can be values or variables.

    - Arguments as values:

    ```
    getArea(3, 5)
    ```

    - Arguments as variables:

    ```
    wallWidth = 3;
    wallHeight = 5;
    getArea(wallWidth, wallHeight);
    ```
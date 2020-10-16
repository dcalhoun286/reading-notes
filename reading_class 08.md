# Reading 08 - Comparison Operators, Logical Operators, For and While Loops

#### **Comparison Operators**

* Evaluate a situation by compariing one value in the script to what you expect it might be
* Result will be a Boolean: ```true``` or ```false```

* ```==``` - is equal to (numbers, strings, Booleans)
* ```!=``` - is __*not*__ equal to (numbers, strings, Booleans)
* ```===``` - strict equal to
    * this operator compares two vaues to check that both the data type and value are the same
    * **Example**
        * ```'3' === 3``` returns ```false```
            - they are *not* the same data type or value
        * ```'3' === '3'``` returns ```true```
            - that *are* the same data type and value
* ```!==``` - strict not equal to
    * operator compares two values to check that both the data type and value are *not* the smae
* ```>``` - greater than (compares numbers)
* ```<``` - less than (compares numbers)
* ```>=``` - greater than or equal to (compares numbers)
* ```<=``` - less than or equal to (compares numbers)

#### **Logical Operators**

* allow you to compare the results of more than one comparison operator

* ```&&``` - logical and
    * Do expression 1 and expression 2 both evaluate to be ```true```?
* ```||``` - logical or
    * Do at least one of the two expressions evaluate to be ```true```?
* ```!``` - logical not
    * this operator takes a single Boolean value and inverts it
    * **Example:**
    ```!(2<1)``` returns ```true```

* Logical expressions are evaluated **left to right**. If the first condition can provide enough info to get the answer, there is no need to evaluate the second condition.

#### **Loops**

* Loops check a condition. If it returns ```true```, a code block will run. The loop will keep repeating until the condition returns ```false```.
* Three common types of loops:
    - **for** loops are used if you need to run code a specific number of times (the most common loop)
    - **while** loops are used when the the amount of times a code should run is undetermined. The code will continue to loop for as long as the condition is ```true```
    - **do while** different from the ```while``` loop in that it will always run the statements inside the curly braces at least once, even if the condition evaluates to ```false```

**Example of ```for``` loop:**

```
for (var i = 0; i < 10; i++){
    document.write(i);
}
```
* ```var i = 0;``` is the **initialization**
* ```i < 10;``` is the **condition** (the loop will continue to run until the counter reaches the specified number)
* ```i++``` - **update**: every time the loop has run the statements in the curly braces, it adds one to the counter

#### Using While Loops

**Example**

```
var output = "";
var i = 0;
while (i < 10) {
    output = "Here is the number" + i;
    i++;
}
```

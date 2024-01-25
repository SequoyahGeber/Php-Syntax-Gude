#1. Variables
Variables are used to store data values.

####Declare a variable

` $x; // declares a variable`

` $y = 10; // declares and assigns a value`

####Variable Types
PHP has different variable types like string, integer, float, boolean, and more.

`    $stringVar = "Hello, World!";`
`    $intVar = 42;`
`    $floatVar = 3.14;`

####Variable Scope

    ```
    function example() {
        $localVar = "I'm local!";
        echo $localVar;
    }

    example();
    // echo $localVar; // This would cause an error as $localVar is not accessible outside the function.
    ```

#2. Comparison Statements
Comparison statements are used to compare values and make decisions.

    `$x = 5;`
    `$y = 10;`

    ```
    if ($x == $y) {
        // Code to execute if $x is equal to $y
    }

    if ($x === $y) {
        // Code to execute if $x is equal to $y in both value and type
    }
    ```

    // Similar comparisons for !=, !==, <, <=, >, >=

#3. Logical Operators
Logical operators are used to determine the logic between variables or values.

` $x = 5;`
` $y = 3;`

    ```
    if ($x < 10 && $y > 1) {
        // Code to execute if both conditions are true
    }

    if ($x == 5 || $y == 5) {
        // Code to execute if at least one condition is true
    }

    if (!($x == $y)) {
        // Code to execute if the condition is false
    }
    ```

#4. Arrays
Arrays are used to store collections of data.

` $animals = array('cat', 'dog', 'bird');`
` $firstAnimal = $animals[0];`
` $animals[1] = 'moose';`

#5. Associative Arrays
Associative arrays use named keys.

```
$user = array(
     "firstName" => "Sequoyah",
     "lastName" => "Geber",
     "age" => 18
 );

 $firstName = $user["firstName"];
 $user["age"] = 20;
```

#6. Functions
Functions are blocks of code that can be called and reused.

```

function printValue() {
$x = 10;
echo $x;
}

    printValue();
```

#7. Loops
Loops are used to execute a block of code repeatedly.

####"For" Loop

```
     for ($i = 0; $i < 5; $i++) {
        // Code to repeat 5 times
    }
```

####"While" Loop

    ```
    $count = 0;
    while ($count < 5) {
        // Code to repeat as long as the condition is true
        $count++;
    }
    ```

#8. Data Types
PHP supports various data types, including null, numbers, strings, booleans, arrays, and objects.

```
    $x; // Empty Variable
    $x = null; // Null Variable
    $x = 10; // Number
    $x = "Hi"; // String
    $x = true; // Boolean
    $x = array(1, 2, 3); // Array
    $x = array("name" => "Sequoyah", "age" => 18); // Associative Array (Object-like)
```

#9. Comments
Comments are used to explain what your code does.

` // This is a single-line comment in PHP`

```
/*
     This is a
     multi-line
     comment
 */
```

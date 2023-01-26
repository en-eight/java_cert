*Notes taken from the W3 Schools Java course.*

# Helpful Links

[ASCII Table Reference](https://www.w3schools.com/charsets/ref_html_ascii.asp)

# Notes

* In Java, every application begins with a **class name** and that class 
**must match the filename**.

* Every line of code that runs in Java must be inside of a class - in the
hello world program `helloWorld.java` included in this repo, the class is
`helloWorld`. 

* Much of the same rules in C/C++ apply to Java, such as:
    * putting strings in double quotation marks: `""`
    * Data types being relatively similar
        * Strongly typed
    * Semicolons on the end of each line
    * Comments behave exactly the same

### `println` method

* The `println` method can print strings, numbers, operations
* This method prints on a new line with each call
    * If you do not want this behavior, use `print` instead

### Datatypes

* `String` - the only default non-primitive data type (starts with a capital letter) stores text
* `int` - stores whole numbers, positive or negative
* `float` - stores floating point numbers; end value with "f"  
* `char` - stores single characters
* `boolean`- t/f
* `byte` - stores whole nubmers from -128 to 127 
* 'short' - can store whole numbers from -32,768 to 32,767
* long - can store whole numbers from -9223372036854775808 to 9223372036854775807.
    * Always end the value with a capital "L" like so: 
        * `long myNum = 999999999L;`
* double - can store floating point values; end value with "d"

### Keywords

* `final` - declares the value as immutable, read-only. Same as C++ `const`.

### Typecasting

* In Java, there are two types of casting:
    * Widening Casting (automatic) - convert a smaller type to a larger type size
        `byte -> short -> char -> int -> long -> float -> double`
    * Narrowing Casting (manual) - convert a larger type to a smaller type size
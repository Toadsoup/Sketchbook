#####[45 Useful JavaScript Tips, Tricks and Best Practices](http://modernweb.com/2013/12/23/45-useful-javascript-tips-tricks-and-best-practices/)

* Don't forget the keyword var when assigning variable's value for first time

* Use === rather than ==

> Also checks type

* undefined, null, 0, false, NaN, and '' (empty string) are all falsy

* Always use semicolons;

* Create and object constructor

> Todo: Put simple example here

* Use caution when using typeof, instanceof and constructor

> Todo: Tell me more

* Create a self-calling function

* Get a random item from an array

* Get a random number from an array

* Get a random number in a specific range

* Generate an array of numberswith numbers from 0 to max

* Generate a random set of alphanumeric chars

* Shuffle an array of numbers

* A String trim function

* Append an array to another array

* Transform the arguments object into an array

* Verify that a given argument is a number

* Get the max or the min in an array of numbers

* Empty an array

* Don't use delete to remove an item from array

* Truncate an array using length

* Use logical AND/OR for conditions

* Use the map() function method to loop through an array's items

* Rounding number to N decimal place

* Floating point problems

* Check the properties of an object when using a for-in loop

* Comma operator

* Cache variables that need calculation or querying

* Verify the argument before passing it to isFinite()

* Avoid negative indexes in arrays

* Serialize and deserialization (working with JSON)

* Avoid the use of eval() or the Function constructor

* Avoid using with() (The good part)

> Using with() inserts a variable at the global scope.  If another variable has the same name shit will crash together.

* Avoid using for-in loops for arrays

> The length of arrays is recalculated every time the loop runs.  (fixed in newer JS engines)

* Pass functions, not strings, to setTimeout() and setInterval()

> Faster

* Use a switch/case statement instead of a bunch of if/else

> When there are more than two cases

* Use a switch/case statement with numeric ranges

* Create an object whose prototype is a given object

* HTML escaper Function

* Avoid using try-catch-finally inside a loop

* Set timeouts to XMLHttpRequests

* Deal with WebSocket timeout

* Pimitive operations can be faster than function calls.  

> Use VanillaJS

* Use code Beautifier when coding linting & minification in prod

* JS is awesome!

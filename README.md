JAVASCRIPT ARRAY METHODS:

There are different types of array methods in JavaScript
1. Array length
2. Array toString()
3. Array pop()
4. Array push()
5. Array shift()
6. Array unshift()
7. Array join()
8. Array delete()
9. Array concat()
10. Array flat()
11. Array splice()
12. Array slice()	

1. Array Length: The length property returns the length of an array.
2. The toString() Method: The toString() method returns an array as a comma-separated string.
3. The join() Method: The join() method joins array elements into a string. but in addition, you can specify the separator.
4. The pop() Method: The pop() method removes the last element from an array. It can also return the value that was "popped out".
5. The push() Method: The push() method appends a new element to an array. It can also return the new array length.
6. The shift() Method: The shift() method removes the first element of an array (and "shifts" the other elements to the left). It also returns the element that was shifted out.
7. The unshift() Method: The unshift() method adds new elements to the beginning of an array. It also returns the length of the new array.
8. The delete Method: Deleting elements leaves undefined holes in an array. It is advisable to use pop() or shift() instead.
9. The concat() method merges (concatenates) arrays.
10. The flat() method creates a new array with sub-array elements concatenated to a specified depth.
11. The splice() Method: The splice() method adds new elements to an array. It also adds new elements to an array and returns an array with the deleted elements.
12. The slice() Method: It can be used to slice out a part of an array starting from an array element specified.

JAVASCRIPT FUNCTIONS:
A Javascript function is a block of code designed to perform a particular task. It is executed when it is been invoked or called.
Moreso, it can be used to compute a calculation by calling a function that performs a calculation and returns the result.

JAVASCRIPT FUNCTION SYNTAX:
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().
Parameter names separated by commas are included in the parenthesis: (parameter1, parameter2, ...), wwhile the code to be executed, by the function, is placed inside curly brackets: {}

SIGNIFICANCE OF FUNCTIONS:
1.It helps developers to reuse code.
2.Codes can be written and used many times.
3. The same code can be used with different arguments, to produce different results.
4. Functions Used as Variable Values
Variables declared within a JavaScript function, become LOCAL to the function, which can only be accessed within the function.

CONTROL FLOWS:
Control flow statements are a fundamental part of any programming language, including JavaScript. They allow developers to control the order in which statements are executed in your program, based on certain conditions or criteria.

In JavaScript, there are three main types of control flow statements:

A. if/else statements
B. switch statements
C. loops.

A. If/else statements:
The if…else statement executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed.

B. Switch Statements:
Switch statements are used to execute a block of code based on the value of a variable or expression.

C. Loops:
Loops are used to execute a block of code multiple times, based on a certain condition. 

There are two main types of loops in JavaScript: for loops and while loops.

While Loops:
A while loop simply repeats itself while something is true. Theoretically a while loop can loop forever. It continues until the condition is false.

While and Do…While Loops:
The while loop executes a specified statement as long as the test condition evaluates to true. The do…while loop will first execute the code, then continue while the condition remains true.

Functions:
Functions are the main “building blocks” of the program. 
We have built-in functions, like alert(message), prompt(message, default) and confirm(question). We can also create functions of our own.

1. Local variables are variables declared inside a function and is only visible inside that function.
2. Outer variables allows a function to be accessed as an outer variable
3. Global variables are Variables declared outside of any function.

Difference between a parameter and argument: A parameter is the variable listed inside the parentheses in the function declaration (it’s a declaration time term), while an argument is the value that is passed to the function when it is called (it’s a call time term).

Default values:
If a function is called, but an argument is not provided, then the corresponding value becomes undefined

Returning a value:
A function can return a value back into the calling code as the result.

Function naming:
A name should clearly describe what the function does. When we see a function call in the code, a good name instantly gives us an understanding what it does and returns.
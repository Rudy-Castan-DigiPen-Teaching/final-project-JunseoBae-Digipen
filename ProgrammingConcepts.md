##### Name: Junseo Bae
##### Assignment Name: Final Project
##### Course Number: CS099
##### Term & Year: 2020 Summer(Spring)

# Topics
## Shapes
* Shapes are functions which are used for drawing figures, such as `circle()`, `triangle()`, `square()`, `line()`, `point()`, etc.
* Shapes are used when drawing shapes on canvas.
* The reason why shapes are used is because they are fundamental functions to draw something meaningful on canvas, except for text.
* Shapes can be used by giving some arguments to the parameters of shapes. 
  The parameters are usually the position of shape's certain point or the positions of each vertex.
#### Code Snippet
(To be updated)

## Colors
* Colors are functions changing shape's charcteristics. Colors can change shape's color, transparency, borders. Colors are basesd on RGB values.(R-red, G-green, B-blue)
* Colors are used to colorize shapes or background usually. Also, they are used when adjusting shape's borders.
* Colors are utilized because they are very useful for adjusting shape's color, borders, and transparencies.
* Colors take different parameters for each function. For example, `color()` can take 1 minimum parameter and 4 maximum parameters.
  * The arguments of colors can be color's name, color's RGB value, or color and transparency value.
  * For borders of shapes, it use `stroke()` mainly. Same as `color()`, it also can take 1 parameter at minimum and 4 parameters for maximum.
  * `fill()` is used to fill shapes with colors, while `noFill()` is used to remove colors. Likewise, `noStorke()` is used to remove borders of shapes.
 #### Code Snippet
(To be updated)

## Variables
* Variables are ways of expression of assigning values. Each variable can store one value at one time and it can be functioned as an argument.
* Variables can be utilized if there are many arguments in functions or programs since programmers can use it instead of magic numbers. For instance, if a programmer wants to draw circles with the same width, he or she can use variables for the arguments of circle's width instead of inputting the same number for each `circle()` function.
* The main reasons of using variables is to avoid using magic numbers and give meaningful names to values so programmers can easily identify what each value means.
* There are two functions to declare a variable: `var` and `let`. The difference between those 2 functions are the scope of variable. A variable declared by `var` can be used throughout the entire program while the one declared by `let` is only affected within a certain block.
  * To use variables, it is mandatory to declare the names of variables and initialize them to one value. After that, programmers can use the variable to parameters where they want to use them. For example, if a programmer wants to draw a square with size of 100, declaring the name of a variable and initializing it into 100 ( like `let size = 100` or `var size = 100`) and putting the variable to `square()` like `square(width / 2. height / 2, size)` will draw a square with size of 100 at the center of canvas.
#### Code Snippet
(To be updated)

## Conditional Statements
* Conditional statements are identifiers which checking out conditions within parenthesises. It identifys if the conditions are true or false. If the conditions are true, the codes within curly braces are executed. However, if the condtions are false, the codes within the braces do nothing.
* Conditional statements are used if programmers would like to make some functions work only in certain conditions.
* The reasons why conditional statements are used are because programmers can simply control programs by using them. It is also used a lot in games. One simple case is rock paper scissors game: If Player1 played rock and player2 played scissors, player1 win and player2 lose.
* There are variety of ways to use conditional statements: `if()`, `else()`, `else if()`, and `switch()`. 
  * `if()` is the basic method of conditional statements. Codes within curly brackets are executed if the condtions within parenthesises are true.
  * `else()` is used with `if()`. The codes within braces after `else()` are run if the condtions within parenthesises are false.
  * `else if()` are used if there are more than three options for results. It is continued after the first `if()` statement. In addition, `else if()` can be used continuously if needed.
  * `switch()` are used if there are many conditions. It uses `case` for condtions. If the value of variables in `switch()` and `case` is equal, it is makred as true. In general, it is common to use `break()` after one condtional check is done. Also, if none of cases are true, the codes inside of `default()` is executed.
* Conditonal statments require operators. There are two types of operators: relational operators and logical operators.
  * Relational operators check the value of arguments. --> <(the value is smaller), <=(the value is smaller or equal), >(the value is bigger), >=(the value is bigger or equal), ==(both of the values are equal), ===(both of the values and the types of data are equal), !=(the value is not equal), !==(the value and datatype are not equal)
  * Logical operators check if there are other condtions. --> &&(AND. Both of conditions must be true to execute the codes in the braces), ||(OR. Any of conditions must be true to execute the codes in the braces, which means not all of conditions must be true if at least one condition is true.), !(NOT. The given conditions are not true.)
#### Code Snippet
(To be updated)

## Loops
* Loops are functions which run iterations in programs. It repeats particular codes inside of the curly braces after the loop statement.
* Loops are used when programmers would like to make certain codes repeated for several times in a specified condition.
* The reasons of why loops are used are to avoid writing the same function again and again. If there are functions which carry out exactly same stuffs, programmers can save considerable time for typing every single line of the same code just by using loop. For instance, if programmers hope to draw exactly same circles in a row from beginning of the canvas to the end of canvas, they can make use of loop to update the x-axis coordinate of each circle.
* There are various method of utilizing loop: `while()`, `for()`, and nested `for()` loop.
  * `while()` requires conditions inside the parenthesis. The codes inside the curly braces is executed if the conditions are true. To get meaningful results, there must be update of variables used at conditions parenthesis inside the curly braces and the declaration and initialization of variables must be done before `while()`.
  * `for()` requires have three parameters in the parenthesis: 
## Function

## Classes

## Arrays

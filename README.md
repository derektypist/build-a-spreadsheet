# Build A Spreadsheet

Aims - Learn about parsing and evaluating mathematical expressions, implementing spreadsheet functions, handling cell references, and creating interactive web interfaces.

How to dynamically update the page based on user input.

## UX

**Getting Started**

Functions include

- sum
- average
- median
- even
- someeven
- everyeven
- firsttwo
- lasttwo
- has2
- increment
- random
- range
- nodupes

**sum** takes a parameter cell range (e.g. `sum(a1,a2)`)

**average** takes a parameter, which is the cell range (e.g. `average(a1,a2)`)

**median** takes a parameter, which is the cell range (e.g. `median(a1,a2)`)

**even** takes a parameter such as cell reference or number (e.g. `even(5)` or `even(a2)`)

**someeven** takes a parameter such as cell range or number (e.g. `someeven(a1,a2)` or `someeven(5)`).  Returns true or false.

**everyeven** takes a parameter such as cell range (e.g. `everyeven(a1,a2)`).  Returns true or false.

**firsttwo** takes a parameter such as cell range (e.g. `firsttwo(a1,a2)`).  Returns the first two items in the list (e.g. `firsttwo(4,9,5)` returns `4,9`).

**lasttwo** takes a parameter such as cell range (e.g. `lasttwo(a1,a2)`).  Returns the last two items in the list (e.g. `lasttwo(4,9,5)` returns `9,5`).

**has2** takes a parameter such as cell reference or number (e.g. `has2(a1)` or `has2(a17,f17)`).  Checks if 2 is included.  Returns true or false.

**increment** takes a parameter such as cell range or number (e.g. `increment(a2)` or `increment(4)`).  Adds 1.  For example, `increment(4)` returns `5`.

**random** takes two parameters such as cell references (e.g. `random(a17,b17)`).  Returns the random number between the first two numbers.

**range** takes two parameters - `start` and `end`.  These parameters can be cell references or numbers.  Gives a list of numbers within the `start` and `end`.  For example, `range(4,6)` returns `4,5,6`.

**nodupes** takes a parameter such as cell range (e.g. `nodupes(a12,b12)`).  Removes duplicates.  For example, `nodupes(4,5,4,2)` returns `4,5,2`.

Note that cell ranges do not have to be consecutive.  For example, you can use `sum(a1,a5,a9)`

Go to any cell (e.g. A3), type `=` followed by the function name (e.g. even) and its cell reference (e.g. A3) or number.  Then press `Enter`.  For example, `=sum(a1,b1)`

Separate the cell ranges or numbers by commas (e.g. `a1,a2,a3,a4,a5`, `15,19,11`).  For example, `sum(4,5,3)` or `sum(a1,b1,c1)`.

You can also do addition, multiplication, subtraction and division.  Type `=` followed by expression (e.g. `3+8`).  Then press enter.  For example, `=3+8`.

You can also nest functions (e.g. `sum(range(4,10))`, which returns `49`).

## Technologies

Uses HTML5, CSS3 and JavaScript.  Covers concepts like the `map()` method, `find()` method, `parseInt()` method and the `includes()` method.

## Deployment

Deployed on [GitHub Pages](https://derektypist.github.io/build-a-spreadsheet/) using the main branch.

## Credits

### Acknowledgements

[FreeCodeCamp - JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/)

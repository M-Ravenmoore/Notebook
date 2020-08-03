# loop notes


## Navigation
1. [Home](README.md)

[CheetSheet](/Js-note-pages/javascript-cheetsheet.md)


- comparisons are usefull

### logical opperators
- logical and `&&`
- - used for testing more than one condition
- logical or `||`
- - used of testing at least one condition
- logical not `!`
- - inverts single boolean

### loops
- a for loop is used to rund a specific code a set number of times
- a while loop is used for an unkown number of runs
- a do while loop is close to while but runs at least once.

- initialization `var i=0` sets variable to 0 and calls it i
- condition `i > 10` loop will urn untill counter reaches the number
- update i++ iplus a modifier will update the variable to the new value

### flow control
## things to remember

- if statements
- else
- if else if
- switch

comparators for theses operatiors

strictly equal`===`
strictly not equal`!==`
greather than`>`
less than`<`
greater than or equal to`>=`
less than or equal to`<=`

ternary opperator allows for compacting of syntax allows for choose between binary decisions : 
> condition ? expression; expression
example: 
>day == "monday" ? price -= 1.5 : price += 1.5;


>input = [3, 8, 12, 14]
function sumArray(input) {
    var total = 0;
    for (n = 0; n < input.length; n++) {
        total = total + input[n] (side note you can also technically just do total += input[n])
    }
    return [total];
}
>function somefunction(takes_an_array)
var input = [some, stuff]
somefunction(input)

see problem 4 and 5 in branching practice Link to come
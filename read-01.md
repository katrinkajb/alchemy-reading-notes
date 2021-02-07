# JS Templates

    ## MDN (only read up to (but not including) "Nesting Templates") 
        - Template Literals. Can be used as placeholders within strings. Must use backticks. Allows you to add paragraph breaks.
        - Expression Interpolation allows you to add expressions to strings via template literals.

    ## Google Developer (don't need to read "Tagged Templates") 
        - Template literals to add text, math, etc to a string
        - Backticks inside the string can be done with \`

    ## CSS Tricks (don't need to read "Tagged Templates" or following section) 
        - multi-line strings are easier with template literals(backticks)
        - expressions can be added within curly braces

# Array Methods

    ## MDN forEach 
        - Runs function once for each array element
        arr.forEach(element => do something)
        - Cannot stop or break a forEach() loop (unlike for or while loops)

    ## for vs forEach (No need to read past first two paragraphs of "When to use..." section)
        - forEach simplifies a for loop because it can be called on any array.
        - callback function can be used with it that accepts element vallue, element index, and array
        - For loops are better when counting 
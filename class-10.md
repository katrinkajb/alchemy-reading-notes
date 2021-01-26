# JS 
    ## Ch. 10, “Error Handling & Debugging”
        - Execution Contexts
            - Global context - code in script, but not in a function. One per page
            - Function context - code within a function. Each function has its own context
            - Eval context - text executed like code in an internal function
        - Variable Scope
            - Global scope - a var declared outside a function can be used anywhere because it has global scope
            - Function-level scope - When a var is declared inside a function it can only be used in that function
        - Execution Context and Hoisting
            - Two phases of activity once a script enters a new execution context:
                - Prepare - new scope created, vars/funcs/arguments created, value of 'this' keyword determined.
                - Execute - values assigned to vars, funcs are referenced and ran, execute statements
        - Console helps narrow down where bug is
        - 7 types of errors in JS
            1) Error - generic
            2) SyntaxError - wrong syntax
            3) ReferenceError - trying to ref a var that doesn't exist/out of scope
            4) TypeError - Unexpected data type
            5) RangeError - Numbers not in acceptable range
            6) URIError - encodeURI/decodeURI functions used incorrectly
            7) EvalError - Eval() used incorrectly

        - Debugging - deduction of where the error is and what the problem is.
            - Try, Catch, Finally statements - error handling
                try {Try to execute this code
                } catch (exception) {
                If there is an exception, run this code
                } finally {
                This always gets executed
                }
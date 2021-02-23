# Styling HTML Forms
    - input[type='___'] can be used to grab all of that type of obj
    - He uses an image sprite for the checks. Not sure I understood how he decided which part to show with 0 and -32px, but it was cool to see it come together
        - background-position
        - 0 is x axis, other number is y axis
    - input:checked for styling on check
    - Need to hide default checkbox/selections in order to show your own
        - opacity, width, and margin all 0 for the input (not the labels)
    - display: block to put inputs on different lines
    - To hide appearance of dropdown have to use extra steps to make it work in all browsers (moz-appearance: none)
    - box-shadow to add shadow to button
    - Validation
        - input[type='__']:valid to style only when valid
        
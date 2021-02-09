What's important in the articles below is the thinking behind breaking down the UI into pieces, or components.  "Components" can also mean a specific technical approach to doing so, like a React component or a Vanilla JS component.

# Applying Atomic Design
    Part 1 
        - To design, start big and work your way down.
        - Organisms - large sections that can be easily extracted from the page
        - Molecules - sections that can be easily extracted from Organisms. Usually repeated in mult places
        - Atoms - basic HTML elements(tags) that can't be broken down more without losing functionality
    Part 2
        -  After defining above items, define folder structure representing each atomic stage (atoms folder, molecules folder, organism folder)
        - To write the code, start small and build up. Make smaller components reusable. 'type' property can help (heading, subheading, or paragraph)
    More examples 
        - React is component-driven for UI development
        - Potential problems due to lack of governance:
            -  Re-creating stylesheets and patterns
            - Interfering styles when they come from different places cause devs to overuse CSS
            - styles coming from different places can break things on other pages without realizing it
        - Reusing component styles can help, but it can be hard to maintain

# Step 1 only of Thinking in React 
    - Start with a mockup and break the UI into components

# UI Components by Design  (don't worry about code examples, the process and ideas are what is important)
    - Common language between UI and dev
    - Working together to determine foundation components with tight feedback loops
    - build, integrate, then learn and iterate

# Callbacks
    ## What are JavaScript Callbacks? 
        - A function executed after another function has completed. A function used as an argument in another function
        - Can be used to make sure functions happen in order
    ## JavaScript Callback Functions 
        - This article wouldn't load. I kept getting a 404.
    ## First class functions 
        - Functions that can be treated like a variable (like Callbacks)
    ## MDN Callback function 
        - Used to continue code execution after an async operation has completed.

# Review: Classes
    ## JavaScript classes 
        - 
    ## Intro to Object-oriented programming in JavaScript 
        - Can use extends to put two classes on something
        - new to create a new object from a class
        - Can use function to declare a class
        - Prototype inheritance - new objects created from original one created with new operator inherit all properties from it.

# Review: this
    ## Intro (Read up to, but not including, Internals: Reference type section)
        - this.___ to access specific info in object
        - Can be re-used in different objects to be more reliable
        - needs an object or it will show as undefined
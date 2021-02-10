# Read
    ## It will be very helpful if you can work thru most of CSS Grid Garden - went through earlier during the course

    ## Shay Howe’s intro to RWD 
        - a site that will adjust to mobile - flexible layout
        - Using flexible grids means using relative length units (% or em units)
            - vw (viewports width)
            - vh (viewports height)
            - vmin (min of viewport's height and width)
            - vmax (max of viewport's height and width)
        - Take target width of element and divide by width of parent element for the relative width.
        - Can also use min-width, max-width, min-height, and max-height properties
        - Media Query - Ability to specify different styles for different browser/devices
        - Orientation - landscape or portrait
        - Aspect Ratio width/height (eg x/y)
        - Mobile-first means loading is quicker on mobile since it doesn't have to load the full site first, then override those styles with mobile styles
        - Viewport meta tag helps scale things on a smaller screen (like buttons and button text)
            - minimum-scale, maximum-scale, initial-scale(almost always set to 1), user-scalable properties
    ## All About Floats 
        - Left and Right floats - used to arrange images and text on a page
        - Ignoring float allows text to go over image
        - Sidebars and seting up content within a page
        - Used instead of absolute position to allow more responsiveness
        - Clear property will move content below the float elements (like a footer)
        - Collapsing of parent elements is something to keep in mind (if all child elements are floated). Can be fixed by clearing the float after floated elements, but before close of container
        - Clearing Floats
            - Empty div method - add prop to empty div
            - Overflow method - set overflow method on parent element to auto or hidden
            - Easy clearing method - CSS pseudo selecor :after
        - Float problems
            - Pushdown - element inside floated item bigger than parent item pushes down other elements. overflow: hidden can fix
            - Double margin bug - if a margin is applied in the same direction as a float it will double the margin. display: inline will fix.
            - 3px jog - text next to floated item is kicked away by 3px. fix by setting height or width on text
            - bottom margin bug - floated parent has floated children, the bottom margin on children is ignored by parent. fix by using padding instead on parent

# Skim
    ## Don't Overthink It Grids 
        - Gutters (box-sizing: border-box, apply fixed padding except to last column)
    ## CSS Floats Explained By Riding An Escalator 
        - Alternate Flows are created by adding floats (left, right, and normal)
        - FLoating left and right allows objects without a float to fill in spaces around floated elements.

# Reference
    ## SMACSS Official Documentation
        - Awesome style guide that will be super helpful when working on projects and/or going back over older projects.
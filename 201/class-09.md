# HTML
    - Ch7: “Forms” (p.144-175)
        - Collecting info from visitors in an input area, user clicks button to submit, server processes info then sends back something new.
        - Different kinds of form controls
            - form element, can have action, id, and method within tag
            - input type='text',  input type='password', text area, radio button, checkbox, dropdown, multi-select, file input, submit button, image button (all options)
        - New html5 form controls
            - validate that inputs are there and match a certain format. input type='____'   date, email, url, search all options. can also add placeholder.
    - Ch14: “Lists, Tables & Forms” (pp.330-357)
        - Specifying bullet point styles - ul, ol. Then li for each
        - list-style-type and list-style
        - Changing appearance of form elements - certically align to make them look nicer

# JS book:
    - Ch6: “Events” (pp.243-292)
        - Interactions create events, events trigger code, code responds to users
            - UI events, keyboard events, mouse events, focus events, form events, mutation events/observers.
            - Select element, specify event, call code.
        - Event handlers
            - html event handlers (not recommended)
            - Traditional DOM event handlers - single function to each event. element.event = functionName
            - DOM level 2 event handlers - one event can trigger multiple actions   element.addEventListener('event', functionName [, Boolean]);
                - Can use with parameters
        - Event Flow
            - matters if event handlers are on an element and a descendent of that element
        - Event Object gives info about the event and element
             - Event listeners can use event object's target to know which to interact with
        - Event Delegation
            - Event listeners on each element slows down page, use event flow to add them only to containing elements and use the target property to direct them
                - benefits: works with new elements, solves limitations, simplifies code
                - "this" keyword (eg this.value.length)
            - Changing default behavior
                - preventDefault() - stops default behavior
                - stopPropagation() - stops bubbling up to containing elements
                - Can use both - 'return false' - but usually better to use preventDefault()
        - Types of events
            - W3C DOM events - regular DOM events
            - html5 events - submit, input, change, readystatechange, DOMcontentLoaded, haschange
            - BOM events (for touchscreen devices) - touchstart, touchend, touchmove, orientationchange
            - UI events (load, unload, error, resize, scroll)
            - focus and blur, mouse events (click, dblclick, mousedown, mouseup, mouseover, mouseout, mousemove)
                - Where events occur (screen, page, client)
                    - Event object can tell you where the cursor was when event was triggered
            - keyboard events (input, keydown, keypress, keyup)
            - form events (submit, change, input)
            - mutation events and observers
                - DOMNoteInserted - fires when a node is inserted into the DOM tree
                - DOMNodeRemoved - fires when node is removed from DOM tree
                - DOMSubtreeModified - fires when structure changes
                - DOMNoteInsertedIntoDocument - fires when  node is inserted into DOM as a descendant
                - DOMNodeRemovedFromDocument - when a node is removed as a descendant
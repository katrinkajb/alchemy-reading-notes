# “The Past, Present, and Future of Local Storage for Web Applications”
    ## Diving In
        - native client vs web applications
        - Goal: lots of storage, on the client, persists beyond page refresh, and isn't transmitted to server
    ## HTML5 Storage
        - Aimed to standardize the space of storing key/value pairs locally with the client web browser
            - Similar to cookies in that leaving the page keeps the data, but different in that the data is never sent to a remote server.
            - Implemented natively within browsers unlike 3rd party plugins
        - Using HTML5 Storage
            - To check for storage can write a function or use external things like Modernizr to check for you
            - Data is stored in key/value pairs. Keys are used to store and retrieve values.
            - Data msut be stored in string format (can be converted from other formats)
            - getItem('itemName') and setItem(key, 'value') can be used to set and retrieve data. removeItem() can remove
        - Tracking Changes
            - Track when setItem(), removeItem() or clear() are called and make a change (storage event only tracks when changes are made)
        - Limitations
            - 5 MB - limit to storage space, but strings take up less room
            - 'quota exceeded' - can't add more
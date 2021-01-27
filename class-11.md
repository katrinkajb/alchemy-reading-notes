# HTML

    ## Ch16: “Images” (pp.406-427)
        - CSS to control look of images
        - Background images
        - Image rollovers and sprites
            - Sprite = when a single image is used for multiple parts of an interface (useful because browser only has to request one image)
            - Rollovers - hover effects
        - Gradients - specify two colors to fade between
    ## Ch19: “Practical Information” (476-492)
        - SEO
            - on-page - keywords, image text
                - 7 places: title, URL, headings, text, link text, image alt text, page desc
            - off-page - external links to site (relevant/related)
        - Analytics
            - How many people visit site 
            - How they behave
            - Where they are coming from
        - Put your site on the web 
            - Domain names
            - Hosting

# MDN article
    ## html5 audio and video
        - <video> and <audio> tags
        - Controls attribute allows play, volume, etc via browser, but these can be hidden and coded yourself instead.
        - HTMLMediaElement API
            - Code in controls for play, pause, etc - HTMLMediaElement.play()
            - wrap everything in a div
            - include <source> elements to load video on different browsers
            - <button> can be used to add play/pause, stop, etc
                - class and data-icons are added to button
                - aria-label attributes for sreenreaders to read labels
            - Timer div to show elapsed time
            - event listener for play/pause clicks (if statement for swapping states), stopping, and other buttons
            - Fast Forward and rewind
                - EventListeners and functions for going forward and backward in time
            - Tracking time elapsed
                - eventListener on timeupdate (instead of click) then a function to setTime
            - Set up play/pause button to cancel ff or rew

# Flash Chapter pages 201-206
    ## Recently deprecated, but was a huge part of websites since the 90's
        - Space Jam site or homestarrunner.com (recently moved from flash) are examples
        - Now HTML5 video and audio tags are used instead
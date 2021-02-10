# Review:
    ## MDN URLSearchParams built-in class 
        - Defines methods to work with query string of URL. can be used like:
            - for (const [key, value] of mySearchParams){}
        .append - appends specified key/value as a new search param
        .delete - deletes param and value from list
        .entires - returns an iterator to allow iterative through all key/value pairs in obj
        .forEach - Allows iteration through all values in obj through callback func
        .get - Returns first value associated with given search param
        .getAll - Returns all values associated with given search param
        .has - returns boolean indicating if param exists
        .keys - returns iterator allowing iteration through all keys of key/value pairs in obj
        .set - sets value associate with given search param to the given value
        .sort - sorts all key/value pairs by their keys
        .toString - returns a string containing a query string suitable for use in an URL
        .values - returns iterator allowing iteration through all values of key/value pairs in obj

    ## toString() returns query string 
        - returns a string containing a query string suitable for use in an URL
    
# Using the url "hash":
    ## Built-in Location Object 
        - represents location(URL) of the object it's linked to. Changes done on Location interface are reflected on associated obj too.
        - Properties:
            - Location.ancestorOrigins - static DOMStringList containing, in reverse order, the origins of all ancestor browsing contexts of the document associated with the given Location object
            - Location.href - stringifier that returns a USVString containing the entire URL. If changed, the associated document navigates to the new page. It can be set from a different origin than the associated document
            - Location.protocol - contains the protocol scheme of the URL, including the final ':'
            - Location.host - contains the host (that is the hostname, a ':', and the port of the URL)
            - Location.hostname - contains the domain of the URL
            - Location.port - contains the port number of the URL
            - Location.pathname - contains an initial '/' followed by the path of the URL, not including the query string or fragment
            - Location.search - contains a '?' followed by the parameters or "querystring" of the URL. Modern browsers provide URLSearchParams and URL.searchParams to make it easy to parse out the parameters from the querystring
            - Location.hash - contains a '#' followed by the fragment identifier of the URL
            Location.origin Read only - Returns a USVString containing the canonical form of the origin of the specific location
        -Methods
            .assign - loads resource at URL provided in param
            .reload - Reloads current URL
            .replace - Replaces current resource with one provided at provided URL. Current page isn't saved in session history (unlike .assign)
            .toString - returns a USVSString with full URL


    ## Hash change event
        - An event fired when fragment id of URL has changed
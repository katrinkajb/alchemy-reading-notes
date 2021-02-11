# Synchronous and Asynchronous JavaScript
    ## Callbacks
        - 
    
    ## Promises 
        - 

    ## MDN on Asynchronous 
        - Happens with a delay (out of order)

    ## Intro 
        - Synchronous means the code runs and is returned as soon as it can be
        - Asynchronous is used with APIs especially since it has to wait for outside servers to return results. This means you have to plan for the delay accordingly (promises and fetch)
        - Async callbacks can tell you when the request has finished
        - Promises - newer than callbacks and made for handling async operations. Can also be chained together, they run in the strict order, have better error handling, and avoids inversion of control
        - Event queues are used so other functions aren't blocked while first functions are running/waiting

    ## Promises 
        - An object that represents an intermediate state of an operation (a promise that a result will come in the future)

# More on Promises
    ## MDN Using Promises 
        - 

    ## Video on Promises and fetch 
        - Promises - two functions where the second depends on the first, you want to run them in the correct order if the first takes longer to run for whatever reason
        - Fetch - Put a url into the parenths of fetch to pull info from API

    ## Promises in 20 Minutes 
        - 

    ## Google Developer on Promises 
        - 

# Using fetch
    ## MDN using fetch 
        - doesn't reject http error status
        - can receive (but doesn't send) cross-site cookies
        - 

    ## Fetching data
        - fetch() makes a network request to an URL and returns a promise that will resolve with a response obj when the remote server responds. Response can be read y calling a response method like text() or json().
# JS
    ## Ch3: “Object Literals” (pp.100-105)
        - literal is just the way the object is written out:
            const object {
                key:value (property) }
        - Use dot notation to use pieces of the object:
            object.property object.method();
        - Square bracket syntax object['property'];
    ## Ch5: “Document Object Model” (pp.183-242)
        - Separate from HMTL and JS, the DOM is a set of rules to model the html page (DOM tree) and access/change it (API)
        - Document Node - top of the DOM tree. Allows you to access every other node in the tree (html, body, divs, h2, ul, scripts, etc)
        - Element Nodes - Each html part (tags) of the page (html, body, divs, h2, ul, scripts, etc)
        - Attribute nodes - id and class, etc in the opening tags of html elements
        - Text nodes - text within an html element
        - Working with the DOM Tree
            1) Access the elements
                a) Select an individual node
                    - getElementByID() - quickest way to a single node
                    - querySelector() - uses CSS selector and returns first matching element
                b) Select multiple nodes
                    - getElementsByClassName() - retu
                    - getElementsByTagName()
                    - querySelectorAll() - Uses CSS selector to return all
                c) traverse between element nodes
                    - parentNode - selects parent of current element node
                    - previousSibling/ nextSibling - selects previous or next sibling in DOM tree
                    - firstChild/ lastChild
            2) Work with those elements
                a) Access/Update text nodes. 
                    - nodeValue let's you access or update contents of a text node
                b) Work with html content
                    - innerHTML allows access to child elements and text content
                    - textContent, or DOM manipulation: createElement(),  createTextNode(), appendChild()/ removeChild()
                c) access or update attribute values
                    - className/ id
                    - hasAttribute(), getAttribute(), setAttribute(), removeAttribute()
        - Caching DOM queries - create a variable when you'll use a DOM query more than once (const = getElementByID();)
        - nodeList - collection of nodes. Can determine which node you want to pull by using the index (getElementsByTagName(booger)[2]);


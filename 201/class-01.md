# HTML
    ##Ch1: Structure
        - Webpages need to know how to display a site so html tags and attributes are used to set up the structure of a text document to show on the web. 
            - Tags: Set within <>, most need closing tags to end the section that end with a forward-slash </>. 
            - Attributes: need a name and a value
    ## Ch8: Extra Markup
        - Comments: "< !-- -->". A way to write a note to yourself or other devs that will not be published.
        - Global attributes
            - ids and classes can be used to style individual(ids) or multiple(classes) elements on the page
        - Elements
            - block elements seem to start on a new row
            - inline elements show on the same line as the rest of the text/elements
            - div tags can be used to put multiple pieces of text/elements together into a block
            - span allows you to group text and elements in the same line
        - iframes: another site being hosted inside a box on your page (eg, google maps showing a location on a restaurant's site). Needs the src, height, and width.
        - meta element: shows back-end info about a page used by search engines (description, keywords for search engines, index info, etc) and other useful info
        - escape characters must be used when including special characters that are typically used by html (greater-than, less-than, ampersand, single and double-quotes, etc)
    ## Ch17: HTML5 Layout
        - Differences from old htmls: using specialized tags for different areas of the page (header, footer, content, article, nav, aside, section, figure, etc) as alternatives to <div> to make things cleaner. BUT div is still important to group similar elements together
        - working with older browsers: in css doc can include a line to display these new elements as blocks so they don't show inline
    ## Ch18: Process & Design
        - Target audience: Individuals/companies, location, size of company, web access, etc. all go in to determining your target audience and how you build your site. User personas can help here - what their motivations are, why they visit your site, how familiar their are with your offerings, how often they visit the site, etc can all inform what type of info they need
        - Organization so visitors can find what they are looking for: Site maps are useful to determine what is related. 
        - Design: Wireframes show an outline of the design to get shape/size info before you start building. Where content should go (and which information/chunks are most important to have immediately available and what can be below the scroll or on other pages). Styling parts differently helps important parts stand out. size, color, and style of text can ensure important pieces are read. Images help break up the information and draw the eye. Grouping things together can be done in different ways to get the intended point across effectively
        - Navigation: You need a clear, and concise nav in order to be useful. Too many options or words make it hard to use. They should also be consistent across pages and show the user where they are quickly.
# JS
    Ch1: ABC of Programming
        - What is a script? A set of instructions (like a recipe or manual) for the computer. Define your goal, list tasks needed to achieve it, then code each task. Flowcharts can be helpful to determine the steps. Sometimes only a subset of the instructions are followed (if it meets criteria early for example)
        - Computers: special vocab and syntax for instructions. Comps create models using data so detailed data is needed to tell it what to do or expect.
            - Objects: A physical thing like a house or car. They can have properties, events, and methods tied to them.
            - Properties: Characteristics of the object (eg, hair color, name, etc.). Must be in a name: value pair.
            - Events: Things that happen to object when a user interacts with it
            - Methods: Way to perform a task
        - How do I write scripts? Separate js file that is connected to html with <script> tag.
            - format: object.method(parameters);
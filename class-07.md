# Domain Modeling
    - process of creating a conceptual model in code for a problem
    - Defines vocab to be used
    - 'new' keyword instantiates(creates) the object(s) which can then be stored in variables
    - constructor function defines and initializes properties inside the object
    - Prototypes can be used in place of using the constructor function every time
    - Use small methods to model behaviors
    - Using 'this' variable within methods allows you to access objects properties/methods from within

# HTML
    Ch6: “Tables” (pp.126-145)
        - To create - <table> then <tr>- table row, and <td> - table data (each cell). <th> for the table heading.
            - Can use <td colspan='5'> to have data span across multiple columns in the row(5 in this example). rowspan for rows.
            - If the table is long, use thead, tbody, and tfoot to help organize and be better for screen readers
# JS
    Ch3: “Functions, Methods, and Objects” (pp.106-144)
        - Constructor Notation to create an object - const thing = new Object(). Then add properties to it
            - thing.name = 'blah';
        - Object properties can be updated with dot notation or square brackets. If obj doesn't have that property, it will be added
        - Delete keyword can be used to delete the property. Otherwise use thing.property = '' to clear it.
        - Obj constructors can use a function as a template to create new objects.
            - function Hotel(name, rooms) {
                this.name = name;
                this.rooms = rooms
                this.checkAvailability = function() {return this.rooms - this.booked;}
            }
            - Then can use new Hotel(stuff) to create a new hotel
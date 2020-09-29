
## Outside Reading

[Understanding the problem domain is the hardest part of programming](http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming)

#### From the Duckett JS book

## Chapter 3: “Object Literals” (pp.100-105)

##### What is an Object: 

a group of variables and functions to create a model of something you would recognize from the real world.  In an object variales and functions take on new names.

- variables become knon as properties
- Functions become know as methods

In JS

- Variables have a name and you can assign them a value of a string, number, or boolean
- arrays have a name and a group on values (each item in an array is a name/value pair becuase it has an index number and a value.)
- Named functions have a name and value that is a set of statements to run if the function is called.
- Objects consist of a set of name/values paris (but the names are referred to as a keys)

Literal notation is the easiest and most popular way to create objects. (there are several ways to create objects.)

## Chapter 5: “Document Object Model” (pp.183-242)

### The browser represents the page using a DOM tree

The DOM Tree

- each node is an object with methods and properties. 
- Scripts access and update the DOM  tree(not the source HTML file)
- Any changes made to the DOM Tree are reflected in the browser

### DOM Trees have four types of nodes: document nodes; element nodes, attribute nodes, and text nodes

##### Document Nodes pg 186

1. The HTML code  creates a DOM tree
1. Every element, attribute and piece of text in the HTML is represented by its own DOM nod

##### Attribute Nodes pg 187

1. Attribute Nodes - opening tags of HTML elements can carry attributes therfore are attributes of nodes in teh DOM tree
1. Attribute nodes are not children of the element that carries them.
1. at the top of the tree a Document node is added. it represents the entire page

#### Element nodes

1. HTML elements describe the structure of an HTML page.
1. to access the DOM tree, you start by looking for elements. 

##### Text Nodes pg 187

1. once you ave access and element node you can then reach the text within that element, this is stored in its own text node
1. cannot have childrenIf an element contains text and another child leement, the child is not a child of the text node but = a child of the containing element.

### You can select  element nodes by their Id or Class attributes, by tag name, or using css selector syntax

### Whenever a DOM Query can return more than one node. it will always return a NodeList.

Accessing and updating the DOM tree involes two steps

1. locate the node tha represents the element you want to work with
2. use its text content, child elements, and attributes

Methods that find elements in the DOM tree are called DOM queries.  When you need to work with an element more than once, you use a variable to store the result of this query.

### From an Element node, you can access and update its content usiong properties such as textContent and innerHTML or using DOM manipulation techniques

> DOM queries may return one element or a NODE list
> Groups of element nodes will alwyas contain a collection
> fastest route to the element is by id or calling 


### An element node can contain multiple text nodes and child elements that are siblings of each other

### in older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery)

### browsers offer tools for viewing the DOM tree

[go back](../README.md)
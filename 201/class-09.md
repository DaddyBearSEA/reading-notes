# Readings : Forms and JS Events

Here are the chapters to read/skim before class:

##### From the Duckett HTML book:

## Chapter 7: “Forms” (p.144-175)

## Whenever you want to collect information from visitors, you will need a form. Which lives inside a form element

- how to create a form on your website
- the differnt tool for collecting data
- new HTML5 form controls

 Why use forms?

- gather information about the user
- store or retrieve data
  
### information from a form is sent in name/value paris

Form Controls 

 - Adding Text = String
 - making a choice - boolean
 - submitting forms - writing to a databae 

## each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.

for name = "string"
for password = incripted string

### HTML5 introduces new form elements whic make it easier forvisitors to fill in forms.

`<form>`
  - `<action>`
  - `<method>`

#### Password maybe hidden on the page, but that doesn't mean that the data control is sent securely to the server

**New HTML5 Element**

- form validation
- date input
- email and URL
- search input

Forms are vary similar to ACCESS DATABASE forms

## Chapter 14: “Lists, Tables & Forms” (pp.330-357)

there are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.

- specify the type of bullet point or numbers on lists
- Add borders and backgrounds to table cells
- control the apperance of form controls

### In addition to the CSS properties covered in other chapters which work with the contents of all elements, there are serveral others that are specifically used to control the appearance of lists, talbles and forms.

- bullet point styling
- images for bullets
- positioning
- list=style
- table properties
- and much much more - I think I have found my new Candy Store

### list markers can be given different appearances using the list-style-type and list-style image properties

### table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent

 > think CSS inside the table!

### forms are easier to use if the form controls are vertically aligned using CSS

### forms benefit from styles that make them feel more interactive

#### Web Developer Toolbar

1. outlines
1. structure
1. css tyels

#### From the Duckett JS book:

## Chapter 6: “Events” (pp.243-292)

wehn you browse the web, your browser registers diffehnt types of evetns. It's the browser's way of saying, "hey, this just happened." Your script can then respond to these events.

> scripts often respond to events by updating the content of the web page via the DOM which makes the page feel more inteactive.  AMAZON!!!!!!

- Interactions Create Events
- Events Triggter Code 
- Code Responds to Users


### Events are the browser's way of indicating when something has happened (such as wehn a page has finished loading or a button has been clickes)

list of UI events (pg 246 = 247)

### Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.

1. Select the Element
1. Specify the Event
1. Call the code




### When an event occurs on an element, it can trigger a JavaScript Function.  When this cuntion then changes the web page in some way, it feels interactive becuase it has responded to the user.
**Event Handling**

When the user interacts with the HTML on a web page, there are three steps involved in getting it to triger some JS code. 

- Element NODE
- Event (binding and evnet to a DOM NODE)
- State the code you want to run when the event occurs

3 ways to Bind an event to an element

1. HTML Event handlers - pg 251
1. Traditional DOM event handlers - pg 252
1. DOM level 2 event listners - p254

#### DO NOT USE #1 HTML EVENTS - its now bad practice

### you can use event delegation to monitor for events that happen on all of the children of an element


#### Event Flow

1. Event Bubbling - The event starts at the most specific node and flows outwards to the lease specific one. DEFAULT pg 260
1. Event Capturing - the event starts at teh lease specific node and flows inwards to teh most specific one (not supported in < IE 8)

Why Flow Matters
> the flow of events only really matters when your code has event handlers on an element and one of its ancestor or decendan elements.

Google Analytics listens??

### the most commonly used events are W3DOM events, although there are others in teh HTML5 specification as browser specific events.

3 different types of Events

1. The W3C DOM specification
1. the HTML5 specification
1. In Browser Object Models

[go back](../README.md)
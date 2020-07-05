# Reading Assignment Day 1



### From the Duckett HTML book:

## Introduction (pp.2-11)

## HTML Chapter 1: “Structure” (pp.12-39)

HTML is the structure of a web page - BONES

Just like a word preocessor you have tags or "elements" to determine structure.
Elements can have attributes to definge how the element is to be understood.
- tags have a start and end tag
- Attributes have a name and Value within the open tag

Head of an HTML page contains meta data and the Title most commonly

`html>head>title>body>` 


## HTML Chapter 8: “Extra Markup” (p.176-199)

**doctypes** - Tells the browser what version of HTML you are using


**comments** - allows you to put comments within the HTML or comment out code for debugging `<!--   -->` Shortcut in VCode is to hightlight text then `ctrl + /`

**`<id>`** Used to uniquely identify that element/tag from other elelements on the page
- Should begine with a Letter of "_"
- should be unique
- Id attribure is known as a **global attribute**
- Only used once

**`<class>`** identifys several elements as being different from the other elements on the page.
- The class attribute can on any element can share the same value
- should be unique
- can be used through out your pages.
- an element can belong to multiple classes by using a space between names 

`(ie. <p class="important">   or <p class="important highlightme"> )`


**`<div>`** allows you to group a set of elements together in one block-level box

**`<iframes>`** a smaller window inside your html to another page.

**`<meta>`** contains information about your page. Some SEO requirements are here within the meta tags. SEO is always changing.
- Lives inside the head tag
- meta description
- meta author
- meta keywords

**Escape Characters** special characters that are used and reserved by HTML code.
- Like `< >` or ` " " `
- Symbols like Copywrite, trademark Yen or Pound signs, and Exclamation point
- see page 194



## HTML Chapter 17: “HTML5 Layout” (pp.428-451)

**HTML5 elements** in the past div was used often to define parts of the page. HTML5 gives you new elements
- header
- footer
- nav
- article
- aside
- section
- hgroup
- figure figcaption
- div

**new elements provide clearer code**


**older browsers**

> Useing Google Javascrip HTML5 shiv or shim.  Less thatn IE9 browsers.

**NOTE:** *anyone using IE* or lower must have JavaScript enabled in their borwser*

**Extra JavaScript**

> See Above under Older Browser


## HTML Chapter 18: “Process & Design” (pp.452-475)

Some basics broken into 4 thoughts
1. Audience - who is your demograhic for your website
1. Organization of your content
1. Presentation of the content
1. Attractive and Professional design to meet the target audience

### Demographic of Audience
> Know your target clientele and why they want to come to your website. Give them the informaton that they seek on your site.

### Motivational Goals
> Why are they visiting your web site and what information are they expecting to find.

**NOTE:** *when taking over an existing website, look for analysis of the current traffic and what demographic is already present.*

### Site Maps
> How will you organize your content for the website. Use a tool called Card Sorting and lay out the information. Index Card or and Excel Spreadsheet is nice to lay things out.

### Wireframes
> Then off to WIREFRAMES - Photoshop has templates for this.

### Visual Hierarchy
> There is a lot of Psychology around design of web sites and what works and doesn’t work. Here is a taste of some psychology


#### Designing Navigation
 - Concise
 - Clear
 - Selective
 - Context
 - Interactive
 - Consistent

### From the Duckett JS book:


## Introduction

Javascrip makes static webpages more dynamic

**Examples of useing Javascript**
- Slideshows
- forms
- reload part of a page
- filtering data



## JS Chapter 1: “The ABC of Programming” (pp.11-52)

#### A What is a script and how do I create one
- searies of instructions

- might only use a subset of the instructions

- Let the computer solve the task programmatically

- break down your goals, create series of tasks and then work out each step needed `(flowchart)`


#### B How do computer fit in with the world around them?

- computers create models of the world

- Models use objects to represent physical things
    - Objects have property
        - Methods
        - events

- Programmers write code when this event occurs = run this code

- Web browswers use HTML Markup to create a model of the web page. Each elements creates its own node `(which is a kind of object)`

- To make web pages interatice, you wirte code that uses the browser's model of the web page.




#### C How do I write a script for a web page?

- Keep JS code in it's onw JS files. HTML its own files and CCS in it's own file.
- HTML `<script>` element is added to HTML to be exucuted within the HTML code
- when looking at the source code the JS will not change the HTML.  The JS works with the MODEL of the Web Page the Browser created


[go back](README.md)




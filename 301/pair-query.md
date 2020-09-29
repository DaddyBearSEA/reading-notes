## Reading

#### JavaScript and jQuery book by Jon Duckett 
pages 293-301, 306-331 and 354-357

#### JQuery Offers
1. select elements
1. perform tasks
1. handle events

Jquery is a JS file that you include in your webpages. It lets you find elements using CSS-style selectors and then do something with the elements using jQuery methods.

1. Find Elements  `$('li.hot')`
1. do something `$('li.hot').addClass('complete');`

**NOTE:** jQurey's motto is "Write less, do more."

##### Why use jQuery?
1. simple selectors
1. common tasks in less code
1. cross browser compatibility

A matched set / jQuery Selection
1. Single Element pg 306
1. Multiple elements

jQuery methods that get and set data
1. get infomration pg 307
1. set information


jQuery objects store references to elements - when you create a selection with jQuery, it stores a reference to the corresponding nodes in the DOM tree. It does not create copies of them.

Caching jQuery selections in variables - a jQuery object stores references to eleements. Caching a jQuery object stores a reference to it in a variable.

## Ways to include jQuery in your page

CDN - Content Delivery Network - a series of server spread out around the world.  
 
Loading jQuery from a CDN -pg 355
`<script src ="//ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>`

`<script>`

`window.jQuery || document.write('<scrit src = 'js/jquery-1.10.2.js"><\/script>')`

`</script>`


Load jQuery at the bottom of the code before the `</body>`



#### [6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

1. How does pair programming work?
1. Why pair programming

[Research of efficiancy](https://collaboration.csc.ncsu.edu/laurie/Papers/XPSardinia.PDF)

6 Reasons Why

 1. greater efficiancy
 1. engaged collaboration
 1. learning from fellow students
 1. Social Skills - Soft Skills
 1. job interview readiness
 1. work environment readiness


#### Bookmark/Skim

##### JavaScript and jQuery book by Jon Duckett pages 332-335

- effects
- basic effects
- animatin css properties
- using animation

##### JavaScript and jQuery book by Jon Duckett pages 302-305
- finding elements
- Doing things with your selection

Lots of .Method here to explore
# Responsive Web Design


## Reading

#### Shay Howe’s intro to RWD

Design for Mobile devices.  
<img src="images/mobilestats.jpg" height = "100px" align = "right">


 - Desktop computer and cell phone users alike all benefit from responsive websites.
 - Responsive vs. Adaptive vs. Mobile
    - Responsive generally means to react quickly and positively to any change,
    - adaptive means to be easily modified for a new purpose or situation, such as change. 
    - Mobile generally means to build a separate website commonly on a new domain solely for mobile users. 
- Flexible Layouts
  3 components
    1. Flexible Layout
    1. Media Queries
    1. Flexible Media

#### Flexible Layouts
> flexible grids

> Dynamically resizing

> Used relative units- em, % 

Relative Viewport Lengths

- vw - Viewport Width
- vmin - Minimum of the viewport's height and width
- vh - Viewport Height
- vmax - Maximum of the viewport’s height and width

**Do not use fixed units like pixels and inches.** The viewport height and width continually change from device to device. 

**Flexible Grid**  

This [guy](https://www.youtube.com/watch?v=k32voqQhODc) really helped me with my CSS on YouTube.  Flexbox in half an hour!

> **NOTE**  *The flexible layout approach alone isn’t enough. At times the width of a browser viewport may be so small that even scaling the the layout proportionally will create columns that are too small to effectively display content. Specifically, when the layout gets too small, or too large, text may become illegible and the layout may begin to break. In this event, media queries can be used to help build a better experience.* [Reference](https://learn.shayhowe.com/advanced-html-css/responsive-web-design/)


### Media Queries 
-  Media queries provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example.

3 ways to use media queries
1. using the @media rule inside of an existing style sheet
1.  importing a new style sheet using the @import rule
1.  linking to a separate style sheet from within the HTML document

The media query expression that follows the media type may include different media features and values,

### Logical Operators in Media Queries
> Logical operators in media queries help build powerful expressions. There are three different logical operators available for use within media queries, including and, not, and only. [Reference ](https://learn.shayhowe.com/advanced-html-css/responsive-web-design/)


**NOTE**  *Omitting a Media Type - When using the not and only logical operators the media type may be left off. In this case the media type is defaulted to all.*

### Media Features in Media Queries
1. Height and Width
1. Orientation
1. Aspect Ration
1. Resolution
1. Other Media 

**NOTE:** *Turning off the ability to scale a website is a bad idea. It harms accessibility and usability, preventing those with disabilities from viewing a website as desired.*

All notes are from [RWD](https://learn.shayhowe.com/advanced-html-css/responsive-web-design/) - Shay Howe

## All About Floats

**What is “Float”?**

*Float is a CSS positioning property. To understand its purpose and origin, we can look to print design. In a print layout, images may be set into the page such that text wraps around them as needed. This is commonly and appropriately called “text wrap”.*

Aside from the simple example of wrapping text around images, floats can be used to create entire web layouts.

**NOTE:** *While floats can still be used for layout, these days, we have much stronger tools for creating layout on web pages. Namely, Flexbox and Grid. Floats are still useful to know about because they have some abilities entirely unique to them, which is all covered in this article.*

#### Techniques for Clearing a Float
1. Empty Div method
1. The Overflow Method
1. The Easy Clearing Method

**The Empty Div** - is just that - a div  `<div style="clear: both;"></div>`

**The Overflow Method** - relies on setting the overflow CSS property on a parent element. *Also bear in mind that the overflow property isn’t specifically for clearing floats. Be careful not to hide content or trigger unwanted scrollbars.*

**Easy Clearing Method**  
`.clearfix:after { 

      content: "."; 

      visibility: hidden; 

      display: block; 

      height: 0; 

      clear: both;
}`


#### Problems with Floats
1. Pushdown
1. Double Margin Bug
1. 3px Jog
1. Bottom Margin Bug

[Video on Floats from CSS-Tricks](https://youtu.be/fyWdofSeukE)


## Bookmark/Skim

## [Don’t Overthink It Grids](https://css-tricks.com/dont-overthink-it-grids/)

ARGH!  more fun CSS!

#### [CSS Floats Explained By Riding An Escalator - If you took Code 201, review this article. If you did not take Code 201, this is Essential reading.](https://www.freecodecamp.org/news/css-floats-explained-by-riding-an-escalator-57fa55232333/)

I took 201!  Yeah - good read though!

**NOTE:** *The next thing you know, your newly floated elements jump out of your carefully chosen order, and stick to the side of your div like a magnet. The phrase “unintended behavior” comes to mind.* ===>  This is totally me!  OMG!





#### [SMACSS Official Documentation](http://smacss.com/)

Already used this for the labs. Still have some clarification questions for lexture.


## Intro to CSS
Page 227 Chapter 12




## CSS <img src="images/eggnog.jpg" height="300px" align="right">

Cascading Style Sheets - one file that represents the look of your HTML pages. The Presentation of the HTML

## Layout - 
Style sheets is the presentation of the HTML to show color, branding and makes the pages look uniform.

## RGB  
red Green Blue - all colors are made of of these three basic colors

``` rgb(14, 115, 225) ```


## RGBA
Alpha - adding Opacity to the color

``` rgba(14, 115, 225, .45) ```

## HSL 
hue saturation light
hsl ( Hue =0 - 360, Saturateion =% and Light = %)

``` hsl(0,75% 100%)```

## HSLA
Alphe Value - adds opacity to the color  value is 0 - 1.0  Transparency - adding white or black to the color

``` hsla(15, 75%, 100%, .45)```

#### Heirachry of colors
Some browsers don't allow for elaborate colors, so when using colors, Two step rule for browsers
1. Use a HEX, Color Name, or RGB
2. Use RGBA Value
If the browswer recognizes the RGBA value, everything is great - if not it falls back to Rule 1

[Reminder of the Color - The Devil Wears Prada](https://www.youtube.com/watch?v=Yj8mHwvFxMc)

## Hex codes  
``` #ff3344 ``` # followeed by 3 pairs of letters and numbers to represent RGB

``` color: #ff33ff;```


## Anatomy of CSS

• Rule - CSS have rules and inheritance within the code. 

## Selectors  Page 237. 292

element, universl, class (begins with periods), id (begins with a #)


p {
    
    color: black
}

	• Rule - Last Rule - So if you use two <p> rules, it will use the second as that 

	• Inheritance - When creating style in the <boby> the child elements will inherit the style





### Selector 
	Emmet Syntax allows you to put a few letters in and you get the syntax.  There is so much more to explore.  

#### Property & value
- Property - Color is the property
- Value - Black is the Value

### Declaration 

property value pair


### Curly braces  

used to created the code for the CSS and is also used in JS

### Class and ID Attributes

Difference between id and class attribute: The only difference between them is that “id” is unique in a page and can only apply to at most one element, while “class” selector can apply to multiple elements. 
> [GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-an-id-and-class-in-html/#:~:text=Difference%20between%20id%20and%20class,can%20apply%20to%20multiple%20elements.)






[go back](README.md)
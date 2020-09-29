# Reading Class 5
####From the Duckett HTML book:

## Chapter 5: “Images” (pp.94-125)
- The `<img>` element is use to add images to a web page
- you must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content onf an image
- You shoulse save images at teh size you will be using them on the wweb page and in the appropriate format
- photgraphs are bes saved as JPEGS inllustration or logos are use flat colors are better saved as GIFs or PNG.

choosing images for your site.
1. images should be relevant
1. convey information
1. convey the right mood
1. be instatly recognisable.
1. fit the color palette

**NOTE: images should be stored in their own folder.**

`<img src ='images/imagename.jpg' alt ='Some Text' title='some text'>`
***align, height, and width are now in CSS***

3 rules for creating images
1. ave images in the right format
1. save images at the right size
1. measure images in pixels

Vector Images differ from bitmap images and are resolution-independent. Vector images are commonly created in programs such as Adobe Illustrator

**HTML5 - `<figure>` and `<figcaption>`**

`<figure><img src><br><figcaption></figcaption></figure`>


## Chapter 11: “Color” (pp.246-263)
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

##### NOTE: If the browswer recognizes the RGBA value, everything is great - if not it falls back to Rule 1

[Reminder of the Color - The Devil Wears Prada](https://www.youtube.com/watch?v=Yj8mHwvFxMc)

## Hex codes  
``` #ff3344 ``` # followeed by 3 pairs of letters and numbers to represent RGB

``` color: #ff33ff;```




## Chapter 12: “Text” (pp.264-299) This is a class all it's own!


### There are properties to control the choice of font, size, weight, style, and spacing
- Serif - has the extra details
- Sans-serif - extra details are removed
- monospace - every letter is set width
- weight - light to Black
- style - normal, italic or oblique
- stretch - condensed, regular Extended




### there is a limited choice of fonts that you can assume most people will have installled

- pg 253 is where the properties start for sytling fonts.
- Design on a MAC the fonts should look fine, but you should always test them on a PC
- Design on a PC a MAC should be fine.





### if you want to use a wider range of typefaces, there are several options. But you need to have the right license to use them.

Not all computers have their own Typefaces. MACs have the most so PCs have to be tested. 

### you can control the space between lines of text, individual letters, and words.  Text can also be aligned to the left, right, center or justified. it can also be indented

- Use CSS to control these properties per element

### you can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.

[go back](../README.md)
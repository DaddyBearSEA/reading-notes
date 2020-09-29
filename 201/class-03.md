# Class Reading Day 3

#### From the Duckett HTML book:

## Chapter 3: “Lists” (pp.62-73)

Three types of Lists
- `ol` - Ordered List usually has 1, 2, 3 depending on style sheet
Reset.css for class removes this attribute so you have to add it back in your style.css

- `ul` - Unordered list - Tend to have a bullet but you can style this in CSS
- `dl` - Definition list automatically indent- I'm sure you can change this in CSS

You can nest list but adding another type of list.  think of Outlines within WORD.



## Chapter 13: “Boxes” (pp.300-329)

### CSS Treats Each HTML Element as if is has its own box
### Use CSS to contol the dimensions of a box
- Box Dimentions = width, height 
- limiting height / width = min-width, max-height etc
- Overflowing Content = allows you to put scroll bars in where content is too long for the box.


### CSS also controls the borders, margins and padding for each box - Bear Man Pig


Bear Man Pig 
1. Bear = Border
2. Man = Margin
3. Pig = Padding

when you create a box, you have extra pixels included in that box - BMP

TRBL - Syntax for BMP is Top, Right, Bottom, Left


#### **Remember: a box includes the total amount of pixels of the margin, padding and border**

Putting things inside 'boxes' makes css easier

### CSS display and Visibility properties can hide elements
- shorthand border: [margin] [style] [color]
- cetering content martin: 10px auto 10px auto => set the left and right to Auto
  > 1. 10 px = Top margin
  > 2. auto = right margin to auto size within the box
  > 3. 10 px = bottom margin
  > 4. auto = left margin to auto size within the box




### block level boxes can be masde into inline boxes and vice versa
**Display property**
- inline => created a block levelelement to act like an inline element
- block => cuases an inline element to act like a block level element
- inline-block => causes a block -level element to flow like an inline element, while retaining other features of block-level element
- none => hides an element from teh page. But can be seen in 'view' source.

display: inline;

**Box Shadows, Rounded Corners and Elliptical Shapes** allows you to  create sytling around your boxes


### Legibility can be imporoved by controling the width of boxes containing text and the leading.

Bear Man Pig again

### CSS3 allows the ability to create image borders and rounded boarders






#### From the Duckett JS book:

## Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

If...Else statements

> *the if...else state checks a condition*

> *if it resolves to "TRUE" the first code block is executed.*

> *If the condition resolves to "FALSE" the second code block is run instead.*

Switch Statment

> *A switch statement starts with a variable called the switch value.*

>*Each case indicates a possible value for this variable and the code that should run inf the variabel matches, so if your varialbe is equal to 2, then case 2 would respond with a condition.

Falsy and Truthy pg 167
- Falsy values are treated as if they are false.

- Truthy values are treated as if they are true. 

*checking equality and Existend and short circuit values are important to understanind true and false in a condition*


**type coercion can lead to unexpected values in your code. Always use STRICT operators** (pg 166), it can give you different results when using a strict operator.

### loop
just as it says, you loop through code until a certain condition is set to false.  A condition would be met and then the code would stop running.

### while
code that is run until a condition is true. Once False is obtained the code stops running.

### for
For loop uses a counter as a condition

### condition
A Condition is a specific True or FALSE statment

### increment
``` 'i++' ```

###decrement
``` 'i--'  ```

Logical Operators

``` '||' ```  logical or

``` '&&' ``` logical and

``` !  Bang ```
``` !== - not strickly equal```
``` <=  Less than or equal to ```


``` if (true) {

    // do the thing

}  else {

    // do this other thing

 } ```



  
```  while(true){

       // do the thing

}
```

This FOR loop is very important

```
  var count = 5

    for(var i - 0; i < count; i++ ){

    // does the thing

}

```
``` isNan("")

while loops are very important

``` 
var count;
while (isNan(count) || count ===''){
  count=prompt('Enter a number please.')

}
]




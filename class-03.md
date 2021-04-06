Read:03 HTML Lists, CSS Boxes, JS Control Flow

Chapter 3 

# Chapter 3

## Lists

*There are three different kinds of lists.*

* Ordered lists -each item on the list is numbered for example steps of a process.
* Unordered lists -Bullet points.
* Defenition lists -Term with explanation/defenition of that term.

## Ordered List

* An ordered list is created using < ol >.
* In between the ordered list to begin a list item use < li > for each item within that ordered list.

## Unordered List

* To begin an unordered list start by using the < ul > element.
* In between the unordered list tage you will use < li > to start bullet points.

## Definition Lists

* To create a definition list start with < dl > and then put the term being defined in between < dt > and the definition itself in < dd >.

## Nested List

* If you want to put a list within a list **nested list** type the < ul > list tag and then start each word in the list using < li > and make sure to close it.

Chapter 13

# Boxes

## Box Dimensions

- **Setting specific dimensions for a box is done by using width and height.  To specify the box size you can use pixels, percentages, and em's.**

- Pixels is the most popular way to specify size.  The allows for better and more precise way of cotroling the size of the box.

- Percentage is relative to how big the browser window.  When you pic a percentage it determines how big the browser is and makes the box bigger or smaller depending on the browswer size.

- em's are determined by the text size within that box.

## Limiting Width

- If a user changes the size of their window the box within that window should change with that size.  Using the min-width property will determine how small that box is allowed to go and the opposite happens with max-width.

## Limiting Height

- Just like the above mentioned, you can set a minimum height and a maximum height for the box dependant on how the browswer window is manipulated.  Using the min-height and max-height will let you manipulate the box's height.

## Overflowing Content

- Overflow allows you to take content that is too long for the box and either hide it using hidden, this will cut off the extra information if it is too long for the box, or scroll will add a scroll bar so you can manipulate the text up and down so the user can read all the information.  

## Border, Margin, and Padding

- Border - The border is the spacing bewtween all boxes.
- Margin - The margin sits outside of the border and can be manipulated to make a gap between boxes.
- Padding - This is the space between the information in the box and the border.

## Border Width

- the border-width prperty controls the width of the border.  This can be manipulated using pixels or other values such as thick, medium, or thin.

- You can also control one specific side at a time by adding which side you want to manipulate such as border-top-width.

## Border style

- The border style allows the develor to choose  how it looks like.

- **Values that work with border style are**

- solid

- dotted 

- dashed

- double

- groove

- ridge

- inset

- outset

- hidden or none

## Border color

- Using the border-color element allows you to change the color of the border.  This too can be manipulated by each individual side or all together.  

## Padding and Margin

- Padding is the spacing bewtween what is insdie the box and the inside broder of the box. This too can be manipulated on any side.

- Margin controls the spacing bewtween boxes and can too be manipulated as a whole or specified sides.  

**To center text within the box you want to set the right and left margins to auto**

Review Chapter 2: “Basic JavaScript Instruction

# Arrays

- An array allows you to store a list of values not just a single one.  

- When creating an array you want to give it a name just like you would do for any other variable you create.  When creating an array you want to start with var and then the name of the array.  Then you will put the value of the array with in []. Values within the array are all in single quotes and separated by commas.  The array should finish with a semi colon after the brackets.

# Chapter 4 Decisions and Loops from switch statements

## Switch

- When different conditions are present a switch allows for different actions to happen dependant on the conditions that are presented.

- When building a switch begin with switch and in parenthesis you will write the name of the variable.  Use curly brackets to begin list each case by number and what you want to happen if that condition is met.  If the condition is not met it will move to the next level.

**There are 5 basic different kinds of data types**

- String - this is made up of letters
- Number - Made up of numeric characters
- Boolean - Are true and false
- Null - Has no value
- Undefined - This variable has not been assigned a value.

## Loops

- Loops runs a block of code checking to see if the condition is true.  If the condition is true it will continue going until the condition is false then it stops.

- For - This is used if the code has a specific amount of times it has to run
- While - This is used if the developer doesn't know how many times the code has to run.
- Do while -This is similar to "while" but will run at least once even if the condition turns out to be false.


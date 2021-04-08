Read: 05 - HTML Images; CSS Color & Text

Chapter 5

# Images

## Stock Photos

* When putting a photo on your site, you can pay for stock photos.  Below are sites that you can purchase pictures from to use on your site.  Do not take them and use the without paying because they are copyright.

- istockphoto.com
- gettyimages.com
- veer.com
- sxc.hu
- fotolia.com

## Insterting an image

* When inserting an image use the < img > element.  Inside that element you want the browser to know where to call that imgae from.  You would use src= and in "" you would let it know what directory to pull it from and the image name after the "" if you want to give a description of the photo you would add alt= and in "" you would give the description.  You can also title the image so if the cursor hovers over the image it shows a title for the photo.  You would do this by adding title= and in "" you would add the title.

## Height and Width of the Image

- Within the < img > element you can add the height and width of the photo.  Use the height= and width= to determine what size you want your picture to be.

## Where to place your image.

-There are three places you can set your image.

* Before a paragragh
* Inside the start of a paragragh
* In the middle of a paragragh

- It's important to know where to put the image depending on whether it is a block or inline element. Block elements always start on a new line. Inline sit in a block level element and do not start on a new line.

- Controlling where the image is should be done in CSS but can be used in HTML by using the element align="" and insert either right or left on the "".

* Left aligns the image to the left and the words flow to the right
* Right aligns the image to the right and the words flow to the left.
* Top aligns the first sentence of the text at the top of the image.
* Middle aligns the first sentence to the middle of the image.
* Bottom aligns the first sentence to the bottom of the image.

**The above functions are old code and should be used sparingly as they can be controlled with CSS.  Some old websites still use it instaed of CSS.**

## Three rules for creating images

* Save images in the right format such as jpeg, gif, or png
* Save images at the right size
* Measure images in pixels

## Image Formats

* jpeg -When an image has a lot of colors it is best saved as a jpeg.
* gif -When an image has an area that is filled witht he same exact color it is best to save it as a gif or png.  Example would most likely be logos.

Chapter 11

# Color

## Foreground color

* RGB Value - This is a number that expresses the amount of Red Green Blue makes up the color seen.
* Hex Code - Six digit code that represents the amount of Red Green Blue in the color.  This number is preceded by a "#".
* Color Names - There are 147 colors that are predefined that you can call by name.

**To insert a color place the name or number in between / * and * /

## Background color

* Use background-color: and then add the color name.

**When choosing a background color keep in mind to make sure you chose a color that there is enough contrast so text is legible.**

Chapter 12

# Text

## Specifying Typefaces

- font-family - This allows you to choice the typeface that you will be using in your elements.  The type face has to be one that is installed on the user's computer so you should sperate different typefaces with a comma to be read on any computer.

- font-size - Font sizes are specified in three different way.  Pixels, percentages, and EMS.

- @font-face - If a specific font size is not installed on the user computer, this will allow you to copy a link path to that specific font so it can then be seen on the user's computer.

- font-weight - This controls how bold the text on the page is.  It can be set to either bold or normal.

- font-style - This allows you to set the kind of italics you want.  Three different kinds of italics are normal, italic, and oblique.

- text-transform - This allows you to make your text all uppercase, lowercase, of capitalize **this makes the first let of each word capital**.

- text-decoration - This allows you to change the decoration of your text using none **removes any decoration** underline, overline, line-through,, and blink **this makes the text blink or flash on the page**.

- line-height -This adjust the veritcal line height of the text in relation to the words above it.

- letter-spacing This allows you to put a specific amount of space between letters in a word.  

- word-spacing - This is the same thing as letter spacing except it is the space between words.

- text-align - This allows you to align the text in four different directions; left, right, center, and justify **This allows the text to take up the whole page with the exception of the last line**.

- vertical-align - This is to help align images to the text not the text to the image.

- text-indent - This allows for the indentation of the first sentence.

- text-shadow - This allows you to put a shadow box behind the text.

- : first-line and : first-line - This allows the ability to make the first letter of a sentence large and then the ability to increase the size of the rest of the sentence.

- :link - This allows to set a style for a link that has not been used to differentiate between what has been visted and what has not. : visited is the opposite of that.

- :hover - Alows some form of styling for where the mouse point is hovering over it can change the look

- :active - Make buttons and other objescts seem like they are more interactive and real. 

- :focus - This gives focus to an element so it is easier to see.

## Attribute selectors

- Existence - []
- Equality - [=]
- Space - [~=]
- Prefix -[^=]
- Substring - [*=]
- Suffix - [$=]

JPEG vs PNG vs GIF

# JPEG PNG GIF

Use JPEG when the image you are trying to link is a natural scene or a photo.  If the image needs transparency it is bet to use PNG. GIF is used for images that have action in them such as a looping video.  

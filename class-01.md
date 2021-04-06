# Introductory HTML and JavaScript

## HTML Chapter 1

## Structure

 *Webpages use structure to give information in a form of order.  Very similar to when writing a paper using a word processor.*

1. HTML code is made of characters that live inside angle brackets.
 "< html > < /html >" - These are called HTML elements. One is open the other is closed due to the slash inside the bracket. Everything is written in between these brackets.

2. Inside the HTML brackets are the Body "< body >" ,Main heading "< h1 >", subheading "< h2 >", and paragraghs "< p >". (note the spaces in the brackets, when writing HTML do not have the spaces in the brackets)

3. Attributes are made of two parts "name and value.  For instance < p lang = "en - us "> would show the name is the language (lang) and the value would be what language is being used (us-english).  Attributes give you more information about the contents of an element.  The name and value are seperated by an "=" sign.

4. Body, Head, and Title

- Body -This is where headings and paragrghs live.
- Head -Normally this comes before the body.  This tells what is going on, on the pages versus what is in the information given on the pages like the text.
- Title -The title is normally within the head of the page.  The title is what shows on the tab of the  page when it is open.

## Chapter 8

# Extra Markup

## Doctypes

- HTML5 - < !DOCTYPE HTML >
- HTML4 - < !DOCTYPE HTML PUBLIC >

## Comments in HTML

- If you want to add a comment in your code that will not be seen by the user you would enter the text in < !-- --> with the text between the -- --.

## ID Attribute

- TO make an ID attribute in paragragh element after the "p" add id=""> and put the name of the ID in the "".

## Class Attribute

- A class attribute allows you to identify in the code portions that are important.

## Grouping text & elements in a block

- using the < div > element will allow you to group text and elements in a box

## Grouping text & elements inline

- You can group a line of text by using the < span > element.

## Chapter 17

## Traditional and New HTML Layout

- In older versions of HTMl the layout was different than the new. Everything in the body would be within a < div > element and would have an ID associated with it.  These div elements would indicate the purpose of each attribute.
- In the new HTML format the < div > element is still used but not as frequently.  New elements such as < heading > and < article > are used.  This allows the developer to skip to different portions of their code to work on what they want to work on at that moment and go back as needed.  The layout is easier to follow.

## Elements

**header** - The header contains the site name and is wehre the main navigation of the page is found.
**footer** - The footer is where the author of the site would put any copyright or trademark information.
**nav** - The nav element allows you to have links that will direct you to different parts of the site.  An example would be the home about or contact us.
**article** -This element allows you to have a specific piece of information blocked off fromt he rest of the page as its own stand alone portion.  You can nest multiple article within each other.
**aside** - This element can live in two different places.  It can live inside an article or outside of an article.  If it lives in an article the aside needs to be relavent to the article it is nested in.  If it's outside of the article it would have to be relavent to the whole page and not just a small portion.
**section** - The section element allows you to group related content together. an example given in the book would be a section with recipes holding multiple recipe links.  Each section would have their own heading.
**hgroup** - An hgroup allows you to group multiple headings together so they are treated as one individual heading. This element seems to be less popular and is not used regularly.
**figure** - This is used to insert a figure that is important to the section you are working on. Examples would be an image or video that is relevant to the section you are working on.  
**figurecaption** - This element allows you to put a caption attached to the figure you inserted.  So if you insert a picture of a dog the caption may let the user know what kind of dog it is or what it is doing.
**< a >** - This element allows you to grab a piece of code and turn that entire block into a link.

**In older browsers HTML5 may be an issue as it does not understand the new elements, therefore it treats them like inline elements.**

# Chapter 18 

# Process and Design

**The idea behind process and design is to make sure you are building a site that is consistently inline with the audience that will be using it.  There are many different things to think about when creating your site whether is is for a specific age range, where they live or if it's for individuals or a business.

## Things to think about when creating a site

- While some people may stumble across you site by accident you will still want to make your site targeted.  Individuals will need a reason to visit you site whther it is to gather information or just to browse and shop.

- It is important to make sure you have informative data for the people visiting your site.  If you lack the information that the user is looking for then it can affect how often a user visits your site.  Make sure the information is relavent to what your site is about.

## Site map

- A site map will give you an idea on how your page is structure.  It can be built like a tree with branches so you know what information needs to go where so that the site functions seamlessly and the user can gather the information they seek easily.

## Wireframe

- It is best practice when thinking up a site to have a wireframe.  A wireframe is essentially a sketch of what you want the website to look like.  Where things will go so you have an idea in your head.  It doesn't necessarly mean that the website will look like your sketch but it give you a roadmap or guide as to where to start. 

## Using design

- When desinging your website you need to make sure that you are bulding it in a way that a user is able to navigate easily.  If a user has to go searching for the information there is a possibility they may opt to go elsewhere to find the information they seek.  Making sure the site is visually pleasing to the eye and is user intuitive is key.  Make sure the content you are providing is relavent and organize it in a way that information is easy for the user to find.  Make different parts of the page look more distict that others so as to not confuse the user as to how to get to where they need to go.  For example use different kinds of buttons to help the user know which button goes to what.

# JavaScript

## Chapter 1


## What is a script

- A script is essentially a form of instructions that a computer can understand  It would be the instruction manual of how something is supposed to be built and act.  When it comes to building your script it has to be very precise as the computer follows only the instructions you give it.  Unlike a person you need to give step by step guidance in order for the machine to act the way you want it to.  If you do not give precise information an important step may be missed and the outcome will not be what you intended it to be.

**Three steps to writing a script**

- Figure out what you are trying to accomplish.
- Designing the script is the next step.  You can do this in a way that each step is individually planned out in the order it needs to go in so that you can get to your goal.
- Lastly each individual step in the language that the computer needs to be able to understand it.  

** In order to become fluent in a coding language you need to be able to undertands the **vocabulary** and the **syntax**.

Vocabulary - The are the words that you need to code in that the computer understands and can execute.

Syntax - Is essentially the grammar of the coding language.  Where to put what where so the instructions are understood by the computer.

## Objects and Properties

- Objects - These are the "things" with in the code.
- Properties - These are how those things look act act like and are specific to the object.

## Event

- An event is a way for a computer to let you know that something has happened.  An exaple would be if you press a button it generates the next step of the process or signals you of the event.

## Method

- When a code is run you need to understand what the result is after the task is complete.

## How HTML, CSS and JavaScript work together

- HTML displays the content that the developer is trying to convey, CSS gives the content in HTML style and makes it look more like a site instead of just words on a page. JavaScript give the page its behavior such as when you click on a button it takes you to a different page within the site or brings up a form.

**When creating JavaScript you want to create it on it's own page.  You will then link it to you HTML so it draws the instructions from your JS file.
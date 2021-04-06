#HTML

# Chapter 2

## Text

*Tags also known as "markups" provide extra meaning to and allow browsers to show the proper structure of the page.*

1.There are two different kinds of Markups.

- Structual -These describe the heading and paragraghs.
- Semantic -These provide extra information such as emphasis in a sentence.

## **Structural markups**
1.Headings -There are six levels of headings from  < h1 > - < h6 >.  The higher the number the smaller the heading.

2.Paragraghs -If creating a paragragh make sure to put the text between < p > and < / p >.  When finished with a paragraghs start a new paragragh in the same manner.

3.Bold and Italics -enclosing a word between < b > and < / b > will make that word bold or < i > and < / i > will make the word italic.

4.Superscript or Subscript -Supersript < sup > allows you to put an exponent above a number or word and Subscript < sub > allows you to put and exponent under a number or word.  Make sure to use a closing tag as well.

5.Line Breaks and Horizontal rules - You can add a line break in a paragragh by entering a < br />between the text that you want to break up from the paragragh. If you want to break up a paragragh and insert a line you would use the < hr /> for a horizontal line between text.

## **Semantic markups**

1.Strong and emphasis -To bolden a word to make it more strong you would add an open and closed  mark up using < strong > to subtly change the meaning of a sentence you may want to emphasize a word within the text by using the markup of < em >.

2.Quotations -Sometimes a quote can be longer than a sentence.  In this instance making a block quote would be appropriate to block it sperately within the paragragh so it stands out. Use < q > for shorter quotes.

3.Abbreviations and Acronymns -If an acronym or abbreviation is used  < abbr > should be used to list what that abv or acronym means. For example < acronym title="Proffesor">Prof< /aacronym>

4.Citations and Definitions - To cite text when doing research you would use the < cite> open and closed. You would only use the define if it is the first time in the text that you are defining something such as a word using the < dfn > tag open and closed around the word you are trying to define.

5.Author details -If contact information such as an email is going to be inserted as a hyperlink the < address > mark up would be used.

6.Changes to content -If you want to remove text you can put it into < del > open and closed and then insert a word after using the < ins > open and closed.  If you want to just mark a word out an < s > opened and closed would be used.

# Chapter 10 CSS

## Understanding CSS

To make sense of CSS you have to picture that all the information that is in each HTML element is enclosed in a box.  Each individual box can be manipulated by using CSS.  With CSS you create rules in those boxes and that controls how that box is supposed to be presented.

**For a CSS rule to work it has to have two parts.  A selector and a declaration.**

- The selector indicates which element in your HTMl the rule applies to.
- The declaration indicated how that element should act.
- You must put the declaration in { } and seperate each rule with a ;
- The CSS doesn't have to be written in the HTML.  You can have it under all the HTML 
- You can write your CSS on a different page and use the < link > element to let your html know where to find the rules.

# External CSS

**href** - Specifies the route to the CSS file
**type** - Specifies the type of document being link to.
**rel** - Specifies the relationship between the HTML and the file it is linked to.

# Internal CSS

**< style >** - Allows you to use CSS within the HTML itself.

## CSS Selectors

* Universal selector
* Type Selector
* Class Selector
* ID Selector
* Child Selector
* Descendant Selector
* Adjacent Sibling Selector
* General Sibling Selector

# Chapter 2 JS

## Basic JavaScript Instructions

## Statements

- So a computer can understand waht you are trying to accomplish you have to write instructions that a computer can understand.  Each individual instruction or step is referred to as a statement.  After every statement is made you must end it with a semicolon to let the computer know that the step it just made is over and it should then go onto the next step.  Keep in mind that Javascript is case sensitive.  When writing your statements each statment must start on a new line.

- To make sure you and someone else that may be revieweing your code it is a good idea to write comments letting yourself or another person know what that specific code is supposed to do.  In order to write in a comment press command and the forward slash and it will default to comment for a single line comment. If you are going to leave a multiline comment use the "/* and */"  Be descriptive when writing your comment.

## Variables

- A variable is a set of instructions that are stored in order for the computer to perform the set of rules you want it to follow.

## How to Declare a variable and Assign a Value

- Before you are able to execute variable you must call on it to use it. First you must use a key word such as "var". This way JavaScript knows that it is creating a variable. You must give the variable a name or an identifier.  If you name the variable you can use one word but if the variable name is more than one word you need to use camelCase.  camelCase is when you capitalize the first letter of each word after the first word.

-Once your variable has been named you need to give it a value.  This is the code that the variable will call on when it is in use.

## Data types

- **There are three types of data types**

- Numeric Data Type - This kind of data type deals with numbers.
- String Data Type - This data type deals with letters and other characters.
- Boolean Data Type - This data type deals with "true" or "false"

# Chapter 4 JS

# Decisions and Loops

##Three concepts to determine which path to take

- Evaluation - This analyzes whether two value match an expected end result.
- Descision - This determine whether the goal was reached or not if it made the goal then it takes on path if it did not meet the goal it goes down another path.
- Loops - This is used if you want something to happen more than one time.


## Operators

 -== -is equal to
 -!= -is not equal to
 -=== -Strict equal to
 -!== -Strict not equal to
 -> -Greater than
 -< -Less than
 ->= -Greater than or equal to
 -<= -Less than or equal to
 -&& -Logical and
 -|| -Logical or
 -! -Logical not

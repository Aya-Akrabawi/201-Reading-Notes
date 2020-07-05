## Introductory HTML and JavaScript
**text tags**
1. Headings and paragraphs:
* main heading: \<h1>\</h1> 
* sub headings (from h1-h6): \<h2>\</h2>
* paragraph: \<p>\</p>
2. Bold, italic, emphasis
* bold \<b>\</b>
* italic \<i>\</i>
3. Structural and semantic markup: 
**Structural markup:** the elements that you can use to
describe both headings and paragraphs
**Semantic markup:** which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on.
* The \<sup> element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 2<sup>2 </sup> and 4<sup>th</sup>
.
* \<sub>
The \<sub> element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical
formulas such as H<sub>2</sub>O.

* Line Breaks \<br />
* Horizontal Rules: To create a break line between themes \<hr />
* Strong t indicates that its content has strong importance. \<strong>\</strong>
* Emphasis: indicates confirms that subtly changes the meaning of a sentence. \<em>\</em>
* Quotations: \<blockquote> which used for longer quotes that take up an entire paragraph & for shorter quotes that sit within a paragraph we use \<q>\</q>
## Introducing CSS:
**CSS:** let you present your web site with deffirent styles, by treating each HTML element as it is inside a box and you wantt to apply rules on it to indicate its style, and rules in CSS compresses from: 
``` Selector {Indicator} ``` which is writen like ``` slector { property : Value ; } ``` 
 * selectors specify the elements the rule applies to.
 * declarations: that indicate what these elements should look like. which includes the the properties of the element that you want to change, and the values of those properties.



![check this Image](Images\CSS-parts.png)


**Example**
``` body {font-family: arial; background-color: rgb(185,179,175);} ```
```h1 {color: rgb(255,255,255);} ```



**Note: CSS rules usually appear in a separate document, although they may appear within an HTML page.**

## IMPORTANT syntaxes: 
- uses the <link> element to indicate where the CSS file is located. ``` <link href="css/styles.css" type="text/css"rel="stylesheet" /> ```
-  include CSS rules within an HTML page```<style type="text/css"> body {font-family: arial;</style>``` 
- add identity in HTML and ```  <h1 id="top">Kitchen Garden Calendar</h1>```
- CSS selector:


![Css Selectos](Images\CSS-selectors.png)


- /* change color by name */ ``` h1 {color: DarkCyan;}```
- /* change hex by code */ ```h2 {color: #ee3e80;}```
- /* change rgb by value */ ```p {color: rgb(100,100,90);}```


## Notes on Color in CSS:
1. Color not only brings your site to life, but also helps convey the mood and evokes reactions.
2. There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
3. Color pickers can help you find the color you want.
4. It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
5. CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
6. CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.

## JavaScript:
- we use javaScript after doing HTML and CSS to make websites more interactive,interesting, and user-friendly ( change the content of an HTML page while it is loaded in the browser), by:
1- *ACCESS CONTENT 2- *MODIFY CONTENT 3- *PROGRAM RULES  4- *REACT TO EVENTS 
*A script is a series of instructions that a computer can follow to achieve a goal. 
*To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.
* Start with the big picture of what you want to achieve, and break that down into smaller steps:
1: DEFINE THE GOAL 2: DESIGN THE SCRIPT (by flowchart) 3: CODE EACH STEP

![flowchart](Images\tasks.png)
![tasks](Images\steps.png)

# Comparison and Logical Operators


**Comparison Operations are:**

== | != | === | !== | < | > | <= | >= 
---|----|-----|-----|---|---|----|----
equal to | not equal to | strict equal | strict not equal | less than | greater than | Less than or equal | greater than or equal


**Logical Operators are:**
it allow you to compare  the results of more than one comparison operator.


&& | || | ! 
===|====|===
logical AND | logical OR | logical NOT


![example](Images\Logical-oerator.png)

**Loop Counters (for & while Loop**
**Loops** : checks a condition, if it's true, the code will run, andd keep checking if it's true until the condition returns false.


![expression](Images\Loop.png)



**For Loops** : the condition specifies that the code should run a unknown number of times from the begining. It should continue to
run as long as a condition is met. 






![how it works](Images\For.png)



**While Loops** :
the condition specifies that the code should run a unknown number of times from the begining. It should continue to run as long as a condition is met. 

# Comparison and Logical Operators


**Comparison Operations are:**

== | != | === | !== | < | > | <= | >= 
---|----|-----|-----|---|---|----|----
equal to | not equal to | strict equal | strict not equal | less than | greater than | Less than or equal | greater than or equal


**Logical Operators are:**
it allow you to compare  the results of more than one comparison operator.


&& | || | ! 
===|====|===
logical AND | logical OR | logical NOT


![example](Images\Logical-oerator.png)

**Loop Counters (for & while Loop**
**Loops** : checks a condition, if it's true, the code will run, andd keep checking if it's true until the condition returns false.


![expression](Images\Loop.png)



**For Loops** : the condition specifies that the code should run a unknown number of times from the begining. It should continue to
run as long as a condition is met. 






![how it works](Images\For.png)



**While Loops** :
the condition specifies that the code should run a unknown number of times from the begining. It should continue to
run as long as a condition is met. 
















## Read: 06 - JS Object Literals; The DOM
**Objects:**
 set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names: 
  VARIABLES >>> PROPERTIES
  FUNCTIONS >>> METHODS
![objects](Images\object.png)
 **we can access a property or method in an object by Dot Notation**
 **we can also access properties using square brackets**
 ![Dot Notation](Images\DotNotation.png)

 ### DOM: Document Object Model
 **The Document Object Model (DOM)** specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window. 
![Areas Of DOM](Images\AreaOf-DOM.png)
**Dom Tree**: is a model of web page. 
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
**It consists of four main types of nodes.**
- THE DOCUMENT NODE: Every element, attribute, and piece of text in the HTML is represented by its own DOM node. At the top of the tree a document node is added; it represents the entire page 
- ELEMENT NODES: HTML elements describe the structure of an HTMLpage. (The ```<hl> - <h6>``` elements describe whatparts are headings; the ```<p>``` tags indicate where paragraphs of text start and finish; and so on.) To access the DOM tree, you start by looking for elements. Once you find the element you want, then you can access its text and attribute nodes if you want to. This is why you start by learning methods that allow you to access element nodes, before learning to access and alter text or attributes. 
- ATTRIBUTE NODES:
- TEXT NODES:
![DOM Tree](Images\DOM-Tree.png)

# Understanding The Problem Domain Is The Hardest Part Of Programming

**What is the hardest thing about writing code?**

* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable

*The more and more I write code, the more I learn that understanding the problem is the most critical piece to the equation. It is very difficult to solve a problem before you know the question.*


**If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:**

* Make the problem domain easier
* Get better at understanding the problem domain

*You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.*

# Object literals 

# creating an object:

**constructor notation**

*the new keyword and the object constructor create ablank object.*

*you can then add properties and methods to the object.*

* first you create anew object using acombination of the new keyword and the object() constructor function.

* next having created the blank object, you can add properties and methods to it using dot notation.

## you create instances othe object using the constructor function.

## the new keyword followed by acall to the function creates anew object.

## the properties of each object are given as arguments to the function.


* An object is a series of variables and functions that represent something from the world around you. 

* In an object, variables are known as properties of the object; functions are known as methods of the object. 

* Web browsers implement objects that represent both the browser window and the document loaded into the browser window.

* JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts


# The Document Object Model 

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas:

* MAKING A MODEL OF THE HTML PAGE 

*When the browser loads a web page, it creates a model of the page in memory.*
*The DOM specifies the way in which the browser should structure this model using a DOM tree.* 
*The DOM is called an object model because the model (the DOM tree) is made of objects.* 
*Each object represents a different part of the page loaded in the browser window.* 

* ACCESSING AND CHANGING THE HTML PAG

*The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser.*

## SELECTING AN ELEMENT FROM A NODELIST 

**There are two ways to select an element from a Nodelist: The item() method and array syntax. Both require the index number of the element you want**

# REMOVING ELEMENTS VIA DOM MANIPULATION 

* STORE THE ELEMENT TO BE REMOVED IN A VARIABLE

* STORE THE PARENT OF THAT ELEMENT IN A VARIABLE 

* REMOVE THE ELEMENT FROM ITS CONTAINING ELEMENT 

# VALIDATE INPUT GOING TO THE SERVER

* Only let visitors input the kind of characters they need to when supplying information. This is known as validation. Do not allow untrusted users to submit HTML markup or JavaScript.

* Double-check validation on the server before displaying user content/storing it in a database. This is important because users could bypass validation in the browser by turning JavaScript off.

* The database may safely contain markup and script from trusted sources (e.g., your content management system). This is because it does not try to process the code; it just stores it.


# The Document Object Model 

* The browser represents the page using a DOM tree. 

* DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes. 

* You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax. 

* Whenever a DOM query can return more than one node, it will always return a Nadelist. 

* From an element node, you can access and update its content using properties such as textContent and inner HTML or using DOM manipulation techniques. 

* An element node can contain multiple text nodes and child elements that are siblings of each other. 

* In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery). 
Browsers offer tools for viewing the DOM tree . 

# Form

**Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.**

**HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site.**

## Why Forms?

*The best known form on the web is probably the search box that sits right in the middle of Google's homepage.*

*In addition to enabling users to search, forms also allow users to perform other functions online. You will see forms when registering as a member of a website, when shopping online, and when signing up for newsletters or mailing lists*

**There are several types of form controls that you can use to collect information from visitors to your site.**

* ADDInG tEXt:text input , password input , text area

* mAkInG ChoICEs: Radio buttons , Checkboxes , Drop-down boxes 

* submIttInG Forms: Submit buttons , Image buttons 

* uploADInG FIlEs: file upload

# hoW Forms Work

* A user fills in a form and then presses a button to submit the information to the server.

* The name of each form control is sent to the server along with the value the user enters or selects.

* The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.

* The server creates a new page to send back to the browser based on the information received.


* visitors you will need a form, which lives inside a <form> element.

* Information from a form is sent in name/value pairs. 

* Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.

* HTML5 introduces new form elements which make it easier for visitors to fill in form


# Lists, tabLes and Forms 

## Table 

*width to set the width of the table*

*padding to set the space between the border of each table cell and its content*

*text-transform to convert the content of the table headers to uppercase*

*letter-spacing, font-size to add additional styling to the content of the table headers*

*border-top, border-bottom to set borders above and below the table headers*

*text-align to align the writing to the left of some table cells and to the right of the others*

*background-color to change the background color of the alternating table rows*

*:hover to highlight a table row when a user's mouse goes over it*

*give ceLLs Padding If the text in a table cell either touches a border (or another cell), it becomes much harder to read. Adding padding helps to improve readability.*

*distingUish headings Putting all table headings in bold (the default style for the <th> element) makes them easier to read. You can also make headings uppercase and then either add a background color or an underline to clearly distinguish them from content.*

*shade aLternate rows Shading every other row can help users follow along the lines. Use a subtle distinction from the normal color of the rows to keep the table looking clean.*

*aLign nUmeraLs You can use the text-align property to align the content of any column that contains numbers to the right, so that large numbers are clearly distinguished from smaller ones.*

# styLing Forms

**Styling text inputs and submit buttons is fairly easy. It is harder to get select boxes, radio buttons, and checkboxes to look consistent across all browsers**

**To achieve this, you might like to download the CSS files available at http://formalize.me. The author of this website has done the hard work of making**

**forms look consistent across browsers. Although the solution incorporates JavaScript, no prior knowledge of this is needed in order to implement the code.**


* In addition to the CSS properties covered in other chapters which work with the contents of all elements, there are several others that are specifically used to control the appearance of lists, tables, and forms.

* List markers can be given different appearances using the list-style-type and list-style image properties.

* Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent. 

* Forms are easier to use if the form controls are vertically aligned using CSS.

* Forms benefit from styles that make them feel more interactive.

# Event

## HOW EVENTS TRIGGER JAVASCRIPT CODE 

Select the element node(s) you want the script to respond to. 
For example, if you want to trigger a function when a user clicks on a specific link, you need to get the DOM node for that link element. You do this using a DOM query (see Chapter 5). 

Indicate which event on the selected node(s) will trigger the response. 
Programmers call this binding an event to a DOM node. 
The previous two pages showed a selection of the popular events that you can monitor for

State the code you want to run when the event occurs. 
W hen the event occurs, on a specified element, it will trigger a function. This may be a named or an anonymous function. 


* Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked). 

* Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon. 

* When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user. 

* You can use event delegation to monitor for events that happen on all of the children of an element.

* The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events. 




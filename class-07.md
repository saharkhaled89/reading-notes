## Domain Modeling

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an **object-oriented** model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

### Define a constructor and initialize properties

To define the same properties between many objects, you'll want to use a constructor function. Below is a table that summarizes a JavaScript representation of an `EpicFailVideo` object.

| Property     | Data              | Type    |
|--------------|-------------------|---------|
| `epicRating` | `1` to `10`       | Number  |
| `hasAnimals` | `true` or `false` | Boolean |

Here's an implementation of the `EpicFailVideo` constructor function.

```javascript
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail);
console.log(corgiFail);
```

As you can see, the constructor function is defined using a **function expression**. In other words, the variable `EpicFailVideo` is declared and then assigned a function with two parameters called `epicRating` and `hasAnimals`.

When the function is called, the data inside these parameters are stored inside the `this.epicRating` and `this.hasAnimals` properties respectively. Storing data within properties ensures any newly created object can access that data later.

After the constructor function definition, two objects are **instantiated** with the `new` keyword and their properties are **initialized** by calling the `EpicFailVideo` constructor function. After being instantiated and initialized, these objects are stored inside the `parkourFail` and `corgiFail` variables.

Finally, the two newly created objects are logged to the console.

![](https://i.imgur.com/G2bPElF.png)

# WhaT's a Table?

A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.

**basic Table sTrucTure**

**<table>: The <table> element is used to create a table. The contents of the table are written out row by row.**

**<tr>:You indicate the start of each row using the opening <tr> tag. (The tr stands for table row.)**

**<td>: Each cell of a table is represented using a <td> element**

* The <table> element is used to add tables to a web page.

* A table is drawn out row by row. Each row is created with the <tr> element.

* Inside each row there are a number of cells represented by the <td> element (or <th> if it is a header).

* You can make cells of a table span more than one row or column using the rowspan and colspan attributes. For long tables you can split the table into a <thead>, <tbody>, and <tfoot>.

# Creating an object: constructor notation

**the new key word and the object constructor creat ablank object.**

**you can then add properties and methods to the objet.**


# THIS (IT IS A KEYWORD) 

**The keyword this is commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates**

# RECAP: STORING DATA 

*In JavaScript, data is represented using name/value pairs. To organize your data, you can use an array or object to group a set of related values. In arrays and objects the name is also known as a key.*

# WHAT ARE BUILT-IN OBJECTS? 

**Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These built-in objects act like a toolkit for creating interactive web pages.**

*The first thing you need to do is get to know what tools are available. You can imagine that your new toolkit has three compartments:*

* BROWSER OBJECT MODEL 
The Browser Object Model contains objects that represent the current browser window or tab. It contains objects that model things like browser history and the device's screen. 

* DOCUMENT OBJECT MODEL 
The Document Object Model uses objects to create a representation of the current page. It creates a new object for each element (and each individual section of text) within the page. 

* GLOBAL JAVASCRIPT OBJECTS 
The global JavaScript objects represent things that the JavaScript language needs to create a model of. For example, there is an object that deals only with dates and times. 

* Functions allow you to group a set of related statements together that represent a single task.

* Functions can take parameters (informatiorJ required to do their job) and may return a value. 

* An object is a series of variables and functions that represent something from the world around you. 

* In an object, variables are known as properties of the object; functions are known as methods of the object. 

* Web browsers implement objects that represent both the browser window and the document loaded into the browser window.

* JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.

* Arrays and objects can be used to create complex data sets (and both can contain the other). 








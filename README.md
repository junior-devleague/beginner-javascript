#Beginner Javascript

##What is Javascript?
JavaScript is a scripting programming language used to make web pages interactive. Programming makes a computer do what you want them to by giving it a set of instructions.

JavaScript is one of **3 languages** all web developers must learn:

1.  **HTML** - marks the content up into different structural types and elements, like paragraphs, divs, lists, images, tables, forms, comments etc. 
_Think of HTML as the skeleton of your web pages._

2.  **CSS** - styles your web page by telling the browser how each type of element should be displayed. 
_Think of CSS as the skin, hair, nails, color of the eyes, clothes, shoes, etc._

3.  **JavaScript** - to program the behavior of your web pages. 
_Think of JavaScript as the director that makes everything move._

Ready to do some cool stuff? Let’s get started!

**Relationship Between HTML, CSS, and JavaScript**

The first step in getting your web page started is setting up your files. The first file you want to create is an **index.html** file. Inside the your **index.html** file is where you will link both the CSS file and your JavaScript code.

##Statements

Each instruction in JavaScript is a “statement”, for example:

```console.log('Hello World');```

Using the **console.log( )** method is the most commonly used way to show information in your console or browser. After each statement be sure to use a semicolon **;** to close out the statement. This lets the computer know that you're done with that statement or instruction.

Try it yourself on repl.it (https://repl.it/).

You can experiment logging something different like your name or a math equation such as **2+2**.

##Variables

Use **variables** to store values.

**You can declare and initialize in two statements.** You can name these variables whatever you want to name them, in this example we will call it **x**.

We will use the **console.log ()** method to check if our code is working properly.

```html
Declares the variable x
var x;
Initializes the variable at 8
x = 8;
console.log(x);
```

**Or, you can declare and initialize in one statement.**

```html
Declares and initializes in one statement
var y = 5;
console.log(y);
```

**You can reassign a value to that variable later.**

```html
var z = 4;
z = 1;
```

##Data Types

Variables can hold many data types including numbers, strings, arrays, objects and more! Let’s go over some of the common data types.

**string:** A series of characters. Strings are written within quotes, you can use single or double quotes.

```html
var greeting = 'Welcome to Paradise!'; //string using single quotes
var restaurant = "Sushi Zushi"; //string using double quotes
```

**number:** Numbers can be written with or without decimals.

```html
var age = 15;
var pi = 3.14;
```

**boolean:** Represents logical values TRUE or FALSE.

```html
var catsAreBest = true;
var dogsRule = false;
```

**undefined:** Represents a value that hasn’t been defined yet.

```var notDefinedYet;```

**null:**  Represents an explicitly empty value.

```var magicTricks = null;```

**Variable Names**
+ Begin with letters, $ or _
+ Only contain letters, numbers, $ and _
+ Case sensitive
+ Avoid reserved words
+ Choose clarity and meaning
+ Prefer camelCase for multipleWords (instead of under_score)
+ Pick a naming convention and stick with it

**OK:**

```var numPets, $mainContainer, _num, _Num;```

**NOT ok:**

```var 2coolForSchool, soHappy!```

##The Fortune Teller
_Why pay a fortune teller when you can just program your fortune yourself?_
+ Store the following into variables: number of children, partner's name, geographic location, job title.
+ Output your fortune to the screen like so: "You will be a X in Y, and married to Z with N kids."


##The Age Calculator
_Want to find out how old you'll be? Calculate it!_
+ Store your birth year in a variable.
+ Store a future year in a variable.
+ Calculate your 2 possible ages for that year based on the stored values.
+ For example, if you were born in 1988, then in 2026 you'll be either 37 or 38, depending on what month it is in 2026.
+ Output them to the screen like so: "I will be either NN or NN in YYYY", substituting the values.

##Instructor
_Assessment_
https://goo.gl/forms/eyBmF88cnBnkqMoU2

**Please let your instructor know when you are finished with this assessment!**

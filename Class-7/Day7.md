# Day 7 - Wrap-Up session

Mentored by : [Ritika Gupta](https://www.linkedin.com/in/gritika1906/)

Platforms used : [jsfiddle](https://jsfiddle.net/) and [codepen.io](https://codepen.io/collection/AQPkmq )

## Introduction to JS

JS is a programming/coding language used make web pages or a website more dynamic or functional in nature.It makes the web pages dynamic or functional through its inbuilt (already
written and stored) methods, also called inbuilt JS functions.

JavaScript is designed on a simple object-based paradigm. An object is a collection of properties, and a property is an association between a name (or
key) and a value.E.g. var person = `{firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};`

You can objects in two ways:
1. objectName.propertyName E.g. `person.lastName;`
2. objectName["propertyName"] E.g. `person["lastName"];`

Most of the inbuilt JS methods are objects in nature containing a huge list of key-value properties to manipulate web page. One Such JS object to manipulate a web page is style object. This style object has many keys like
border, minWidth, padding, margin, position, color, width, height,textTransform, overflowm overflowX, overflowY, marginBottom, marginTop,etc.

Now, the values to these keys are nothing but the ones given by a developer through css property-value set code like color:red is defined in the css style, this piece of css code will embed the value 'red' to the key 'color' in JS predefined style object; which can then be modified dynamically through JS
functions and conditions. This entire feature of JS is segregated as **JS-DOM**

JS DOM takes help of event-handlers as HTML attributes like onclick, onerror,onresize, onload etc. to execute the script written inside a JS file.

JS much alike CSS may vary in types:

When an external JS file is maintained to write a code with an extension .js, it is called an external js type and is called in the head section of HTML through a script tag as shown here script src="myscripts.js"
Another way is to declare the script functions and methods inside the script tag either in the head section or the bottom of body section on a web page.

Preferred is to place the script tag always on the bottom of the body tag because while a script loads it tends to hinder the rendering of CSS which leaves a web page without any visual effects to appear as plain distorted text
until entire script loads, and if placed in head section it will prevent all the css files called in the head section to not load until script is fully loaded.

Another type of JS object is '**document**' as it contains keys like `write`,`getElementById()`, `getElementsByClassName` etc. These keys are a function or a method in nature which further contain a piece of code pre-defined to carry
out some task, some of them may further act as object to wrap some keys and values.
E.g. 
```javascript
function changeTheme(){
if(document.getElementById('bodyWrapper').style.backgroundColor ==
"black"){
document.getElementById('bodyWrapper').style.backgroundColor = "white";
}
else{
document.getElementById('bodyWrapper').style.backgroundColor = "black";
}
```

Reference link to study JS-DOM from:
[https://www.w3schools.com/js/js_htmldom.asp]( https://www.w3schools.com/js/js_htmldom.asp)

## More To Explore!

* How to Use Developer Tools to Debug HTML/CSS and JS
* Responsive Web Designing Using Media Queries
* Developing a Print-Friendly Page in CSS using media query print
* Developing a Responsive Website/Web-page using Bootstrap
* Developing an E-mail template using HTML-4 and CSS-2
* Some more hands-on with JS-DOM
* What JQuery Does?
* LESS pre-processor
* Making Prototype Presentations with Invision
* How To use tools like zeplin, avocode, invision to pick styles from?
* And learning never stops.....

### **_Hunger to Learn serves nutrition to succeed! Keep Learning! Keep Growing!_** 

## Assessment and Certification Links

* [W3Schools CSS Quiz](https://www.w3schools.com/css/css_quiz.asp)
* [JavaTPoint HTML Quiz](https://www.javatpoint.com/html-mcq)
* [W3Schools HTML Quiz]( https://www.w3schools.com/html/html_quiz.asp)
* [W3Schools HTML Exercises](https://www.w3schools.com/html/html_exercises.asp)
* [W3Schools CSS Exercises]( https://www.w3schools.com/css/css_exercises.asp)
* [TestDome Tests]( https://www.testdome.com/tests)
* [TestDome HTML/CSS]( https://app.testdome.com/t?GeneratorId=13)
* [Template Monster Certifications](https://certification.templatemonster.com/certifications/)
* [Ranksheet Certifications]( https://ranksheet.com/Public/WhyRankSheet.aspx#exam)
* [Gymnasium Certifications](https://thegymnasium.com/courses/GYM/107/0/about)

## Study & Related Reference Links

* [FontAwesome CSS Content Code Cheatsheet and Usage Description]( https://astronautweb.co/snippet/font-awesome/)
* [Font-Awesome HTML entity code and icon name to be used in class](https://fontawesome.com/v4.7.0/cheatsheet/)
* [SASS Official Learning Website]( https://sass-lang.com/guide)
* [JavaTPoint SASS Tutorial]( https://www.javatpoint.com/sass-tutorial)
* [CSS Pseudo-Classes Cheatsheet](https://www.w3schools.com/css/css_pseudo_classes.asp)
* [HTML Symbol Entities CheatSheet](https://www.w3schools.com/html/html_symbols.asp)
